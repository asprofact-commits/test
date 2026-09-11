# Phase 5 — Valuation, stress tests & investment committee memo
## Strategy Inc. (NASDAQ: MSTR) · $128.48 · as of 2026-09-11

---

## 5.1 Peer benchmarking

### Why the conventional peer table does not apply, and what replaces it

Strategy has no EBITDA worth multiplying, no earnings that mean anything (GAAP net income is a bitcoin
price chart under ASU 2023-08), and a book value that *is* its NAV because the asset is marked to
market. **EV/EBITDA, P/E and P/B against normalised ROE are all either undefined or circular here.**

The governing ratio is **price to net asset value**, and the correct peer set is the other vehicles
that sell the same thing — including, critically, the one that did not exist when this strategy was
designed.

| Vehicle | Holding | **P/NAV (mNAV)** | Annual carry | Leverage | Why it is in the set |
|---|---|---|---|---|---|
| **Strategy (MSTR) — self** | **845,256 BTC** | **1.04x** *(published readings 1.13–1.16x)* | **3.44% of common NAV** | **1.37x** | The subject |
| Metaplanet (3350.T) | 40,177 BTC | **0.99x** | n/d | n/d | The most aggressive 2025 accumulator; ran the identical playbook in a different jurisdiction |
| BitMine (ETH) | >4.7m ETH | **1.01x** | n/d | n/d | The one treasury peer whose asset **yields** — it funds a dividend from staking. The control case for what Strategy structurally cannot do |
| Semler Scientific | n/d | **0.88x** | n/d | n/d | A small operating business that bolted on a treasury; shows what happens without scale |
| Nakamoto | n/d | **~0.70x** | n/d | n/d | Down 96% from peak. The tail outcome, and it is not theoretical |
| Twenty One Capital (XXI) | 43,500 BTC | n/d `[GAP]` | n/d | n/d | Second-largest corporate holder |
| MARA Holdings | 35,303 BTC | n/d `[GAP]` | n/d | n/d | Miner-plus-treasury hybrid |
| Bullish (BLSH) | 24,300 BTC | n/d `[GAP]` | n/d | n/d | Exchange-plus-treasury hybrid |
| **US spot bitcoin ETF** | Bitcoin | **1.00x by construction** | **~0.20%** | **1.00x** | **The alternative. The single most important row in this table** |
| Listed closed-end funds (generic) | Liquid securities | Historically **0.85–0.95x** | 0.5–2.0% | 1.0x | The structural analogue: a permanent-capital vehicle holding a liquid asset, charging a fee, with no durable edge |

[FACT] peer mNAV readings from bitcoin-treasury trackers and sector reporting, 2026; holdings per the
same. **More than 15% of digital-asset treasuries now trade below 1.0x NAV.** [ANALYST ESTIMATE] the
MSTR row, derived in Phase 1 §1.4.

### Defending the premium analytically

**Median P/NAV across the five populated treasury peers is 0.99x. Strategy trades at 1.04x.**

That is the finding, and it inverts the usual framing. **Strategy does not trade at a discount to its
sector. It trades at a 5% premium to it** — and at an infinite premium to the instrument that delivers
the same exposure for 20 basis points.

Decomposing the 5 points:

| Component | Points of P/NAV | Justified? |
|---|---|---|
| Scale, liquidity, Nasdaq-100 membership | **+5** | **Yes.** Index inclusion and a deep options market are worth something real |
| Longest track record, deepest capital-markets access | **+5** | **Yes.** Strategy can still raise preferred when peers cannot |
| Highest absolute carry burden ($1.63bn/yr, 2.51% of the stack) | **−3** | **Yes** — and this one grows as bitcoin falls |
| Preferred-heavy structure versus peers' simpler balance sheets | **−2** | **Yes.** More senior claims ahead of the common |
| **Net explained** | **+5** | |
| **Unexplained residual** | **≈ 0** | |

**There is no peer-relative opportunity here.** The premium is fully explained by scale and access, and
those advantages are precisely the ones that stop mattering when the ATM is shut. The honest conclusion
from the peer work is not "cheap" or "expensive" — it is that **MSTR is correctly priced against its
sector, and its sector is priced at roughly liquidation value.**

---

## 5.2 Three scenarios

Each is a coherent state of the world, consistent across Phases 1–4. For this company a scenario is
defined by two variables and only two: **the bitcoin price** and **the P/NAV rating the market assigns**.

| | **Bear (35%)** | **Base (40%)** | **Bull (25%)** |
|---|---|---|---|
| **Trigger set** | Bitcoin breaks below the $75,417 cost basis and stays there; mNAV holds below 1.0; ATM stays shut; carry funded entirely by bitcoin sales; STRC ratchets twice; premium compresses toward the Semler/Nakamoto range | Bitcoin recovers modestly; mNAV oscillates around 1.0x; ATM reopens intermittently; carry funded by a mix of preferred issuance and bitcoin sales; STRC holds near 12% | Bitcoin makes a new cycle high; mNAV re-rates above 1.25x; the accretion machine restarts; buybacks of preferred become possible; STRC rate falls |
| **Bitcoin price, spot equivalent** | **$45,000** | **$85,000** | **$150,000** |
| **P/NAV assigned** | **0.80x** | **1.00x** | **1.25x** |
| Implied gross-asset multiple *(as supplied to the model)* | **0.49x** | **1.10x** | **2.37x** |
| Bitcoin per share trajectory | **−4.3%/yr** (sales fund carry at a lower price) | **−1.5%/yr** | **+8%/yr** (accretive issuance resumes) |
| WACC (documented, not used in a DCF) | 17.5% | 15.5% | 13.5% |
| **Value per share** | **$32** | **$142** | **$370** |
| vs $128.48 | **−75%** | **+10%** | **+188%** |

### Why these probabilities, and not symmetry

**Bear 35%** — above symmetric, for evidenced reasons: bitcoin is **−12% year to date**; the entire
position sits **2.1% above cost**; mNAV has already been below 1.0 once this cycle; the carry is
procyclical; the STRC ratchet is one-way; and two peers (Semler 0.88x, Nakamoto 0.70x) demonstrate that
sub-1.0x is a stable state, not a brief dislocation.

**Bull 25%** — held at a full quarter weight, and it deserves it. Bitcoin is a genuinely fat-tailed
asset that has produced multi-hundred-percent moves in each prior cycle. Critically, **Strategy will
still be here to participate**: Phase 4 established there is no margin call, no maturity wall before
2029 and no covenant to breach. The structure survived a 33% drawdown in H1 2026 without a forced sale.
**The convexity is real and it is the entire reason not to be outright negative.**

**Base 40%** — bitcoin recovers to roughly its 2025 year-end level and the premium sits at liquidation
value, which is where the sector median already is.

---

## 5.3 Triangulated valuation

### Why there is no DCF, stated explicitly

The sector profile for balance-sheet businesses says a DCF here must be "a dividend-discount or
excess-returns model, never an EV/FCF model." For Strategy even that is unavailable:

- **The asset produces no cash flow at all.** Bitcoin has no coupon, no dividend and cannot be staked.
- **Free cash flow to the firm is structurally negative** — roughly −$1.6bn a year — and it is negative
  in *every* scenario, including the bull case, because a higher bitcoin price generates no cash.
- **The common pays no dividend**, so a dividend-discount model has a zero numerator.

A DCF built on these inputs would return a large negative number and would be worse than useless. **No
`fcf` scenarios are supplied to the model, and the DCF weight is set to zero.** This is a deliberate
methodological choice, not an omission, and the workspace renormalises the remaining weights.

For the same reason the **justified P/B versus normalised ROE** method is omitted: book value here *is*
NAV (the asset is marked to market), so `(ROE − g)/(COE − g) × BVPS` collapses into a circular restatement
of the P/NAV question, and a perpetual-growth model applied to a 50%-volatility asset degenerates.

### (1) Asset-base multiple — P/NAV. **Primary.**

Gross assets of **$68.98bn** (bitcoin $65.08bn + USD reserve $2.40bn + software ~$1.50bn), less senior
claims of **$21.50bn** (converts $6.70bn + preferred ~$14.80bn), across **384.2m shares**.

| Scenario | Bitcoin price | P/NAV | Multiple on gross assets | **Value/share** |
|---|---|---|---|---|
| Bear | $45,000 | 0.80x | 0.49x | **$32** |
| Base | $85,000 | 1.00x | 1.10x | **$142** |
| Bull | $150,000 | 1.25x | 2.37x | **$370** |
| **Probability-weighted** | | | | **$160** |

*The "multiple" supplied to the model compounds two effects — the bitcoin price move and the P/NAV
rating — so that the workspace reproduces the same per-share answers from a single gross-asset input.*

### (2) Sum of the parts — today's liquidation value

| Segment | Method | Metric | Multiple | **Value ($m)** |
|---|---|---|---|---|
| Bitcoin | Mark to market at $77,000 | 65,085 | 1.0x | **65,085** |
| Software business | EV/Sales | 495 | 3.0x | **1,485** |
| USD reserve | At cost | 2,400 | 1.0x | **2,400** |
| **Gross value** | | | | **68,970** |
| Less senior claims (converts + preferred) | | | | **(21,500)** |
| **Equity value** | | | | **47,470** |
| **Per share (384.2m)** | | | | **$123.56** |

This is a static, today's-price figure and it deliberately contains no bitcoin forecast. **It is the
floor the market is currently paying a 4% premium to.**

### (3) Peer multiples — cross-check only

Median treasury-peer P/NAV of **0.99x** applied to today's NAV gives **$122** per share. Strategy's own
1.04x is a 5% premium to that. As established in §5.1, the premium is fully explained and the
unexplained residual is approximately zero.

### Triangulation

| Method | Weight | Value | Why this weight |
|---|---|---|---|
| **Asset-base (P/NAV, scenario-weighted)** | **55%** | **$160** | The governing valuation framework for a mark-to-market holding vehicle. It is the only method that carries a forward view |
| **SOTP (today's liquidation value)** | **45%** | **$124** | The hard floor. Weighted heavily because it requires no bitcoin forecast, and because a forecast of bitcoin is not an analytical edge this file possesses |
| DCF | **0%** | — | No cash flows exist. Deliberately omitted, see above |
| P/B vs normalised ROE | **0%** | — | Circular: book value is NAV. Deliberately omitted |
| Peer multiples | cross-check | $122 | Unexplained residual ≈ 0 |
| **TRIANGULATED FAIR VALUE** | | **$143.70** | **+11.9% against $128.48** |

---

## 5.4 Investment committee memo

### Rating: **HOLD / NEUTRAL**

### Fair value today

| | Bear | Base | Bull | Prob-weighted |
|---|---|---|---|---|
| Probability | 35% | 40% | 25% | |
| **Fair value / share** | **$32** | **$142** | **$370** | |
| **Triangulated fair value** | | | | **$143.70** |
| vs $128.48 | −75% | +10% | +188% | **+11.9%** |

Single US listing in USD; no ADR line. The preferred series STRE is euro-denominated and LuxSE-listed
but is a liability, not an alternative line in the common.

### Three-year target and expected IRR (to September 2029)

The common pays **no dividend**, so total return is price only.

| | Bear | Base | Bull | Expected |
|---|---|---|---|---|
| Bitcoin assumption | $45,000 | $110,000 | $200,000 |  |
| P/NAV assumption | 0.80x | 1.00x | 1.30x | |
| Bitcoin held (after dividend-funded sales) | ~780k | ~792k | ~900k | |
| Shares outstanding | ~400m | ~420m | ~450m | |
| **3-year target price** | **$24** | **$166** | **$474** | **$193** |
| Dividends | $0 | $0 | $0 | $0 |
| **IRR (CAGR)** | **−42.6%** | **+8.8%** | **+54.5%** | **+14.5%** |

**Expected IRR of 14.5% against an 18.0% cost of equity.** Positive, fat-tailed, and still short of the
hurdle. That gap — not the +11.9% fair-value premium — is why this is a HOLD and not a BUY.

**The one-line version for the committee:** *if you want bitcoin, buy bitcoin. MSTR is a 1.37x levered
wrapper charging 3.44% a year on your NAV, and it only beats spot above a ~12% bitcoin CAGR. At 1.04x
NAV you are paying a small premium for that trade, in a sector whose median is 0.99x. It is not
expensive enough to sell and not cheap enough to buy.*

### Why the market is mispricing this — three non-consensus points

**1 · The leverage is 1.37x, not the 2–3x the market still prices, and it is rented, not owned.**
*Market believes:* MSTR is "the leveraged bitcoin proxy" — buy it when you want amplified beta.
*We believe:* the amplification is **1.37x**, and it is paid for with a **3.44% annual fee on common
NAV that rises as bitcoin falls** — 2.51% of the bitcoin stack at $77,000, 4.29% at $45,000. The
"leverage" is a rented call option with a procyclical premium, not a permanent capital structure
advantage.
*Evidence:* Phase 4 §4.4 leverage derivation ($65.08bn exposure / $47.48bn NAV); Phase 2 §2.2
procyclical carry curve.

**2 · Strategy trades at a premium to its own sector, not a discount — and the mean reversion points
down.**
*Market believes:* mNAV has collapsed from 3.89x, therefore MSTR is cheap and the discount will close.
*We believe:* at 1.04x, Strategy trades **above the 0.99x median of its treasury peers** and far above
the structural analogue — listed closed-end funds holding liquid assets with a fee and no durable edge
have historically traded at **0.85–0.95x**. Semler sits at 0.88x and Nakamoto at 0.70x today. **Nothing
in the historical record of permanent-capital vehicles supports a durable premium once the access
monopoly is gone**, and it is gone.
*Evidence:* Phase 5 §5.1 peer table; Phase 4 §4.4 on the permanence of the spot-ETF overlay.

**3 · The headline KPI is designed so that it cannot report the failure.**
*Market believes:* BTC Yield of +13.3% year to date shows the compounding machine is still working.
*We believe:* BTC Yield measures bitcoin per share and rises whenever stock is issued above 1.0x mNAV,
**regardless of the bitcoin price and regardless of what the capital cost**. Year to date, bitcoin per
share rose 13.3% while the bitcoin price fell 12%, leaving **bitcoin value per share approximately flat**
and the shares ~65% below their high. With the ATM shut and dividends funded by sales, the same metric
now runs at roughly **−2.5% a year**.
*Evidence:* Phase 3 §3.2; company BTC Yield disclosure at 2026-05-25; bitcoin at $87,515 on 2025-12-31.

### What the consensus is correctly terrified of — three structural risks

**1 · The reverse flywheel has no internal exit.** mNAV below 1.0 makes issuance dilutive → the ATM
shuts → bitcoin per share falls as dividends are funded by sales → there is less reason to pay a
premium → mNAV stays below 1.0. The loop is self-reinforcing in both directions, and **the only thing
that breaks it is an exogenous bitcoin rally.** A company whose recovery condition is the outcome it is
supposed to produce is not in control of its own future. The purchase pause from mid-June to 2026-08-31
is this mechanism on the record.

**2 · The carry is procyclical and the ratchet is one-way.** At $77,000 the cash bill is 2.51% of the
stack; at $45,000 it is 4.29%; at $30,000 it is 6.44% — and in exactly those states STRC trades below
$95 and the rate ratchets up 0.5 points at a time, permanently, at ~$53m a year each. The rate has
already gone **9.00% → 12.00% in fourteen months**. The liability structure is engineered to tighten
when the asset falls, which is the definition of the risk an investment committee should refuse to
underwrite cheaply.

**3 · The access monopoly is permanently gone.** Strategy's premium was built when it was the only
regulated way to hold bitcoin in a brokerage account. Spot ETFs now do it for ~0.20% — **one twelfth of
Strategy's carrying cost** — with daily creation and redemption at NAV, which is precisely the
mechanism that prevents a discount from persisting. Strategy has no redemption mechanism. Any future
premium must be earned by leverage and the issuance machine alone, and both of those are cyclical. This
is the one part of the bear case that no bitcoin rally repairs.

### The steel-manned bull, because it is genuinely strong

The bull case is not a story, it is a structure: **Strategy cannot be forced to sell.** No secured debt,
no margin calls, no maturities before 2029, perpetual preferred that can never be put back, and a
wipe-out price 73% below spot. It absorbed a 33% drawdown in H1 2026 and added 11% more coins through
it. If bitcoin does in the next three years anything resembling what it has done in prior cycles, the
1.37x exposure plus a re-rating to 1.25x NAV produces **$474 a share, a 54.5% IRR** — and the holder
will still be there to collect it. **That convexity is why the rating is HOLD and not AVOID.**

### Catalyst calendar

| Window | Catalyst | Impact | Prob. | Re-rates the multiple or changes NAV? |
|---|---|---|---|---|
| **Continuous** | **The bitcoin price** — 94.3% of gross assets, 1.37x levered | **High** | — | **NAV** |
| Monthly | STRC dividend reset — a direct market quote for Strategy's marginal cost of capital | Medium | 1.00 | Multiple |
| Weekly | 8-K purchase/sale disclosures — the cleanest read on whether the ATM has reopened | Medium | 1.00 | Both |
| **Late Oct 2026** | Q3 2026 results: cumulative bitcoin sales, USD reserve, updated preferred balance | **High** | 0.95 | Both |
| 2027 | MSCI's broader consultation on non-operating companies concludes — the deferred overhang | **High** | 0.50 | Multiple |
| Next 12m | Software-business monetisation or a further discounted convertible repurchase — the only deleveraging levers | Medium | 0.40 | NAV |
| Bitcoin-dependent | mNAV sustained above 1.25x, restarting accretive issuance | **High** | 0.30 | Both |
| Next 12–18m | S&P rating action on B− stable | Medium | 0.30 | Multiple |

### Trigger-to-sell conditions (measurable, falsifiable)

**A falling P/NAV is deliberately not among them.** For a mark-to-market holding vehicle with the
structure intact, a wider discount is a *better entry price*, not a reason to sell — which is why the
buy trigger below is a P/NAV level and every sell trigger here is about the **NAV itself being consumed
or encumbered.** Confusing the two is the most common error in closed-end-fund investing.

1. **Bitcoin per share declining for three consecutive quarters** — the compounding machine running in
   reverse on the only measure that matters to the common.
2. **Cumulative bitcoin sales above 25,000 BTC in any rolling twelve months** (~3% of the stack) — the
   bleed exceeding the modelled 2.51%.
3. **Bitcoin holdings lower year-on-year in any quarter** — the absolute stack shrinking.
4. **STRC dividend rate above 14.00%** — two further ratchet triggers; carry above 3% of the stack.
5. **USD reserve below $1.0bn** — under eight months of carry cover.
6. **Senior claims above 45% of bitcoin market value** (currently 33%) — the common's share of the
   asset being structurally eroded.
7. **Any secured borrowing against the bitcoin, or an S&P downgrade below B−** — the single structural
   protection, the absence of a margin call, being surrendered.

### Trigger-to-buy conditions (would flip this to TACTICAL BUY)

1. **P/NAV below 0.80x** — buying $1 of bitcoin for 80 cents, with the flywheel optionality free. This
   is the condition under which the file turns positive, and peer evidence says it is reachable.
2. **mNAV sustained above 1.25x with the ATM demonstrably reopened and bitcoin per share rising for two
   consecutive quarters** — the machine verifiably restarted.
3. **Preferred reduced below $10bn**, by software-business monetisation or buy-back at a discount —
   cutting the carry below 2% of the stack.
4. **STRC rate back below 9.00%** — the cost of capital normalised.

---

## What this phase establishes

1. **Triangulated fair value is $143.70 against $128.48 — a 11.9% premium to the current price** — on a
   35/40/25 scenario weighting, with P/NAV weighted 55% and today's liquidation SOTP 45%.
2. **Expected three-year IRR is 14.5% against an 18.0% cost of equity.** Positive but below the hurdle,
   and that gap is what decides the rating.
3. **Strategy trades at a 5% premium to its treasury-peer median (1.04x vs 0.99x), not a discount** —
   and the premium is fully explained by scale, liquidity and index membership, leaving an unexplained
   residual of approximately zero.
4. **No DCF and no justified-P/B is run, deliberately.** The asset produces no cash flow in any
   scenario and book value is NAV, so both methods are undefined rather than merely difficult. The
   weights are set to zero and the reasoning is stated rather than hidden.
5. **The dispersion is $32 to $370 and it is almost entirely a bitcoin view.** The honest position is
   that this file has an edge on the *wrapper* — its cost, leverage and mechanics — and no edge
   whatsoever on the *asset*.

## What it could not establish

| Gap | Valuation dependence | Resolved by |
|---|---|---|
| **Exact preferred balance and market value** | The largest deduction in every valuation here; a $1bn error is $2.60 per share and 0.03x of leverage | Q3 2026 10-Q equity note |
| **Exact current share count** | Published figures span 345.9m to 419.9m; the spread is worth ~$12 per share of NAV | Q3 2026 10-Q cover page |
| Peer P/NAV for Twenty One, MARA and Bullish | Would let the sector median be computed on eight names rather than five | Treasury trackers with a stated methodology |
| Software segment operating income and any standalone valuation mark | It is 2.2% of gross assets and the only monetisable non-bitcoin asset | Segment disclosure |
| A bitcoin price forecast of any analytical standing | It is the dominant variable and this file does not have one — which is precisely why SOTP at today's price carries 45% of the weight | Not resolvable by research |

## What it changes about the thesis

Nothing in Phases 1–4 is contradicted; Phase 5 prices it and reaches a conclusion the headline
narrative does not support in either direction. **This is neither the broken company the 65% drawdown
implies nor the cheap leveraged proxy the sell-side consensus of $224–252 implies.** It is a
competently-run, unbreakable, expensive wrapper around an asset the buyer can hold for 20 basis points,
trading at roughly its own liquidation value plus a small, fully-explained premium.

The discipline the protocol demands is to say what that is worth and stop. It is worth approximately
what it is trading at. **HOLD** — and the specific, dated conditions that would make it a buy (P/NAV
below 0.80x with the structure intact) or a sell (bitcoin per share falling three quarters running,
sales above 25,000 BTC a year, STRC above 14%) are listed above, so the position can be monitored
rather than re-argued.
