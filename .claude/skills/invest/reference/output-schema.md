# Output schema

Each phase writes `research/<TICKER>/phase-<N>.json`. `research.html` imports these, merges them by phase, and runs the valuation models from the accumulated `model` block.

Only `schema`, `meta` and `findings` are required. Everything else is optional — omit a key rather than emitting an empty or invented value. Never emit `null` for a number; leave the key out.

## Envelope

```json
{
  "schema": "invest-phase/1",
  "meta": {
    "company": "NextEra Energy, Inc.",
    "ticker": "NYSE: NEE",
    "sector": "regulated-utility",
    "currency": "USD",
    "fxToUsd": 1,
    "price": 72.40,
    "priceUnit": "share",
    "asOf": "2026-09-05",
    "phase": 1,
    "phaseName": "Regulatory & competitive architecture",
    "assumedContext": ["Phase 2 not yet run; capacity figures taken from the FY25 10-K"]
  },
  "findings": [
    {
      "id": "p1-01",
      "claim": "Florida Power & Light operates under a four-year rate settlement running through 2029.",
      "label": "REGULATORY STATUTE",
      "value": null,
      "unit": null,
      "source": "FPSC Docket 20250011-EI, order dated 2025-10-14",
      "asOf": "2025-10-14",
      "confidence": "high",
      "impact": "high"
    }
  ],
  "tables": [
    {
      "title": "Allowed ROE by jurisdiction",
      "columns": ["Jurisdiction", "Allowed ROE", "Equity ratio", "Effective"],
      "rows": [["Florida (FPL)", "11.05%", "59.6%", "2026-2029"]],
      "note": "[REGULATORY STATUTE] FPSC settlement."
    }
  ],
  "gaps":       [{"item": "…", "whyItMatters": "…", "resolvedBy": "…"}],
  "risks":      [{"text": "…", "severity": "high", "probability": "medium"}],
  "catalysts":  [{"text": "…", "window": "H1 2027", "impact": "High", "probability": 0.55}],
  "conclusions":["…"],
  "thesisImpact": "…",
  "model": {}
}
```

### Field rules

| Field | Rule |
|---|---|
| `meta.sector` | one of: `regulated-utility`, `infrastructure`, `semiconductor`, `software`, `financials`, `energy`, `healthcare`, `consumer`, `industrials`, `real-estate`, `other` |
| `meta.currency` | reporting currency, ISO code. `fxToUsd` converts one unit to USD |
| `meta.price` | current price in `currency`, per `priceUnit` (`share` or `ADR`) |
| `findings[].label` | exactly one of `FACT`, `REGULATORY STATUTE`, `MANAGEMENT GUIDANCE`, `CONSENSUS`, `ANALYST ESTIMATE` |
| `findings[].value` / `unit` | include when the finding carries a number, so the workspace can chart it |
| `findings[].source` / `asOf` | **mandatory on every finding.** No source, no finding |
| `confidence` / `impact` | `high` \| `medium` \| `low` |
| `severity` / `probability` (risks) | `high` \| `medium` \| `low` |
| `catalysts[].probability` | number 0–1 |

## The `model` block

Any phase may contribute; Phase 4 and 5 carry most of it. The workspace deep-merges blocks across phases, later phases winning. All monetary values in `meta.currency`, in **millions**, unless the key says otherwise.

```json
"model": {
  "sharesOut": 2055,
  "netDebt": 82000,
  "minorities": 0,
  "wacc":           {"bear": 0.082, "base": 0.072, "bull": 0.068},
  "terminalGrowth": {"bear": 0.005, "base": 0.020, "bull": 0.025},
  "fcf": {
    "bear": [4200, 4350, 4400, 4500, 4600],
    "base": [5100, 5600, 6100, 6600, 7100],
    "bull": [5600, 6500, 7400, 8300, 9200]
  },
  "assetBase": {
    "label": "RAB",
    "value": 141000,
    "multiple": {"bear": 1.00, "base": 1.25, "bull": 1.50}
  },
  "book": {
    "bvps": 38.20,
    "coe": 0.085,
    "growth": 0.020,
    "roe": {"bear": 0.060, "base": 0.101, "bull": 0.130}
  },
  "sotp": [
    {"name": "Regulated T&D", "method": "EV/RAB",    "metric": 141000, "multiple": 1.25, "stake": 1.0},
    {"name": "Generation",    "method": "EV/EBITDA", "metric": 12000,  "multiple": 7.5,  "stake": 1.0}
  ],
  "peers": [
    {"name": "Duke Energy", "evEbitda": 11.2, "pe": 18.1, "pb": 1.70, "ndEbitda": 5.8, "roe": 9.4, "dy": 3.9}
  ],
  "targets": {
    "bear": {"price3y": 52,  "dividends3y": 6.2},
    "base": {"price3y": 88,  "dividends3y": 7.0},
    "bull": {"price3y": 121, "dividends3y": 7.8}
  },
  "probabilities": {"bear": 0.25, "base": 0.50, "bull": 0.25},
  "weights": {"dcf": 0.45, "asset": 0.25, "pb": 0.15, "sotp": 0.15}
}
```

`weights` is your stated triangulation — Phase 5 asks which method you weight most and why, and this is how that reaches the arithmetic. Omit it to accept the defaults shown above. Weights are renormalised over the methods that actually produced a value, so a method with no inputs costs nothing. Weight the DCF down when near-term free cash flow is negative or the terminal value dominates; weight it up when cash conversion is stable and predictable. The reader can still flex any weight in the workspace, and their change wins over yours.

### What the workspace computes from it

You supply inputs; **do not pre-compute these** — the workspace does, so the arithmetic is reproducible and the user can flex any assumption:

| Output | From |
|---|---|
| DCF per share, per scenario | `fcf`, `wacc`, `terminalGrowth`, `netDebt`, `sharesOut` |
| Asset-base value per share | `assetBase.value` × `multiple`, less `netDebt` |
| Justified P/B and implied value | `(roe − growth) / (coe − growth)` × `bvps` |
| P/B × ROE sensitivity matrix | `book` |
| SOTP per share | `sotp` segments, less `netDebt` |
| Peer median multiples and implied discount | `peers` |
| Probability-weighted fair value | scenario values × `probabilities` |
| 3-year IRR per scenario | `targets`, `meta.price` |

`fcf` must be exactly five forward years. Rates are decimals (0.072, not 7.2). If a scenario is genuinely not modellable, omit that scenario key rather than filling it with the base case.

## The `memo` block — Phase 5 only

Carries the investment committee conclusions in a form the workspace renders directly. The rating you state here is shown next to the rating the arithmetic implies; if they disagree, the workspace says so, so make sure you can defend the gap.

```json
"memo": {
  "rating": "TACTICAL BUY",
  "weighting": "DCF weighted 50%, EV/RAB 30%, P/B-ROE 20% — the RAB multiple carries the regulatory verdict the DCF cannot express.",
  "nonConsensus": [
    {
      "market": "What the market currently believes",
      "us": "What we believe instead",
      "evidence": "The specific Phase 1-4 finding that separates the two"
    }
  ],
  "fears": [
    {"text": "The structural risk, stated as a bear would state it", "why": "Why it is legitimate"}
  ],
  "sellTriggers": [
    "Allowed ROE cut below 9.0% in the next rate case",
    "Net debt/EBITDA above 6.5x for two consecutive quarters"
  ]
}
```

`nonConsensus` and `fears` should each hold exactly three entries. `sellTriggers` must be measurable — a threshold and a metric, never a sentiment.

To mark the subject company inside the peer table so the workspace can compute its discount to the median, add `"self": true` to its row in `model.peers`.

## Writing the files

Write the JSON and the `.md` together, then report both paths. Validate before writing: `JSON.parse` must succeed, `findings` must be non-empty, and every finding must carry `label`, `source` and `asOf`.
