# Phase 4 — Capital structure, balance sheet risk & returns on capital

**The question:** can the balance sheet fund the plan, and does the business out-earn its cost of capital?

## 4.1 The capital base and its allowed return

- Size the invested capital base. For regulated businesses this is the **Regulated Asset Base**: current size, the allowed rate of return and authorised ROE, the regulatory depreciation profile, and the lag between spending and earning on it.
- **How much of the forward capex enters the rate base, and when?** Capex admitted to the base at an allowed return is an earnings annuity. Capex disallowed, deferred, or spent ahead of a rate case is a hole. Split the programme between the two and quantify each.
- For unregulated businesses, use invested capital: net PP&E + working capital + capitalised intangibles, and the incremental return on new investment.
- Where a bank: CET1, risk-weighted assets, and the capital consumed per unit of loan growth.

## 4.2 Debt capacity and the ceiling

- Total net debt, gross debt, and the maturity profile year by year. Identify the walls.
- Average cost of debt, fixed/floating split, currency composition, and the refinancing schedule against the current rate curve.
- **Constraints that bind before the market does**: statutory issuance caps, covenant thresholds, rating-agency downgrade triggers, regulatory gearing limits. State the current headroom in absolute terms and as a percentage — and how many years of the capex plan that headroom funds. Where a statutory bond-issuance ceiling exists, compute the exact distance to it.
- Funding gap: capex plan + dividends + maturities − operating cash flow. If the gap exceeds headroom, the equity is the plug. Say so.

## 4.3 Mandatory sensitivities

Model and tabulate:

| Shock | Model |
|---|---|
| Rates +100 bps / +200 bps | Effect on interest expense and pre-tax income, phased by the refinancing schedule — not applied to the whole stock at once |
| 10% depreciation of the reporting currency | Input/import costs, hard-currency debt service and translation, net operating margin effect |
| Input cost shock | The move that matters for this sector (fuel, feedstock, wages, funding cost), sized to a real historical episode |

Show each as a table with the transmission mechanism, not a single number.

## 4.4 ROIC vs WACC — the only test that matters

- Compute **ROIC over a full historical cycle, ten years where data allows**, alongside estimated WACC for the same years. Tabulate the spread annually. Be explicit about the ROIC definition used (NOPAT / average invested capital) and hold it constant.
- A business that has earned below its cost of capital for a decade requires an extraordinary claim to justify assuming it will not continue to.
- **State the exact conditions under which the spread turns durably positive**: what tariff, price, mix, utilisation or cost outcome is required, individually and in combination. Then assess how plausible each is on the evidence from Phases 1–3.
- Distinguish a cyclical recovery in the spread from a structural one. Only the structural case supports a re-rating.

## Required output

- Capital base table: size, allowed return, capex entering the base by year.
- Debt table: maturity ladder, cost, currency, fixed/floating.
- Headroom table against every binding constraint.
- Three sensitivity tables.
- Ten-year ROIC vs WACC table with the spread, and the conditions for a durable positive spread.

Populate `model.netDebt`, `model.assetBase`, `model.wacc`, and `model.book`.
