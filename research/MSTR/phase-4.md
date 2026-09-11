# Phase 4 — Capital structure, balance-sheet risk & returns on capital
## Strategy Inc. (NASDAQ: MSTR) · as of 2026-09-11

**The question:** can the balance sheet fund the plan, and does the business out-earn its cost of
capital?

---

## 4.1 The capital base and the claims ladder

### The stack, at market

| Layer | Face / par | Market value [ANALYST ESTIMATE] | Cost | Maturity |
|---|---|---|---|---|
| **Convertible notes** | $6.70bn | ~$6.0bn | ~0%–2.25% coupon; ~3.5% YTM at a discount | **2029, 2030, 2032** — no wall before 2029 |
| **Preferred (STRF, STRC, STRE, STRK, STRD)** | ~$14.80bn | ~$13.5bn | **~11.9%** current yield on market value | **Perpetual — no maturity at all** |
| **Common equity** | — | **$49.36bn** | 18.0% (Phase 1) | Residual |
| **Total capital** | | **~$68.9bn** | | |

[FACT] Convertible balance $6.70bn at 2026-06-30, reduced 18% in the quarter; 2029 notes convert at
$672.40 and 2030s at $433.43, both far out of the money at $128.48. Preferred par per Phase 1 §1.2.
Market values are estimates: STRC trades below its $100 stated amount, and the May 2026 convertible
repurchase cleared at 92 cents on the dollar.

### Two genuine structural strengths, stated before the criticism

1. **There is no maturity wall and no margin call.** The preferred is perpetual — it can never be put
   back to the company. The converts do not mature until 2029 at the earliest. **No debt is secured on
   the bitcoin.** Strategy absorbed a ~33% bitcoin drawdown in H1 2026 — the holding fell from $51.6bn
   at 2026-03-31 to $49.7bn at 2026-06-30 *while adding 11% more coins* — without a forced sale. A
   levered fund with the same exposure and a repo book would not have survived it.
2. **Deleveraging is available and is being used.** $1.50bn of 2029 converts was repurchased for
   $1.38bn in May 2026, and the convertible balance fell 18% in a single quarter.

Those two facts are why this phase does not conclude in a solvency warning. The problem is not that
Strategy breaks. It is what it costs to not break.

### The wipe-out price

| | |
|---|---|
| Senior claims: converts $6.70bn + preferred $14.80bn | **$21.50bn** |
| Less USD reserve $2.40bn and software ~$1.50bn | **($3.90bn)** |
| Bitcoin value required to cover the claims | **$17.60bn** |
| ÷ 845,256 BTC | |
| **Bitcoin price at which common equity is worth zero** | **≈ $20,820** |
| Distance from spot ($77,000) | **−73%** |

[ANALYST ESTIMATE] derivation shown; static, before any bleed from dividend-funded sales.

**The common equity is not near a zero.** A 73% bitcoin decline is required, and bitcoin has done that
before. But the more useful reading is the reverse: **$21.5bn of the $65.1bn bitcoin stack — 33% of it —
already belongs to someone else.**

---

## 4.2 Debt capacity, and the constraints that bind before the market does

| Constraint | Current position | Headroom |
|---|---|---|
| **Covenants** | None disclosed on the converts or preferred `[GAP]` | Assume non-binding |
| **Maturity schedule** | No maturities before 2029; a holder put on the 2032 notes at 2029-06-15 | ~3 years clear |
| **Secured debt / margin calls** | **None** | Not applicable — the key structural protection |
| **S&P Global issuer rating** | **B− , stable** (2025-10-27), citing "high bitcoin concentration, narrow business focus, weak risk-adjusted capitalization, and **low U.S. dollar liquidity**"; upgrade explicitly unlikely within 12 months | The rating is the constraint on the *price* of new capital, not on access |
| **USD liquidity** | **$2.40bn** against $1,633m of annual cash carry | **~17.6 months** with zero issuance and zero bitcoin sales |
| **The mNAV gate** | **1.04x — economically shut** | The binding constraint. See Phase 3 |
| Statutory issuance cap | None | n/a |

### The funding gap

| $m | FY2026E | FY2027E |
|---|---|---|
| Software operating cash flow | ~+25 | ~+25 |
| − Preferred dividends | (1,603) | (1,603) *before any ratchet* |
| − Convertible interest | (30) | (30) |
| − Bitcoin purchases | discretionary, currently ~0 | discretionary |
| **= Funding gap before financing** | **(1,608)** | **(1,608)** |
| Covered by | USD reserve ($2.40bn), preferred ATM, or **bitcoin sales** | Same, with a smaller reserve |

[ANALYST ESTIMATE] built on Phase 2 and Phase 3.

**The gap is structural, not cyclical.** It does not close if bitcoin rallies — a higher bitcoin price
does not generate a single dollar of cash. It only makes the gap easier to fund, by reopening the
equity ATM. **This is the defining feature of the credit: an asset that cannot service its own
liabilities in any state of the world.**

---

## 4.3 Mandatory sensitivities

### (a) Interest rates +100bp / +200bp

| Channel | +100bp | +200bp |
|---|---|---|
| **Floating-rate debt** | **$0** — there is none | $0 |
| **Convertible interest** | $0 — fixed to 2029+ | $0 |
| **STRC repricing.** The board's monthly reset explicitly references credit spreads; a risk-free move transmits within two to four resets at up to 0.25% each | **+$105m/yr** per 1% on $10.5bn | **+$210m/yr** |
| Full preferred stack repricing over time | +$148m/yr | +$296m/yr |
| **Cost of equity** | 18.0% → ~19.0%, compressing the justified premium to NAV | 18.0% → ~20.0% |
| **Second-order: bitcoin** | Higher real rates have historically been bitcoin-negative; this is the dominant channel and is not modellable here | — |

**Direct P&L sensitivity to rates is close to zero, which is a genuine strength.** The exposure is
indirect and runs through the STRC reset and the bitcoin price.

### (b) A 10% move in the functional asset

Strategy reports in USD, but its economic functional currency is bitcoin. The protocol's
"10% depreciation of the reporting currency" maps to a 10% move in BTC.

| Shock | Bitcoin value | NAV to common | Change | Carry as % of stack |
|---|---|---|---|---|
| **BTC +10% → $84,700** | $71.59bn | $53.99bn | **+13.7%** | 2.28% |
| **Spot, $77,000** | $65.08bn | $47.48bn | — | 2.51% |
| **BTC −10% → $69,300** | $58.57bn | $40.97bn | **−13.7%** | 2.79% |
| **BTC −33% → $51,600** (repeat of H1 2026) | $43.62bn | $26.02bn | **−45.2%** | 3.74% |

**A 10% bitcoin move is a 13.7% NAV move — that is the 1.37x leverage, and it is symmetric.** What is
*not* symmetric is the premium: the peer evidence (Semler 0.88x, Nakamoto 0.70x, Metaplanet 0.99x)
shows that treasury-company premiums compress in drawdowns and do not expand symmetrically in rallies.
A −10% bitcoin move plus a premium compression from 1.04x to 0.90x is a **−25% equity move**.

**Genuine FX exposure, small but real:** STRE is euro-denominated (~€775m). A 10% euro appreciation
raises the USD liquidation preference by roughly $90m and the annual dividend by ~$9m.

### (c) The input-cost shock: the cost-of-capital ratchet

For Strategy the "fuel cost" is the dividend rate, and the relevant historical episode is the one that
already happened.

| Episode | STRC rate | Annual carry on $10.5bn | Change |
|---|---|---|---|
| Listing, July 2025 | **9.00%** | $945m | — |
| Spring 2026 | 11.50% | $1,208m | +$263m |
| **September 2026** | **12.00%** | **$1,260m** | **+$315m vs listing** |
| Repeat the same +300bp move | 15.00% | $1,575m | **+$630m vs listing** |
| Whole preferred stack +300bp | — | +$444m/yr across ~$14.8bn | — |

[FACT] rate history per company announcements. [ANALYST ESTIMATE] the repeat scenario.

**The cost of Strategy's largest funding source has risen 33% in fourteen months, and the mechanism that
raised it is a one-way ratchet.** Each trip below $95 adds ~$53m a year permanently. A repeat of the
move already observed adds $630m a year — 39% more carry — and it would arrive in precisely the states
of the world where bitcoin is falling.

---

## 4.4 ROIC vs WACC — the only test that matters

### WACC

| Layer | Market value | Weight | Cost | Contribution |
|---|---|---|---|---|
| Common equity | $49.36bn | 71.7% | **18.0%** | 12.90pp |
| Preferred | ~$13.50bn | 19.6% | **11.9%** | 2.33pp |
| Convertibles | ~$6.00bn | 8.7% | **3.5%** | 0.31pp |
| **WACC** | **$68.86bn** | 100% | | **≈ 15.5%** |

[ANALYST ESTIMATE] Cost of equity derived in Phase 1 §1.4 (risk-free 4.79% + beta ~2.9 × ERP 4.5%).
Preferred cost = $1,603m of dividends over an estimated $13.5bn of market value. Convertible cost is a
yield-to-maturity estimate on a discounted, deep-out-of-the-money bond. **No tax shield is applied:**
preferred dividends are not deductible, and Strategy has no taxable income against which to deduct
convertible interest.

### ROIC

Strategy's invested capital is bitcoin, and its return on that capital is the bitcoin return. There is
no operating return to measure — which is itself the finding.

| Measure | Value | Source |
|---|---|---|
| Capital deployed into bitcoin, cumulative | **$63.73bn** | [FACT] |
| Current market value | **$65.08bn** | [FACT] at $77,000 |
| **Cumulative return on all capital deployed** | **+2.1%** | Derived |
| Simple annualisation over the ~6.1-year programme | **~+0.34%/yr** | Derived; crude, and flattered by cheap early vintages |
| **WACC** | **15.5%** | Above |
| **SPREAD** | **≈ −15.2 percentage points** | |

### The reported record

| Period | Net income | Driver |
|---|---|---|
| FY2025 | **+$3.80bn** | Bitcoin $87,515 at year-end; revenue $477m |
| Q1 2026 | **−$12.54bn** | A **$14.46bn** unrealised markdown — the largest loss in company history |
| Q2 2026 | **−$8.60bn** | Operating loss $8.3bn, again bitcoin fair value |
| **H1 2026** | **−$21.14bn** | |

[FACT] FY2025 10-K; Q1 2026 results 2026-05-05; Q2 2026 results 2026-07-30. Under **ASU 2023-08** the
income statement is a bitcoin price chart, which means GAAP earnings carry no information about the
business and, per Phase 1, disqualify Strategy from the S&P 500.

**`[GAP]`, and it is the protocol's ten-year test:** a full decade of ROIC and WACC could not be
constructed. Bitcoin holdings and convertible balances before FY2025 were not retrievable under this
session's egress policy. What can be said is that the spread was **enormously positive from 2020 to
2024** — Strategy bought bitcoin at an average well below $75,417 with capital costing ~0.4% — and has
been **deeply negative since the preferred stack was built in 2025**. The inflection is not gradual; it
coincides with the funding mix shift documented in Phase 2 §2.2.

### The test that actually decides the investment: does the wrapper beat the asset?

This is the calculation that matters, and it is available only because spot bitcoin ETFs now exist.

```
Bitcoin exposure                   $65.08bn
NAV attributable to common         $47.48bn
LEVERAGE                           1.37x

Annual cash carry                  $1,633m
As a % of common NAV               3.44%

Expected MSTR NAV return  =  1.37 × r  −  3.44%
Expected spot ETF return  =  1.00 × r  −  0.20%

Breakeven (ignoring the entry premium):
        1.37r − 3.44%  =  r − 0.20%
        0.37r = 3.24%   →   r = 8.8%

Breakeven (paying today's 1.04x premium, decaying to 1.00x over three years ≈ −1.3%/yr):
        1.37r − 3.44% − 1.30%  =  r − 0.20%
        0.37r = 4.54%   →   r = 12.3%
```

| Bitcoin CAGR | MSTR NAV return (1.37x − 3.44%) | Spot ETF (−0.20%) | **MSTR advantage** |
|---|---|---|---|
| −20% | −30.8% | −20.2% | **−10.6pp** |
| −10% | −17.1% | −10.2% | **−6.9pp** |
| 0% | −3.4% | −0.2% | **−3.2pp** |
| **+10%** | **+10.3%** | **+9.8%** | **+0.5pp** |
| +20% | +24.0% | +19.8% | +4.2pp |
| +40% | +51.4% | +39.8% | +11.6pp |

**The finding, stated plainly: bitcoin must compound at more than roughly 12% a year — including the
cost of today's 4% entry premium — for Strategy's common stock to beat simply owning bitcoin.** Below
that, the wrapper subtracts. Above it, the leverage pays, and pays increasingly.

That is a clean, falsifiable, entirely quantitative statement of the investment case, and it is the
only one that matters.

### What it would take for the spread to turn durably positive

| Condition | Required | Currently | Plausible? |
|---|---|---|---|
| **Bitcoin compounds above 15.5% (the WACC)** | A bull market | −12% year to date; +2.1% over six years | **Possible, and it has happened repeatedly. This is the whole bull case** |
| **Retire the 12% preferred** | ~$10bn of cash to take WACC to ~10% | No cash to do it with; the software business is worth ~$1.5bn | **Low** without a bitcoin rally first |
| **mNAV back above ~1.2x** | Restores common issuance as cheap capital — at 3.89x, issuing equity had an effectively *negative* cost | 1.04x | **Medium.** Requires bitcoin higher first |
| **Bitcoin volatility falls** | Would cut the 18% cost of equity | No evidence of it | Low |

**Cyclical or structural?** This compression is **cyclical, with one permanent structural overlay.**

- *Cyclical:* everything about the mNAV gate, the carry ratio and the preferred repricing reverses on a
  bitcoin rally. A 50% bitcoin move takes the carry from 2.51% to 1.67% of the stack, re-rates the
  equity above NAV, reopens the ATM, and restarts the accretion machine. Nothing is permanently broken.
- *Structural and permanent:* **the spot ETF.** When Strategy was the only regulated way to hold bitcoin
  in a brokerage account, a large premium was rational. That monopoly is gone and will not return. Any
  future premium must be earned by the *leverage and the issuance machine alone*, not by access — which
  caps how high it can durably go.

---

## What this phase establishes

1. **The balance sheet does not break, and that is a real finding.** No secured debt, no margin calls,
   no maturities before 2029, perpetual preferred that cannot be put back. Strategy absorbed a 33%
   bitcoin drawdown in H1 2026 without a forced sale. Common equity is wiped out only at bitcoin
   **≈ $20,820**, 73% below spot.
2. **WACC is ~15.5% and the return on invested capital is ~0.3% a year.** A spread of roughly
   **−15 percentage points**, and the inflection coincides exactly with the 2025 build-out of the
   preferred stack, not with anything that happened to the business.
3. **33% of the bitcoin stack already belongs to someone else** — $21.5bn of senior claims against a
   $65.1bn asset — and the claims accrue at ~11.9% while the asset yields nothing.
4. **MSTR is a 1.37x levered claim on bitcoin carrying a 3.44% annual fee on common NAV.** Including
   the 4% entry premium, **bitcoin must compound above ~12% a year for the wrapper to beat a spot ETF.**
   That single number is the investment case.
5. **The compression is cyclical, with one permanent overlay.** Everything reverses on a bitcoin rally
   except the existence of the spot ETF, which permanently caps the durable premium.

## What it could not establish

| Gap | Ranked by valuation dependence | Resolved by |
|---|---|---|
| **Exact preferred balance and market value** | The largest single input to leverage, WACC and the wipe-out price. A $1bn error moves NAV per share by $2.60 and the leverage ratio by 0.03x | Q3 2026 10-Q equity note |
| **Ten-year ROIC and WACC series** | The protocol's core test could only be run for 2025–26. Pre-2025 bitcoin holdings and convertible balances were not retrievable | FY2023/FY2024 10-Ks — egress-blocked |
| **Covenant terms on converts and preferred** | Would confirm that nothing binds before the rating does. Currently assumed, not verified | Indentures and certificates of designation |
| Software segment operating income | The only recurring cash inflow; modelled at ~$25m | Segment disclosure |
| Whether the STRC ratchet has triggered, and how often | Each trigger is ~$53m/yr permanently added to the carry | Dividend announcements and the 10-Q |
| Market prices of each preferred series | Preferred market value is estimated at ~$13.5bn against ~$14.8bn par; this sets the cost of preferred in the WACC | Live quotes for STRK/STRF/STRD/STRC/STRE |

## What it changes about the thesis

Phase 3 said the structure bleeds 2.51% of the bitcoin stack a year. Phase 4 prices that bleed against
the alternative and finds the number the entire decision turns on: **bitcoin above ~12% a year and the
wrapper wins; below it, the wrapper loses to an instrument any investor can buy for 20 basis points.**

It also removes the tail risk that would otherwise dominate: **this is not a forced-seller story.** There
is no margin call, no maturity wall and no covenant to breach. Strategy can bleed for years. The
question for Phase 5 is therefore not solvency. It is whether a 1.37x levered, 3.44%-fee bitcoin wrapper
trading at 1.04x its own liquidation value is worth owning — and at what price it would be.
