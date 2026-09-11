# Phase 3 — Demand & monetisation structure
## Meta Platforms, Inc. (NASDAQ: META) · as of 2026-09-06

**The question:** where does incremental demand come from, how firm is it, and does serving it create
value?

Phase 2 set the hurdle: **$12.8bn of incremental annual revenue per gigawatt** to earn the cost of
capital on the compute Meta is building. Phase 3 goes looking for that revenue.

---

## 3.1 The demand map

### The single most important structural fact

**Meta has essentially no contracted revenue.** There is no take-or-pay, no minimum-volume floor, no
indexation clause and no multi-year offtake behind the ~$240bn of advertising it will sell this year.
Every dollar is re-won in a spot auction, every day. An advertiser can halve its Meta budget on a
Monday morning at no cost.

This is not a criticism — it is the structure of the industry, and it has served Meta extraordinarily
well for twenty years. But it must be stated at the top of a phase whose job is to classify demand
firmness, because it determines the answer:

| Class | Test | Meta's FY2027E incremental revenue in this bucket |
|---|---|---|
| `[Existing Contracted]` | Signed, binding, take-or-pay | **~$0bn** |
| `[Approved / Committed Pipeline]` | Shipping product, inventory live, capacity reserved | **~$50bn** |
| `[Unfunded Planned Project]` | Announced or trialled, not launched at scale | **~$3–8bn** |
| `[Speculative Demand]` | Extrapolation, MOU, aspiration | **unbounded, weighted zero** |

An asset with a $137bn annual capital programme and a zero-dollar contracted book is a fundamentally
different risk object from one with the same capex and a signed offtake. That asymmetry is the whole
of Phase 3.

### Named demand sources

| # | Source | Counterparty / market | Unit driver | Size | Start | **Class** |
|---|---|---|---|---|---|---|
| 1 | Core Feed/Reels ad load + price | ~10m advertisers, no concentration | Impressions × price per ad | $59.36bn/qtr, +27% y/y | Live | `[Approved / Committed]` |
| 2 | Ranking-model uplift (GEM, Andromeda) | Same | Price per ad | +12% y/y = ~$25bn annualised | Live | `[Approved / Committed]` |
| 3 | **Threads ads** | Broadening to UK, EU, Brazil | New impression supply | Not separately disclosed | 2026 rollout | `[Approved / Committed]` |
| 4 | **WhatsApp Status ads** | Global, phased | New impression supply | Not separately disclosed | Through FY2026 | `[Approved / Committed]` |
| 5 | **WhatsApp paid messaging** | Businesses, esp. LatAm/APAC | Conversations | **>$2.0bn annual run-rate** at Q4 2025 | Live | `[Approved / Committed]` |
| 6 | **Business AI agents** | >1m businesses using them weekly in Q2 2026; >1m weekly conversations in Mexico and the Philippines alone | Conversations → subscription + usage billing | Revenue not disclosed | Globally available on WhatsApp and Messenger from Q2 2026 | `[Approved / Committed]` (product) / `[Unfunded Planned]` (pricing) |
| 7 | **Meta AI consumer subscriptions** — Meta AI Plus / Premium | Tested in Singapore, Guatemala | Subscribers × ARPU | Not disclosed | Test | `[Unfunded Planned]` |
| 8 | **Hatch agent platform / "Watermelon" model, reported $199.99/mo tier** | Reported from internal documents | Subscribers × $2,400/yr | Not launched | n/d | `[Unfunded Planned]` |
| 9 | **Vibes** AI video, freemium credits | Consumer | Credit packs | Not disclosed | Live, freemium | `[Unfunded Planned]` |
| 10 | Muse model family / API tokens | Developers; "trillions of tokens weekly" for some users | Tokens | Not disclosed; open-weights strategy suppresses direct monetisation | Live | `[Speculative]` as a revenue line |
| 11 | Reality Labs hardware | Consumer | Units | **$431m/qtr and shrinking in relevance** | Live | `[Approved / Committed]`, immaterial |
| 12 | "Personal superintelligence" / enterprise AI / agentic commerce take rates | — | — | Unbounded in the narrative | — | **`[Speculative]` — zero weight** |

[FACT] sources: Meta Q2 2026 results (2026-07-29) for items 1, 2, 11; Meta Q4 2025 commentary for
item 5; Meta Q2 2026 disclosure and trade press for item 6; press reporting (Yahoo Finance/Forkast,
tech-insider) for items 7–9; CNBC 2026-08-10 for item 10.

**`[GAP]` — and it is the most consequential gap in this entire analysis.** Meta does not break out a
single dollar of AI-attributable revenue. Business messaging, agents, subscriptions and Meta AI are
all inside "Family of Apps". There is no disclosed line against which the $137bn capital programme can
be tested directly. Every revenue-per-gigawatt statement below is therefore an inference from the
consolidated numbers, not a measurement.

### The demand bridge

FY2025 actual → FY2027E, in revenue rather than volume, because volume (impressions) is not disclosed
in absolute terms:

| Step | $bn | Basis |
|---|---|---|
| FY2025 revenue | **200.97** | [FACT] |
| + Price per ad (ranking uplift) | +26 | [ANALYST ESTIMATE] ~12% on the ad base |
| + Impressions (ad load, new surfaces) | +28 | [ANALYST ESTIMATE] ~14% |
| − Regional and mix drag | −3 | [ANALYST ESTIMATE] APAC at +19% dilutes the blend |
| **= FY2026E revenue** | **~252** | [ANALYST ESTIMATE]; Q1 $56.31bn + Q2 $60.80bn actual, Q3 guided $61–64bn, Q4 estimated ~$72bn |
| + Price per ad | +24 | Decelerating: model gains compound off a larger base |
| + Impressions incl. Threads and WhatsApp Status | +26 | Threads/Status are the marginal new supply |
| + Business messaging and agents | +5 | From a >$2bn run-rate base |
| − Youth-safety design mandates (time limits, nighttime block) | −2 | [ANALYST ESTIMATE] first regulatory instrument to cut impressions directly |
| **= FY2027E revenue** | **~305** | Matches [CONSENSUS] ~$305bn |

My independent bridge lands on the consensus number. That is worth stating: **the disagreement with
the market in this report is not about revenue. It is about what the revenue costs.**

---

## 3.2 Value capture — is the volume worth having?

### The incremental margin calculation

This is the calculation the guardrail exists for. It uses Meta's own guidance, not my assumptions.

```
FY2025 actual        revenue $200.97bn      operating income $83.28bn      margin 41.4%
FY2026E              revenue ~$252bn        expenses $165-169bn (guidance, midpoint $167bn)
                                            → operating income ≈ $85bn     margin 33.7%

Δ revenue            $252bn − $200.97bn                    =  +$51.0bn
Δ operating income   $85bn  − $83.28bn                     =  +$1.7bn

INCREMENTAL OPERATING MARGIN  =  $1.7bn / $51.0bn          =  3.3%
AVERAGE OPERATING MARGIN (FY2025)                          =  41.4%
```

[MANAGEMENT GUIDANCE] FY2026 total expenses $165–169bn and "operating income above 2025" (Q2 2026,
2026-07-29). [ANALYST ESTIMATE] FY2026 revenue ~$252bn, built from two reported quarters and guided Q3.

**Incremental margin is 3.3% against an average margin of 41.4%. In the words the protocol requires:
growth dilutes returns.** Meta is adding fifty-one billion dollars of revenue and keeping under two
billion of it at the operating line.

Two honest qualifications, both of which I have tested and neither of which changes the conclusion:

1. *The $2.4bn Q2 legal charge and severance inflate 2026 costs.* Add both back and incremental
   operating margin rises to roughly **11%** — still a quarter of the average margin.
2. *Depreciation is a sunk-cost artefact of past capex, not a cost of this year's revenue.* True, and
   it is precisely the point: this year's capex creates the next five and a half years of that
   artefact. On an EBITDA basis the incremental margin looks fine; on an EBIT basis it is 3.3%; on a
   free-cash basis it is **negative** (below).

### The free cash flow test

| | FY2025 | H1 2026 | FY2026E |
|---|---|---|---|
| Operating cash flow | $115.8bn (derived) | **$64.09bn** | ~$136bn [ANALYST ESTIMATE] |
| Capex incl. finance leases | $72.22bn | $50.94bn | $130–145bn [GUIDANCE] |
| **Free cash flow** | **$43.59bn** | **$13.17bn** | **~$0bn (range −$9bn to +$6bn)** |
| Dividends paid | — | ~$2.7bn | ~$5.4bn |
| Buybacks | — | **$0** | $0 |

[FACT] FY2025 FCF $43.59bn; Q1 2026 OCF $32.23bn / FCF $12.39bn; Q2 2026 OCF $31.86bn / FCF **$0.784bn**,
down ~91% y/y, with capex consuming 98% of operating cash flow. Q2 dividends of $1.353bn exceeded Q2
free cash flow by ~$569m.

**Meta's free cash flow goes to approximately zero in 2026 and the dividend is being paid out of
borrowings.** That is not a forecast; two of the four quarters are reported.

### Does the incremental revenue clear the Phase 2 hurdle?

This is the arithmetic that decides the investment case.

```
Capacity added, 2025 + 2026        ($72.22bn + $137.5bn) ÷ $40bn/GW   ≈  5.2 GW
Revenue required from that vintage  5.2 GW × $12.8bn/GW/yr            ≈  $67bn per year, at maturity

Capacity added, 2027E (at $165bn)   $165bn ÷ $40bn/GW                 ≈  4.1 GW
Additional revenue required          4.1 GW × $12.8bn                 ≈  $53bn per year

Actual annual revenue increments     FY2025 +$36.5bn
                                     FY2026E +$51.0bn
                                     FY2027E +$53.0bn (consensus)
```

Read the last two blocks against each other. **At a $165bn annual capital programme, each year of
spending adds about $53bn to the annual revenue Meta must earn simply to break even on its cost of
capital — and Meta's actual annual revenue increment is about $51–53bn.** At the $180bn+ run-rate the
2027–28 plans imply, the required-revenue hurdle grows by ~$58bn a year against actual growth of
~$51bn.

The programme is, at the current run-rate, **running to stand still**. It clears its cost of capital
only under one of three conditions:

| Condition | What it requires | Plausibility on Phases 1–2 evidence |
|---|---|---|
| **Capex plateaus** | 2027 spend flat to modestly up, then flat 2028–30, letting revenue catch the installed base | **Medium.** Management refused to guide 2027 and has raised guidance twice. But a plateau is entirely within its control, and the buyback suspension shows it is watching the funding line |
| **Revenue per GW is far above $12.8bn** | Either capex per GW is well below $40bn, or the incremental gross margin is above 80%, or a GW serves far more revenue than assumed | **Medium.** This is the most likely place my arithmetic is wrong, and it is why Phase 5 flexes it |
| **A second revenue stream arrives** | Meta AI subscriptions, business agents or model licensing at $20bn+ scale | **Low in the base case.** Everything in this bucket is `[Unfunded Planned]` — trialled in Singapore and Guatemala, or reported from internal documents |

### Commercial structures — what Meta could do and does not

| Mechanism | In use? | Economics if used |
|---|---|---|
| Upfront customer capital contributions | **No** | Would shift data-centre capex to the customer — the single highest-value structure available and entirely absent |
| Long-term contracts with take-or-pay | **No** | Would convert spot auction revenue into a contracted book and re-rate the multiple |
| Volume commitments / minimum spend | Limited, at the largest agency-holding-company level; not disclosed | Modest floor |
| Indexation | **No** | n/a |
| Premium/priority tiers | **Partially** — Meta Verified, Meta AI Plus/Premium (test markets), Business Agent subscriptions, Vibes credits | High-margin, small; the only structural monetisation innovation on the list |
| Usage-based billing | **Emerging** — business messaging (>$2bn run-rate), agent conversations | Genuinely incremental; low capital intensity; the most attractive economics in the company |
| Model/API licensing | **Deliberately foregone** — Muse Spark 1.2 open-weighted, Muse Glimmer open-source | Gives away the direct monetisation of the compute in exchange for ecosystem position |

The last row deserves a sentence of its own. Meta is spending $137bn a year on compute and then
**publishing the weights of the models that compute produces**. That is a defensible strategy — it
commoditises a rival's moat and attracts talent — but it means the AI capex must be justified
*entirely* through advertising and first-party products. There is no licensing annuity to fall back on.

---

## Required output: does this demand create value, destroy it, or merely relocate it?

**On the FY2026 numbers, this demand destroys value at the margin.** The evidence:

- Incremental operating margin of **3.3%** against an average of 41.4% (11% if you forgive the legal
  charge and severance).
- Free cash flow of approximately **zero** on $252bn of revenue, with the dividend funded by debt.
- A required-revenue hurdle growing at roughly the same rate as actual revenue — so the capital is not
  yet buying a widening spread, it is buying a treadmill.

**It relocates value in one specific and important direction:** from Meta's shareholders to Meta's
competitive position. The compute is buying share of a market Meta is defending against TikTok's newly
unencumbered US venture and OpenAI's ad platform. Defensive capex is not valueless — the counterfactual
of *not* spending it may well be worse — but it must be underwritten as defence, at defence's returns,
not as growth at growth's returns.

**Where it plausibly creates value:** business messaging and agents. WhatsApp paid messaging at a
>$2bn run-rate, more than a million businesses using Business Agents weekly, and usage-based billing
attached — that is genuinely incremental revenue on genuinely low incremental capital. It is also,
today, about 1% of revenue. It is the right thing to watch and the wrong thing to capitalise.

---

## What this phase establishes

1. **Meta's contracted revenue is approximately zero.** A $137bn annual capital programme is being
   underwritten by a spot auction with no floor, no offtake and no indexation.
2. **Incremental operating margin is 3.3% against an average of 41.4%** — computed from management's
   own expense guidance. Growth dilutes returns, in those words.
3. **Free cash flow reaches roughly zero in FY2026** and the dividend is debt-funded; Q2 FCF was
   $784m against $1,353m of dividends.
4. **The required-revenue hurdle is growing as fast as revenue.** At a $165–180bn capital run-rate the
   annual increase in required revenue (~$53–58bn) matches or exceeds Meta's actual annual revenue
   increase (~$51–53bn). The base case needs a capex plateau, not a demand surprise.
5. **My revenue bridge agrees with consensus (~$305bn for 2027).** The disagreement with the market is
   not about revenue. It is about what the revenue costs.

## What it could not establish

| Gap | Why it matters | Resolved by |
|---|---|---|
| **Any AI-attributable revenue line** | There is no disclosed figure against which the $137bn programme can be tested. This is the highest-value missing disclosure in the company | Meta breaking out business messaging, agents, and AI subscriptions — as it once did for Reality Labs |
| Threads and WhatsApp Status ad revenue | These are the marginal new impression supply; their price per ad determines whether new inventory is accretive or dilutive | Segment or surface-level disclosure |
| Meta AI subscription funnel: subscribers, ARPU, conversion in test markets | Determines whether items 7–9 ever leave the `[Unfunded Planned]` bucket | Company disclosure or app-store estimates |
| Advertiser concentration and budget elasticity | With no contracts, elasticity is the only defence against a downturn | Not disclosed |
| Actual revenue per gigawatt | The single input that would confirm or destroy the Phase 2 hurdle | Meta disclosing fleet GW alongside AI revenue |

## What it changes about the thesis

Phase 2 asked whether the demand exists to clear $12.8bn per gigawatt. Phase 3's answer is: **the
revenue exists, but the margin on it does not — yet.** The demand is real, growing 27%, and needs no
heroic assumptions. What fails the test is the conversion of that demand into incremental profit, and
the failure is arithmetically attributable to the capital programme rather than to competition,
regulation or user decline.

That narrows the investment question to a single variable, which Phase 4 must now stress and Phase 5
must price: **when does capex plateau?** Everything else in this company is working.
