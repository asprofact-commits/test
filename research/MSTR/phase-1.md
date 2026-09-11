# Phase 1 — Pricing-power architecture
## Strategy Inc. (NASDAQ: MSTR) · Bitcoin treasury + enterprise software · USD · as of 2026-09-11

**Price used throughout: $128.48 (close, 2026-09-10). 52-week range $81.81–$365.21.**
[FACT] Quote per market-data pages retrieved 2026-09-11; Sept 10 intraday range $126.91–$131.88;
Sept 8 close $137.57. Bitcoin fell a further ~2% on the morning of 2026-09-11 to ~$76,800–77,700.

> **Environment note.** Every external domain except the search index is blocked by this session's
> network egress proxy (`CONNECT tunnel failed, response 403` against `data.sec.gov` and
> `strategy.com`; `WebFetch` returns `EGRESS_BLOCKED`). No 10-Q, 10-K or 424B5 was retrievable
> directly. Figures below that originate in Strategy's filings are labelled `[FACT]` and sourced to
> the filing, but reached this analysis through search-index summaries of those documents. See
> `.claude/skills/invest/reference/network-access.md`. For a company whose entire valuation is a
> balance-sheet arithmetic problem, this is a more serious limitation than it would be elsewhere, and
> the `[GAP]` list at the end of each phase should be read as load-bearing.

> **Sector note.** No sector profile fits cleanly. Strategy is run through the **financials** profile:
> the "asset base" is the bitcoin holding, prudential-style constraints are the preferred stack and
> the rating, and — per that profile — **Phase 5 uses P/NAV as primary and does not run an EV/FCF
> DCF.** The reasoning is set out in Phase 5 §5.3.

---

## 1.1 What is actually being priced

Strategy sells almost nothing. Software revenue was **$122.37m in Q2 2026** and **$124.3m in Q1 2026**
(+11.9% y/y), against **$477m for FY2025** [FACT, Q1/Q2 2026 results and FY2025 10-K]. That is 0.7% of
the enterprise. The other 99.3% is **845,256 bitcoin** [FACT, holdings as at the 2026-08-31 purchase of
4,600 BTC].

So the Phase 1 question — *who sets this company's price, and what can override that?* — has to be
asked about the thing that actually determines the equity's value. That is not an output price. It is
the **price of Strategy's input capital, measured against the return on the asset it buys.** The whole
business model is a single spread:

```
Value created  =  (return on bitcoin)  −  (cost of the capital used to buy it)
```

Everything in this phase is about who sets each term.

### The mechanism: reflexive issuance against mNAV

Strategy's core machine is the at-the-market equity programme, and its economics are governed by one
ratio — **mNAV**, the market value of the enterprise divided by the market value of the bitcoin it holds.

| mNAV | What issuing equity does | Observed behaviour |
|---|---|---|
| **> 1.0** | Each share sold buys more bitcoin than it dilutes → **bitcoin per share rises** | ATM runs at full speed. Q2 2026 alone raised **$8.41bn** of gross ATM proceeds, plus $1.28bn in the first 26 days of July |
| **≈ 1.0** | Neutral. Management has indicated issuance below roughly **1.22x** can already be value-destructive per share once fees and timing are counted | |
| **< 1.0** | Each share sold buys **less** bitcoin than it dilutes → **bitcoin per share falls** | **The ATM stops.** Strategy paused open-market bitcoin purchases for roughly ten weeks from mid-June 2026, resuming only on 2026-08-31 |

[FACT] ATM proceeds per Q2 2026 10-Q; the purchase pause and its resumption per market reporting,
June–September 2026. [MANAGEMENT GUIDANCE] the ~1.22x threshold.

**This is a reflexive loop, and in 2026 it reversed.** The premium existed because issuance at a
premium grew bitcoin per share; bitcoin per share grew because there was a premium. Strategy's mNAV
reached **3.89x in November 2024** [FACT, market data]. It fell **below 1.0 in late June 2026** — the
first time in the cycle — at which point the machine that justified the premium switched off, which
removed the reason for the premium. Published readings now cluster at **1.13x–1.16x** on some
definitions and at or below 1.0x on enterprise definitions [FACT, mnav.com and Investing.com,
2026; CoinDesk 2026-06-27].

Those published figures disagree because "mNAV" has no standard definition. My own bridge, built from
disclosed components, is in §1.4 and lands at **1.04x**. What matters for Phase 1 is not the second
decimal. It is that **the premium is gone**, and with it the mechanism by which Strategy created value.

### The second price: STRC, and who really sets the cost of capital

Strategy funds itself increasingly through perpetual preferred stock, of which **STRC ("Stretch") is
now by far the largest at roughly $10.5bn outstanding** [FACT, September 2026]. STRC is the most
important instrument in the capital structure and its pricing mechanism is explicit:

| Feature | Mechanic |
|---|---|
| Stated amount | $100 per share; the instrument is **managed to trade at par** |
| Dividend | Variable, paid semi-monthly; the **board resets the rate monthly**, in increments of up to 0.25%, with reference to trading price, credit spreads, bitcoin volatility and USD reserve coverage |
| **The ratchet** | If STRC trades **below $95**, the dividend rises by **0.5 percentage points — and the increase cannot be reversed even if the price recovers.** Each trigger adds roughly **$53m** of annual obligation |
| Rate history | **9.00%** at listing (July 2025) → **11.50%** (spring 2026) → **12.00%** (September 2026, held from the prior month) |

[FACT] STRC terms per Strategy's STRC information page and the 424B5; rate history per company
announcements and reporting, July 2025 – September 2026. STRC has been trading **below par**.

Read the mechanic carefully. The board nominally sets the rate; in substance **the market sets it**,
because the board's mandate is to keep STRC at $100 and the ratchet punishes failure asymmetrically.
Strategy's cost of capital is therefore determined by a **monthly auction it does not control, with a
one-way ratchet**. The rate has risen 300 basis points in fourteen months — a 33% increase in the cost
of the company's largest funding source — while the return on the asset it funds has gone negative.

**That is the answer to Phase 1's question, and it is the opposite of pricing power.** Strategy is a
price-taker on both sides: it takes the bitcoin price on the asset side, and it takes the market's
required yield on the liability side. There is no statute, contract, switching cost or network effect
anywhere in the structure that lets it set either.

---

## 1.2 Price differentiation across the capital stack

Strategy does differentiate — not by geography or customer class, but by **security**. Each instrument
sells a different slice of the same bitcoin to a different buyer at a different price.

| Instrument | Stated rate | Approx. outstanding | Seniority | What it sells |
|---|---|---|---|---|
| **STRF** (Strife) | 10.0% fixed, cumulative, quarterly | ~$1.28bn | **1st** | The safest claim on the stack |
| **STRC** (Stretch) | **Variable, 12.00% in Sept 2026** | **~$10.5bn** | 2nd | A par-stable, high-yield cash instrument |
| **STRE** (Stream) | ~10%, €-denominated, LuxSE-listed | ~$0.9bn (€) | 3rd | European yield buyers |
| **STRK** (Strike) | 8.0%, convertible into MSTR | ~$0.7bn `[GAP]` | 4th | Yield plus equity upside |
| **STRD** (Stride) | 10.0%, **non-cumulative** | ~$1.40bn | 5th | The most junior, highest-risk preferred |
| **Convertible notes** | ~0%–2.25% coupon | **$6.70bn** | Senior debt | Cheap money against a call on MSTR |
| **MSTR common** | — | ~384m shares | Residual | Levered bitcoin |

[FACT] Preferred share counts as at 2026-03-19 per the FY2025 10-K securities exhibit: STRF
12,839,689; STRC 50,246,513; STRE 7,750,000; STRD 14,024,221 — all at $100 (or €100) stated amount.
STRC rolled forward to ~$10.5bn on September 2026 reporting. Convertible debt $6.70bn at 2026-06-30,
**reduced 18% in the quarter** [FACT, Q2 2026 results].

**Model both legs.** The differentiation is genuinely clever financial engineering — five instruments,
five buyer bases, one asset — and it has raised extraordinary sums: **$25.3bn in calendar 2025**, the
largest equity issuance of any US public company for a second consecutive year, and **$11.68bn in the
first four months of 2026**, the largest US equity issuance of 2026 [FACT, company disclosure and
reporting]. But the revenue leg and the cost leg move together, and only one of them is contractual:

```
Revenue leg (bitcoin return)        variable, unbounded both ways, currently NEGATIVE
Cost leg (preferred dividends)      FIXED IN CASH, ratcheting upward, ~$1.60bn/yr
```

Q2 2026 preferred dividends were **$400.7m** [FACT, Q2 2026 10-Q] — a **$1.60bn annual run-rate**
against software revenue of ~$495m. The cost leg is roughly **3.2x total revenue.**

### The 2029 convertible repurchase — the one genuinely accretive act of 2026

On 2026-05-19 Strategy repurchased and cancelled **$1.50bn principal of the 0% 2029 convertibles for
$1.38bn**, an 8% discount, leaving $1.50bn outstanding [FACT, company press release 2026-05-15 and
Q2 2026 10-Q]. The 2029s convert at **$672.40**; the 2030s at **$433.43** [FACT]. Against a $128.48
share price, **every convertible in the structure is far out of the money** — which means none of them
will convert to equity, and all of them are debt that must be refinanced or repaid in cash.

---

## 1.3 The statutory architecture

Unusually for this protocol, Strategy's binding rules are **accounting standards and index rules**,
not regulators. Four events since late 2025 define the envelope, and three of the four went Strategy's
way.

| Rule / decision | Date | Holding | Equity impact |
|---|---|---|---|
| **ASU 2023-08** — fair value measurement of crypto | Adopted 2025 | Bitcoin marked to market each period, with gains and losses **through net income** | The reason Q1 2026 showed a **$12.54bn net loss** on a **$14.46bn** unrealised markdown, and Q2 2026 a **$8.6bn** net loss. Earnings are now a bitcoin price chart |
| **CAMT interim guidance** — Treasury/IRS | **2025-09-30** | A corporation **may disregard unrealised gains and losses on digital assets** when computing adjusted financial statement income for the 15% corporate alternative minimum tax | **Removed a multi-billion-dollar tax liability** that would otherwise have begun in 2026 on paper gains. The single largest favourable statutory event in the company's history |
| **MSCI index consultation** | Proposal Dec 2025; **decision 2026-01-15** | MSCI **declined to exclude** digital-asset treasury companies from its Global Investable Market Indexes, deferring exclusions and size changes, and opening a **broader consultation on "non-operating companies"** | Removed an estimated **$8.8bn–$15bn** of forced outflows. Strategy was **74.5% of the $113bn** of affected float. **The overhang is deferred, not extinguished** |
| **S&P 500 / Nasdaq-100** | 2026 | **Still excluded from the S&P 500** — the index committee will not admit a company whose income is pure asset exposure, and GAAP losses disqualify it on the earnings test. **Retained in the Nasdaq-100** at the annual reconstitution | Index demand is capped. The largest passive bid available to a US mega-cap is structurally closed to it |
| **S&P Global issuer credit rating** | 2025-10-27 | **B− , stable** — citing "high bitcoin concentration, narrow business focus, weak risk-adjusted capitalization, and low U.S. dollar liquidity" | First bitcoin-treasury company rated by a major agency. **Junk.** Upgrade explicitly unlikely within twelve months |

[REGULATORY STATUTE / FACT] sources: FASB ASU 2023-08; Treasury/IRS interim guidance 2025-09-30 and
Strategy's 8-K response; MSCI consultation outcome January 2026; S&P Global Ratings, 2025-10-27.

**The asymmetry worth noting:** Strategy won the tax fight and won the index fight, and the equity is
still down roughly 65% from its 52-week high. The problems are not regulatory. They are arithmetic.

---

## 1.4 Ownership, governance and the NAV bridge

### Control

| Class | Shares | Votes/share | Votes | Share of votes |
|---|---|---|---|---|
| Class A | **326,581,627** (2026-04-01) | 1 | 326.6m | 62.4% |
| Class B (Saylor and affiliates) | **19,640,250** (2026-04-01) | 10 | 196.4m | 37.6% |

[FACT] Share counts per the 2026 definitive proxy statement, as at 2026-04-01.

**Michael Saylor no longer holds majority voting control.** It fell below 50% on or shortly after
2024-11-12 because the ATM issued so many Class A shares that Class A voting power overtook Class B
[FACT, company 8-K disclosure, November 2024]. **Strategy no longer qualifies for the Nasdaq
"controlled company" exemption** and must comply with the full independent-director and committee
requirements.

This is the mirror image of the usual finding in this protocol. Most founder-controlled companies
concentrate power as they grow; **Strategy dilutes its founder's control every time it executes its
strategy.** The strategy is self-diluting by construction — of votes, and, once mNAV falls below 1.0,
of bitcoin per share as well.

Class A has grown further since April (reported shares outstanding now ~**384.2m**, with ~**419.9m**
fully diluted as at late August 2026 [FACT]), so Saylor's voting share is now nearer **35%**. He
retains effective control in practice through the board and the absence of any organised opposition,
but not as a matter of right.

### The NAV bridge — the single most important table in this analysis

Built from disclosed components at bitcoin **$77,000** (2026-09-11):

| Component | $bn | Basis |
|---|---|---|
| Bitcoin: 845,256 BTC × $77,000 | **65.08** | [FACT] holdings; [FACT] BTC price 2026-09-11 |
| + USD reserve (cash $1.71bn + short-term investments $0.74bn) | **2.40** | [FACT] 2026-06-30 |
| + Software business | **1.50** | [ANALYST ESTIMATE] ~3.0x ~$495m FY2026E revenue |
| **= Gross assets** | **68.98** | |
| − Convertible notes | **(6.70)** | [FACT] 2026-06-30 |
| − Preferred liquidation preference | **(14.80)** | [ANALYST ESTIMATE], range $13.9–15.5bn |
| **= NAV attributable to common** | **47.48** | |
| ÷ shares outstanding (384.2m) | | |
| **= NAV per share** | **$123.56** | |
| **Price / NAV** | **1.04x** | at $128.48 |

**The market is paying a 4% premium to liquidation value for the common.** For an entity whose only
function is to hold an asset anyone can buy directly, at a 0.2% annual fee, through a spot ETF, a 4%
premium is the entire equity story — and §1.5 shows it is not free.

### Cost of the bitcoin, six years in

| | |
|---|---|
| Bitcoin acquired | 845,050 BTC for **$63.73bn** [FACT, as at the 2026-08-31 purchase] |
| **Average cost** | **$75,417** per bitcoin |
| Price today | **$77,000** |
| **Cumulative gain on the entire programme** | **+2.1%, or ~$1.34bn** |

After six years and $63.7bn deployed, **the whole bitcoin position is approximately 2% above cost.**
At quarter-end on 2026-06-30 it was *below* cost, with bitcoin at roughly $58,700 [FACT: bitcoin
holdings market value fell from $51.6bn at 2026-03-31 to $49.7bn at 2026-06-30 on a holding that grew
11%]. That is the return the capital structure in §1.2 has to be serviced out of.

### The structural discount

Strategy's premium ran from **3.89x (November 2024)** to **below 1.0x (June 2026)** to **~1.04x today**.
It is not alone: Metaplanet trades at **0.99x**, Semler Scientific at **~0.88x**, Nakamoto at **~0.70x**
after a 96% decline from peak, BitMine at **1.01x**, and **more than 15% of digital-asset treasuries
now trade below 1.0x** [FACT, treasury-tracker and press data, 2026].

**Is there a catalyst that dissolves the discount?** The honest answer is that the premium was never a
governance discount to be closed — it was an **operating premium earned by accretive issuance**, and it
can only return if accretive issuance returns, which requires the premium to exist first. That
circularity is why the premium collapsed so completely and so quickly across the entire sector, and why
a specific, dateable catalyst for its return cannot be named. What *can* be named is the condition:
**a bitcoin price high enough that MSTR's option-like equity re-rates above 1.0x NAV**, restarting the
loop. That is a bet on bitcoin, not on Strategy.

---

## Required output: can this company raise price to cover cost, and who decides?

**No, and nobody at Strategy decides either side of it.**

- **The asset return** is the bitcoin price. Strategy has no influence over it. It is −12% year to
  date (bitcoin $87,515 at 2025-12-31 → ~$77,000 today) and the company's entire six-year position is
  2% above cost.
- **The cost of capital** is set monthly by the STRC market, with a one-way ratchet, and has risen from
  9.00% to 12.00% in fourteen months.
- **The one lever Strategy did control — issuing equity at a premium — is switched off**, because the
  premium is gone. The ATM stopped for ten weeks from mid-June.

The spread that defines the business is therefore **negative today**: a roughly 0–2% realised asset
return against an 11–12% marginal cost of preferred capital. The company is meeting the difference by
**selling bitcoin** (see Phase 3), which is the mechanical opposite of the thesis it was built on.

**Cost-of-equity view formed here: 18.0%.** Derivation: risk-free 4.79% (US 10-year, early September
2026) + an equity beta of ~2.9 against a 4.5% equity risk premium. The beta is not a regression — it is
structural: the common is a **1.37x levered claim on bitcoin** (§ Phase 4), and bitcoin's realised
volatility is multiples of the equity market's. 18% is if anything conservative.

---

## What this phase establishes

1. **Strategy is a price-taker on both sides of its only spread.** It takes the bitcoin price on the
   asset side and the STRC market's required yield on the liability side. There is no pricing power
   anywhere in the structure.
2. **The reflexive flywheel reversed in June 2026.** mNAV fell below 1.0 for the first time in the
   cycle, issuance became dilutive to bitcoin per share, and the ATM stopped for ten weeks. The
   mechanism that created the premium requires the premium to exist.
3. **The cost of capital ratchets and does not un-ratchet.** STRC's rate has gone 9.00% → 11.50% →
   12.00% in fourteen months, with a contractual +0.5% trigger below $95 that cannot be reversed. The
   preferred dividend run-rate is **$1.60bn/yr against ~$495m of total revenue**.
4. **Six years and $63.73bn of bitcoin purchases have produced a ~2% gain.** The average cost is
   $75,417 against ~$77,000 today, and the position was underwater at the last quarter-end.
5. **The statutory news was good and it did not matter.** CAMT relief (Sept 2025) removed a
   multi-billion tax liability and MSCI declined to exclude (Jan 2026), yet the equity is ~65% below
   its 52-week high. The problem is arithmetic, not regulation.

## What it could not establish

| Gap | Why it matters | Resolved by |
|---|---|---|
| **Exact preferred liquidation preference outstanding today** | It is the largest single deduction in the NAV bridge; a $1bn error moves NAV per share by $2.60 | The Q3 2026 10-Q equity note — egress-blocked |
| **STRK shares outstanding** | The only series for which no current count was retrievable | Same |
| **Exact share count today** | Published figures range 345.9m (EOP) to 384.2m to 419.9m fully diluted; a 10% error moves NAV per share by ~$12 | Q3 2026 10-Q cover page |
| Definition behind each published mNAV figure (1.13x, 1.16x, "below 1") | The headline ratio is quoted four different ways and they disagree by ~15 points | A stated methodology from each publisher |
| Whether the STRC ratchet has been triggered, and how many times | Each trigger is a permanent ~$53m/yr increase in the cash obligation | Company dividend announcements and the 10-Q |
| Software segment operating income | Determines how much of the $1.60bn dividend bill the operating business can cover — Phase 3's central question | Segment disclosure in the 10-Q |

## What it changes about the thesis

Phase 1 establishes that this is not an operating company with a pricing problem. It is a **leveraged,
fee-bearing wrapper around an asset the buyer can own directly**, whose one value-creating mechanism —
issuing stock above NAV — has stopped working, and whose cost of capital ratchets upward on a monthly
schedule while the asset return sits at zero.

Phase 2 must therefore size the asset base and the true cost of carrying it. Phase 3 must establish
where the cash to pay $1.60bn of annual preferred dividends comes from when the ATM is shut. Phase 4
must test whether the levered structure beats simply owning the asset. Those three questions are the
entire investment case.
