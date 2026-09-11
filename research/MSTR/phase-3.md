# Phase 3 — Demand & monetisation structure
## Strategy Inc. (NASDAQ: MSTR) · as of 2026-09-11

**The question:** where does incremental demand come from, how firm is it, and does serving it create
value?

For Strategy, "demand" does not mean customers. The software business has ~$495m of revenue and is
irrelevant to the equity. **Demand here means demand for Strategy's securities** — the capital that
funds bitcoin purchases and, increasingly, pays the dividends on the capital raised before it.

Phase 2 set the bill: **$1,633m a year of cash carry**. This phase establishes where it comes from.

---

## 3.1 The demand map

### Named sources of capital

| # | Source | Counterparty | Capacity | Status | **Class** |
|---|---|---|---|---|---|
| 1 | **MSTR common ATM** | Public equity market | Half of the **$42bn** "42/42" authorisation (2026-03-23) | **GATED — economically shut below 1.0x mNAV; paused ~10 weeks from mid-June 2026** | `[Approved / Committed]` capacity; `[Speculative]` demand |
| 2 | **STRC ATM** | Yield buyers | Other half of the $42bn authorisation | **Open, but STRC trades below its $100 par and the rate is 12.00%** | `[Approved / Committed]` capacity |
| 3 | STRF / STRD / STRE ATMs | Yield buyers, incl. European (LuxSE) | Not separately disclosed `[GAP]` | Open | `[Approved / Committed]` capacity |
| 4 | Convertible note market | Credit/vol funds | — | **Strategy is a net repurchaser, not an issuer**: $1.50bn of 2029s bought back for $1.38bn in May 2026 | Not in use |
| 5 | **Bitcoin sales** | Spot market | 845,256 BTC | **In use.** ~3,620 BTC sold in May–June 2026 for ~$218m | `[Existing Contracted]` — the only genuinely certain source |
| 6 | Software operating cash flow | ~10,000 enterprise customers | ~$495m revenue | Stable, immaterial | `[Approved / Committed]`, ~0–3% of the bill |
| 7 | Secured borrowing against bitcoin | Private credit | Not used | Not disclosed | `[Unfunded Planned]` |
| 8 | **"1 million BTC by end-2026"** | — | Requires ~155,000 more BTC ≈ **$12bn** in under four months with the common ATM shut | Announced 2026-03-23 | **`[Speculative]` — zero weight** |

[FACT] 42/42 plan announced 2026-03-23: $42bn of additional ATM authorisations split equally between
MSTR and STRC, with a stated goal of 1 million BTC by end-2026. ATM proceeds of $8.41bn in Q2 2026 and
$1.28bn between 1 and 26 July. $25.3bn raised in calendar 2025 and $11.68bn in the first four months of
2026. Bitcoin sales per 8-K disclosures, May and June 2026.

### The classification that matters

The protocol's taxonomy exposes something the headline authorisation figures hide:

> **A $42bn ATM authorisation is a permit, not a pipeline.** It is board approval to *offer* securities.
> Nobody is obliged to buy them, there is no backstop, no standby purchase agreement and no
> underwriting commitment. **Strategy's committed forward funding is $0.**

| Class | Test | Strategy's position |
|---|---|---|
| `[Existing Contracted]` | Signed, binding, take-or-pay | **$0 of capital.** The only contractually certain source of cash is *selling the asset* |
| `[Approved / Committed]` | Approved, capacity reserved | **$42bn of authorisation**, of which the common half is economically unusable below 1.0x mNAV |
| `[Unfunded Planned]` | Announced without financing | Secured bitcoin borrowing; further preferred series |
| `[Speculative]` | Extrapolation or aspiration | **The 1-million-bitcoin target** |

Meanwhile the *obligations* run the other way. **$1,633m a year of preferred dividends is contractual,
cumulative for STRF and STRC, and ratcheting.** Strategy has converted uncertain, optional funding into
certain, perpetual obligations. That is the structural trade the last eighteen months made.

### The demand bridge — capital raised, and what happened to it

| Period | Capital raised | Bitcoin added | Implied cost |
|---|---|---|---|
| Calendar 2025 | **$25.3bn** — largest US equity issuance, second consecutive year | to ~713,502 BTC at year-end | — |
| Q1 2026 (to 2026-05-05) | **$11.68bn** — largest US equity issuance of 2026 | 762,099 BTC at 2026-03-31 | — |
| Q2 2026 | **$8.41bn** ATM gross proceeds | **+81,676 BTC** | ~$65k/BTC |
| 2026-07-01 to 07-26 | $1.28bn ATM gross proceeds | — | — |
| **Mid-June to 2026-08-31** | **Common ATM paused** | **+1,481 BTC net**, including sales | — |

**The bridge has a negative term now, and it is new.** Bitcoin per share was **220,900 sats** at
2026-05-25 [FACT]. On today's 845,256 BTC over ~384.2m shares it is **~220,000 sats** — flat for three
and a half months, after rising 13.3% in the first five months of the year.

---

## 3.2 Value capture — does raising this capital create value?

### The incremental-margin calculation, common equity

Issuing common at an mNAV of *m* adds $1 of bitcoin and dilutes existing holders by $1/*m* of NAV.
Accretion per dollar issued is therefore **$1 × (1 − 1/m)**:

| mNAV | Accretion per $1 issued | Less ~1.5% ATM fees | Verdict |
|---|---|---|---|
| **3.89x** (Nov 2024 peak) | **+74.3¢** | +72.8¢ | The machine that built the company |
| 1.60x | +37.5¢ | +36.0¢ | Strongly accretive |
| 1.22x (management's stated threshold) | +18.0¢ | +16.5¢ | Accretive |
| **1.04x (today)** | **+3.8¢** | **+2.3¢** | **Economically trivial** |
| 1.00x | 0¢ | −1.5¢ | Value-destructive after fees |
| 0.95x | **−5.3¢** | −6.8¢ | Destroys value |

[ANALYST ESTIMATE] derivation shown; mNAV of 1.04x from the Phase 1 NAV bridge; 3.89x peak is [FACT].

**At today's premium the flagship mechanism produces about two cents of value per dollar raised.** The
engine has not merely slowed — its output has fallen by 97% from peak, and it turns negative on a 5%
move in the share price.

### The incremental-margin calculation, preferred equity

Raising $1 of STRC buys $1 of bitcoin and creates a **perpetual 12% cash claim**. The incremental margin
is simply:

```
Incremental margin  =  (bitcoin's compound return)  −  (12.00%)
```

Strategy's own realised experience is the best available estimate of the first term:

```
$63.73bn deployed over six years, now worth $65.08bn   =  +2.1% cumulative
Annualised, dollar-weighted (most capital deployed 2024-26)  ≈  1% or less per year

INCREMENTAL MARGIN ON PREFERRED-FUNDED BITCOIN  =  ~1%  −  12%  =  ~ −11 percentage points
```

**State it in the words the protocol requires: growth here does not merely dilute returns, it destroys
capital.** Every dollar of preferred raised to buy bitcoin at these prices has, on the company's own
six-year track record, funded an asset returning ~1% with capital costing 12%. The strategy only works
if bitcoin's *forward* return exceeds 12% — which is a bet on bitcoin, not a business.

### The KPI problem

Management's headline metric is **BTC Yield** — the growth in bitcoin per share. Year to date at
2026-05-25 it was **13.3%**, with a **BTC Gain of 89,378 bitcoin** and a **BTC $ Gain of $6.8bn** [FACT,
company disclosure].

Those are real numbers and they are not wrong. They are, however, constructed so that they **cannot
register the thing that went wrong**:

```
BTC per share, YTD                          +13.3%
Bitcoin price, YTD ($87,515 → ~$77,000)     −12.0%
Bitcoin value per share, YTD                 ≈ −0.3%
MSTR share price vs the 52-week high         ≈ −65%
```

BTC Yield rises whenever Strategy issues stock above 1.0x mNAV, **regardless of what the bitcoin price
does and regardless of what the capital cost**. A shareholder who held all year owns more bitcoin per
share and less money. The gap between −0.3% and −65% is the collapse of the premium, and no metric
management reports captures it.

This is worth stating plainly because it is the clearest governance finding in the file: **the company's
primary performance indicator is structurally incapable of declining when the strategy is failing.**

### Where the $1,633m actually comes from

| Source | Annual capacity | Share of the bill | Class |
|---|---|---|---|
| Software operating cash flow | **~$0–50m** [ANALYST ESTIMATE] | **0–3%** | Certain, immaterial |
| Common ATM | **$0 while mNAV < ~1.05** | **0%** today | Gated |
| Preferred ATM | Open, but each dollar raised **adds ~11% of permanent new carry** | Can cover 100% — by enlarging the problem | Self-defeating at the margin |
| USD reserve draw-down | **$2.40bn = 17.6 months**, once | — | Finite |
| **Bitcoin sales** | **Unlimited until the stack is gone** | **The residual — and therefore the real answer** | In use |

**Bitcoin sales are no longer hypothetical.** Two are on the record:

| Date | Amount | Proceeds | Stated purpose |
|---|---|---|---|
| 2026-05-26 to 05-31 | **32 BTC** | ~$2.5m at an average $77,135 | STRC preferred dividends |
| ~end of June 2026 | **3,588 BTC** | **$216m** | Preferred dividends |

[FACT] 8-K disclosures reported 2026-06-01 and subsequently.

And the policy is explicit. On the Q1 call (2026-05-05) Michael Saylor said Strategy would *"probably
sell some bitcoin to pay a dividend just to inoculate the market and send the message that we did it"*
and later called it *"a big nothing burger"*, arguing Strategy can buy 20 bitcoin for every one it
sells. On the Q2 call, the president and CEO said the company will sell bitcoin whenever management
considers it *"advantageous"* and that investors should *"expect that we may do that on a go-forward
basis"* [MANAGEMENT GUIDANCE].

**The "20 for 1" claim is true only while the ATM works.** With the common ATM gated below 1.0x mNAV,
the ratio in the ten weeks from mid-June was approximately **0 bought for every 1 sold.**

### The reverse flywheel, quantified

```
Annual carry funded entirely by bitcoin sales at $77,000:
    $1,633m ÷ $77,000  =  21,208 BTC per year  =  2.51% of the stack

Bitcoin per share, today            845,256 / 384.2m  =  ~220,000 sats
Bitcoin per share, in 12 months     824,048 / 384.2m  =  ~214,485 sats
                                                          −2.51%
```

Compare that with the +13.3% BTC Yield the company reported for the first five months of the year. **The
same metric now runs negative at roughly 2.5% a year, and it gets worse as bitcoin falls** — at $45,000
the bleed is 4.3% a year.

---

## 3.3 Commercial structures — what is available and what is used

| Mechanism | In use? | Economics |
|---|---|---|
| Committed / backstopped equity facility | **No** | Would convert $42bn of authorisation into actual committed capital. Its absence is why forward funding is $0 |
| Revolving credit facility | **Not disclosed** `[GAP]` | A B− issuer with no disclosed revolver has no liquidity backstop other than its own assets |
| Secured borrowing against bitcoin | **No** | Would be cheaper than 12% preferred but introduces margin-call risk against a volatile collateral — the one risk the current structure genuinely avoids |
| Yield on the asset (lending, staking) | **Not possible** | Bitcoin does not stake. Note the contrast: BitMine, the ETH treasury peer, funds a dividend from staking yield on 4.7m ETH. **Strategy structurally cannot do this** |
| Covered-call overwriting on the holding | Not disclosed | Would generate income at the cost of capping upside |
| Sale or spin of the software business | **No** | ~$1.5bn of value that could retire ~$1.5bn of 12% preferred, saving ~$180m/yr of carry |
| Convertible repurchase at a discount | **Yes** | $1.50bn repurchased for $1.38bn in May 2026 — **the single most clearly accretive act of 2026** |
| Take-or-pay / minimum volume | **No** | n/a |

Two rows deserve emphasis. **The absence of secured borrowing is a genuine credit strength** — Strategy
cannot be margin-called, which is why it survived a 33% bitcoin drawdown in H1 2026 without a forced
sale. And **the software business is the only asset that could be monetised without touching the
bitcoin**, worth roughly one year of carry.

---

## Required output: does this demand create value, destroy it, or merely relocate it?

**It destroys value at the margin today, and it is the destruction that is contractual.**

- **Common issuance** creates ~2¢ per dollar after fees at a 1.04x mNAV, against 74¢ at the November
  2024 peak — a 97% collapse in the value of the mechanism.
- **Preferred issuance** funds a ~1%-returning asset with 12% capital: an incremental margin of roughly
  **−11 percentage points**, on the company's own six-year record.
- **Bitcoin sales** to fund dividends relocate value from the balance sheet to the preferred holders,
  at a run-rate of **2.51% of the stack per year**, rising as the price falls.

**Where value is genuinely created:** repurchasing convertibles at a discount ($1.50bn for $1.38bn) and,
prospectively, monetising the software business to retire preferred. Both are balance-sheet
*shrinkage*. That is a real finding and a striking one — **in 2026 the only value-accretive actions
available to this company are the opposite of its stated strategy.**

**Who the demand is actually being served for:** the preferred holders. They are receiving a 10–12% cash
yield, senior to the common, funded partly by the sale of the asset the common owns. The structure is
not fraudulent and it is fully disclosed — but the direction of transfer is unambiguous, and Phase 4
sizes it.

---

## What this phase establishes

1. **Strategy's committed forward funding is $0.** A $42bn ATM authorisation is a permit to offer
   securities, not a pipeline; there is no backstop, standby purchase agreement or underwriting
   commitment. The obligations on the other side are contractual, cumulative and ratcheting.
2. **The common-issuance mechanism now produces about 2 cents of value per dollar raised**, after fees,
   at a 1.04x mNAV — down 97% from the 74 cents available at the November 2024 peak, and negative on a
   5% share-price fall.
3. **Preferred-funded bitcoin purchases carry an incremental margin of roughly −11 percentage points**:
   a ~1% realised asset return against a 12% cost of capital.
4. **Bitcoin sales to fund dividends have started and are policy, not accident** — 32 BTC in May, 3,588
   BTC for $216m in June, with management stating investors should expect more. The run-rate bleed is
   **2.51% of the stack a year**, rising to 4.3% at bitcoin $45,000.
5. **The company's headline KPI cannot fall when the strategy fails.** BTC Yield was +13.3% year to date
   while bitcoin value per share was −0.3% and the shares were ~65% below their high.

## What it could not establish

| Gap | Why it matters | Resolved by |
|---|---|---|
| **Software segment operating income and cash flow** | It is the only non-bitcoin source of cash. At $50m it covers 3% of the carry; at −$50m the hole is 6% bigger | Segment disclosure in the 10-Q |
| **Whether any committed or backstopped facility exists** | Would transform the funding picture from $0 committed to something underwritable. A B− issuer with no disclosed revolver is a materially different credit | The 10-Q debt and commitments notes |
| Total bitcoin sold to date in 2026 | Only two sales were retrievable (~3,620 BTC). The true cumulative figure sets the actual bleed rate | 8-K purchase/sale disclosures and the 10-Q |
| Remaining unissued capacity under each ATM programme, by series | Determines how long preferred issuance can substitute for common issuance before capacity, not appetite, binds | The 10-Q equity note and current prospectus supplements |
| Whether the 1-million-bitcoin target has been formally withdrawn | It is the company's only public forward commitment and is arithmetically unreachable without $12bn in four months | Q3 2026 results |

## What it changes about the thesis

Phase 2 asked where $1,633m a year comes from. Phase 3's answer is: **from selling the asset, or from
issuing more of the instrument that created the obligation.** Neither is growth. Both shrink bitcoin per
share, which is the only variable the equity is actually long.

The thesis is now fully specified and unusually clean. Strategy's equity is a **levered claim on
bitcoin, carrying a 2.51% annual fee that rises as bitcoin falls**, whose one historical source of
alpha — accretive issuance — is switched off and cannot restart until the thing it is supposed to cause
has already happened. Phase 4 tests whether that levered claim beats simply owning the asset.
