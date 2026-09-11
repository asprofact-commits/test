# Phase 2 — Productive asset base & physical bottlenecks
## Strategy Inc. (NASDAQ: MSTR) · as of 2026-09-11

**The question:** what actually produces the output, what does each unit cost, and what limits expansion?

For Strategy the answer is unusually clean. The productive asset is **845,256 bitcoin**. It has no
maintenance capex, no depreciation, no operating cost, no utilisation rate and no physical bottleneck.
Everything that can go wrong with it is financial.

This phase therefore does three things: inventories the asset and its cost basis, builds the **carrying
cost curve** — the only unit cost this asset has — and identifies the binding constraint on expansion,
which turns out not to be physical at all.

---

## 2.1 The asset base

### Inventory

| Asset | Quantity | Value at $77,000/BTC | Share of gross assets |
|---|---|---|---|
| **Bitcoin** | **845,256 BTC** | **$65.08bn** | **94.3%** |
| USD reserve — cash $1.71bn + short-term investments $0.74bn | — | $2.40bn | 3.5% |
| Software business (Strategy ONE / enterprise analytics) | ~$495m FY2026E revenue | ~$1.50bn [ANALYST ESTIMATE, 3.0x sales] | 2.2% |
| **Gross assets** | | **$68.98bn** | 100% |

[FACT] Bitcoin holdings following the 2026-08-31 purchase; USD reserve at 2026-06-30; software revenue
$122.37m in Q2 2026 and $124.3m in Q1 2026 (FY2025 $477m).

Bitcoin represents **4.025% of the 21 million bitcoin that will ever exist** [FACT, treasury trackers,
2026]. Strategy is the largest institutional holder in the world by an order of magnitude — the next
largest corporate holder, Twenty One Capital, holds 43,500 BTC, then Metaplanet at 40,177 and MARA at
35,303 [FACT, treasury trackers, September 2026].

### The accumulation curve — and where it stopped

| Date | Holdings (BTC) | Change | Note |
|---|---|---|---|
| FY2025 year-end | ~713,502 | — | [FACT] FY2025 disclosure. *See `[GAP]`: a separate Q1 statement of "+22% since January" does not reconcile to this figure* |
| 2026-03-31 | **762,099** | — | [FACT] derived from Q1 holdings market value of $51.6bn |
| 2026-05-25 | 843,738 | — | [FACT] company disclosure |
| 2026-06-30 | **843,775** | **+81,676 in Q2** | [FACT] Q2 2026 results; holdings +11% in the quarter |
| 2026-08-31 | **845,256** | **+1,481 in two months** | [FACT] after a 4,600 BTC purchase at an average $80,318 |

**Read the last two rows against the two above them.** Strategy added **81,676 bitcoin in Q2 2026** and
then **1,481 bitcoin in the following two months** — a 98% collapse in the accumulation rate. Open-market
purchases were paused for roughly ten weeks from mid-June, resuming only on 2026-08-31 [FACT, market
reporting]. Between those dates the company was a net *seller* in two separate transactions (Phase 3).

The machine did not slow down. **It switched off**, and it switched off on precisely the date mNAV fell
below 1.0. That is not a coincidence; it is the mechanism described in Phase 1 §1.1 operating exactly
as designed.

### Cost basis

| | |
|---|---|
| Bitcoin acquired, cumulative | 845,050 BTC for **$63.73bn** |
| **Average cost** | **$75,417 / BTC** |
| Market price, 2026-09-11 | **~$77,000** |
| **Unrealised gain on the entire programme** | **+$1.34bn (+2.1%)** |
| Price at which the whole position goes underwater | **$75,417** — 2.1% below spot |
| Price at 2026-06-30 quarter end | ~**$58,700** — position was **below cost** |

[FACT] company holdings disclosure; bitcoin price per Fortune / Yahoo Finance, 2026-09-11.

**The asset base is 2.1% above the price paid for it, and the buffer is smaller than a bad afternoon
in bitcoin.** Phase 4 tests what that means against $21.5bn of senior claims.

---

## 2.2 The unit cost curve

Bitcoin has no production cost for a holder. Its only unit cost is **financial carry** — what it costs
per year to keep the position funded. That curve is now the most important operating metric in the
company, and it has moved violently.

### The carry, built from disclosed obligations

```
Preferred dividends           $400.7m in Q2 2026, annualised          =  $1,603m
Convertible note interest     ~$6.7bn, coupons 0%-2.25%               =  ~$30m
Software business, net        revenue ~$495m, assumed ~breakeven      =  ~$0m
                                             TOTAL ANNUAL CASH CARRY  =  ~$1,633m

÷ 845,256 bitcoin                                                     =  $1,932 per BTC per year
÷ $77,000 per bitcoin                                                 =  2.51% per year
```

[FACT] Q2 2026 preferred dividends of $400.7m; $6.70bn convertible balance at 2026-06-30; coupons
0%–2.25% per the note terms. [ANALYST ESTIMATE] software net contribution and the annualisation.

### The comparison that matters

| Vehicle | Annual cost of holding bitcoin | Multiple of the cheapest |
|---|---|---|
| **US spot bitcoin ETF** | ~0.20% | 1.0x |
| Self-custody | ~0% + operational risk | — |
| **Strategy (MSTR common)** | **2.51%** of the stack, rising | **12.5x** |

Strategy's carry is **twelve and a half times** the cost of the identical exposure in an exchange-traded
fund, before any premium paid on entry and before the leverage effect (which cuts both ways — Phase 4).
In 2021 that comparison did not exist, because the ETF did not exist. **The wrapper's competitive
position has deteriorated for reasons entirely outside its control, and irreversibly.**

### The mix shift — this phase's central arithmetic

The protocol asks what happens when expensive marginal supply is displaced by cheap baseload. For
Strategy the mix shift has run **the wrong way**: cheap convertible funding has been displaced by
expensive perpetual preferred funding.

| Funding source | Blended cost | ~2024 balance | 2026 balance | Annual carry 2026 |
|---|---|---|---|---|
| Convertible notes | **~0.4%** | ~$7.3bn `[GAP]` | **$6.70bn** (−18% in Q2 alone) | ~$30m |
| Perpetual preferred | **~10.8%** | **$0** (STRK launched Feb 2025) | **~$14.80bn** | **~$1,603m** |
| **Total** | | ~$7.3bn | **~$21.50bn** | **~$1,633m** |

**Per unit:**

```
Carry per bitcoin, ~2024:   ~$30m of convert interest ÷ ~450,000 BTC   ≈   $67 / BTC / yr   `[GAP]` — 2024 holdings not sourced
Carry per bitcoin, 2026:    $1,633m ÷ 845,256 BTC                      =   $1,932 / BTC / yr
```

Even on a conservative reading of the unsourced 2024 denominator, **the unit carrying cost of Strategy's
bitcoin has risen by more than an order of magnitude in two years while the bitcoin price has not.**
The asset base grew roughly 1.9x from the 2026-03-31 level to today in dollar terms; the cost of
carrying it grew from essentially nothing to $1.6bn a year.

That is the mix-shift arithmetic, and it is the reverse of the one this protocol usually finds.

### Why the carry only goes up from here

Three mechanics push it higher, none of which management controls:

1. **The STRC ratchet.** Below $95, the rate rises 0.5pp permanently, worth ~$53m a year per trigger.
   STRC is currently trading below par. The rate has already gone 9.00% → 11.50% → 12.00%.
2. **New preferred issuance.** With the common ATM shut below 1.0x mNAV, preferred is the only open
   funding channel — and every dollar raised adds ~10–12% of permanent annual carry.
3. **Falling bitcoin raises the carry ratio mechanically.** At bitcoin $50,000 the same $1.63bn of cash
   obligations is **3.9%** of the stack; at $35,000 it is **5.5%**.

| Bitcoin price | Stack value | Carry as % of stack | BTC/yr needed to fund carry |
|---|---|---|---|
| $120,000 | $101.4bn | 1.61% | 13,608 |
| **$77,000 (spot)** | **$65.1bn** | **2.51%** | **21,208** |
| $60,000 | $50.7bn | 3.22% | 27,217 |
| $45,000 | $38.0bn | 4.29% | 36,289 |
| $30,000 | $25.4bn | 6.44% | 54,433 |

[ANALYST ESTIMATE] at a constant $1.633bn cash carry — which is itself conservative, because the
ratchet raises the carry precisely in the scenarios where the price is falling.

**The carry is an inverse function of the asset price.** That is the definition of a procyclical
liability structure, and it is the single most important structural fact in this phase.

---

## 2.3 The bottleneck

There is no transmission queue, no permit, no turbine lead time. The constraints are financial, and one
of them is binding right now.

| Constraint | Binding? | Evidence | Resolution path | Execution risk |
|---|---|---|---|---|
| **The mNAV gate** | **Yes — binding since June 2026** | mNAV fell below 1.0 in late June; ATM issuance became dilutive; open-market purchases paused ~10 weeks; accumulation fell 98% quarter-on-quarter | Only a higher bitcoin price, which re-rates the equity above NAV and restarts accretive issuance | **High.** The condition for fixing it is the condition it is supposed to produce |
| **US dollar liquidity** | **Approaching** | S&P's B− rating explicitly cites "low U.S. dollar liquidity". USD reserve $2.40bn against $1.633bn of annual cash carry = **~17.6 months of cover with zero issuance** | Preferred ATM, bitcoin sales, or a convert | **Medium.** All three are available; all three are costly |
| **STRC par discipline** | **Yes** | STRC trades below its $100 stated amount, which is the condition under which further STRC ATM issuance is least attractive and the ratchet threatens | Raise the rate (already 12%), or stop issuing | **Medium** |
| **Index eligibility** | Partially | S&P 500 closed on GAAP losses and pure-asset income; Nasdaq-100 retained; MSCI deferred with a broader consultation open | None available to management | **Low-medium** |
| **Bitcoin market depth on exit** | Latent | 845,256 BTC is **4.025% of all bitcoin that will ever exist**. There is no orderly path to liquidating it | Not applicable while solvent | **High if ever triggered** |
| Physical / operational | **No** | Custody and operations are immaterial costs | — | Low |

### The stress model: what a 24-month closed window costs

Phase 2's job is to model the delay. Here the "delay" is an extended period with mNAV below 1.0 and the
equity ATM shut.

```
Annual cash carry                                          $1.633bn
24 months of carry                                         $3.27bn
Funded by USD reserve ($2.40bn) then bitcoin sales         $0.87bn of bitcoin at $77,000
                                                           = 11,250 BTC sold, reserve exhausted

If the reserve is preserved and carry is funded by bitcoin alone:
   $3.27bn ÷ $77,000                                       = 42,400 BTC, 5.0% of the stack
At bitcoin $50,000:                                        = 65,400 BTC, 7.7% of the stack
At bitcoin $35,000, with two ratchet triggers (+$106m/yr): = 98,700 BTC, 11.7% of the stack
```

**The asymmetry is the finding.** A closed capital-markets window costs Strategy 5% of its bitcoin over
two years if bitcoin holds, and nearly 12% if bitcoin halves — because the numerator rises as the
denominator falls. Phase 3 shows this is not hypothetical: the sales have already started.

---

## 2.4 Is the "capex" compensated?

Bitcoin purchases are Strategy's capex. The comparison to a regulated asset base is instructive in both
directions, and the honest version gives Strategy real credit:

| Test | Regulated utility | A hyperscaler's GPU fleet | **Strategy's bitcoin** |
|---|---|---|---|
| Enters a return-earning base? | Yes, at an allowed ROE | No | **No** |
| Recovery legally assured? | Yes | No | **No** |
| **Asset life / depreciation** | 30–60 years | **5.5 years** | **Infinite — no depreciation at all** |
| **Maintenance capex to hold output flat** | Substantial | Substantial | **Zero** |
| **Operating cost** | Substantial | Substantial | **Effectively zero** |
| Recovery mechanism | Tariff | Product pricing | **Price appreciation only** |
| Stranded-asset risk | Mitigated by cost recovery | Total loss over 5.5 years | **Total loss, but no forced write-down schedule** |

**Give the structure its due.** Strategy's asset does not decay, does not need replacing, and costs
nothing to run. Compared with $137bn a year of five-and-a-half-year GPUs, this is a far cleaner asset.
100% of the capital deployed still exists and is still working.

**And then state the offset.** Because the asset produces no cash flow whatsoever, **100% of the cost of
owning it is financing cost**, and that cost is now $1.6bn a year, contractual, and ratcheting. A
utility's rate base earns a return that pays for the debt that funded it. Bitcoin earns nothing. The
entire carry must be paid from somewhere else — and Phase 3 establishes that "somewhere else" is a
$495m software business and the bitcoin itself.

**Split growth from maintenance:** for Strategy, **100% of bitcoin purchases are growth capex and 0% is
maintenance** — there is nothing to maintain. That sounds favourable, and it is, but it means there is
no "sustaining" spend that can be cut in a downturn to preserve cash. The cuttable line is the purchase
programme, and it has already been cut to zero.

---

## What this phase establishes

1. **The productive asset is 845,256 bitcoin — 4.025% of total supply — held at an average cost of
   $75,417 against a ~$77,000 price.** The entire six-year programme sits 2.1% above water, and was
   below water at the last quarter end.
2. **The accumulation engine switched off in mid-June 2026.** Holdings grew 81,676 BTC in Q2 2026 and
   1,481 BTC in the following two months — a 98% collapse — on precisely the date mNAV crossed below 1.0.
3. **The unit cost of this asset is financial carry, and it is now $1,932 per bitcoin per year, or 2.51%
   of the stack** — twelve and a half times the ~0.20% fee on a spot bitcoin ETF that did not exist when
   the strategy was designed.
4. **The funding mix shifted the wrong way**: from ~$7bn of ~0.4% convertibles to ~$14.8bn of ~10.8%
   perpetual preferred, taking annual carry from roughly nothing to $1.63bn in about two years.
5. **The carry is procyclical.** At $77,000 it is 2.51% of the stack; at $45,000 it is 4.29%; at $30,000
   it is 6.44% — and the STRC ratchet pushes it higher in exactly those states. The liability structure
   is designed to tighten when the asset falls.

## What it could not establish

| Gap | Why it matters | Resolved by |
|---|---|---|
| **2024 convertible balance and year-end bitcoin holdings** | The mix-shift arithmetic is directionally certain but the 2024 base is unsourced, so the "order of magnitude" claim is conservative rather than measured | FY2024 10-K |
| **Software segment operating income** | Determines whether the operating business contributes to, or consumes, the $1.633bn carry. Treated as breakeven here | Segment disclosure in the 10-Q |
| Whether the 2026 bitcoin purchases were funded by common ATM, preferred ATM, or both, and in what proportion | Determines how much of the preferred carry was incurred to buy bitcoin at prices above today's | Q2/Q3 2026 10-Q financing activities |
| Reconciliation of the FY2025 year-end holding (713,502 BTC) with the Q1 2026 statement of "+22% since January" | A ~40,000 BTC discrepancy, worth ~$3bn | The FY2025 10-K and Q1 2026 10-Q |
| Exact convertible coupon schedule and any remaining put dates | The 2032 notes carry a holder put on 2029-06-15; other put dates were not retrievable | Note indentures |

## What it changes about the thesis

Phase 1 said the value-creating mechanism had stopped. Phase 2 prices what it costs to wait for it to
restart: **2.51% of the bitcoin stack per year, rising as the price falls, with no operating asset
capable of covering it.**

It also establishes the one genuinely favourable structural fact in this company — the asset does not
depreciate, requires no maintenance and costs nothing to operate — and shows why that advantage is
neutralised. An asset with zero yield cannot service a liability with a 10.8% coupon out of anything
except itself.

Phase 3 must now answer the question this sets up: **with the ATM shut, where does $1.633bn a year
actually come from?**
