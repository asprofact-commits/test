# KEPCO — Phase 1: Pricing-power architecture

**Korea Electric Power Corporation** · KRX: 015760 / NYSE: KEP · regulated utility
Price ~KRW 33,600 / share (ADR USD 12.26, 2026-08-10) · FX 1 USD = KRW 1,348.85 (2026-09-05)
Analysis date: 2026-09-05

> **Evidence warning.** No primary document was retrievable: SEC EDGAR, kepco.co.kr, MOTIE, the Korean press and the law-firm briefings are all blocked by this environment's network egress proxy. Every finding rests on search-result summaries. Article numbers and exact statutory wording are unverified. Nothing here should go to an investment committee without primary verification — the gap list at the end is ordered by how much the valuation depends on closing it.

---

## 1.1 The government–utility nexus and tariff mechanics

### Who sets the price

KEPCO proposes; MOTIE disposes. Retail tariff changes require the approval of the **Ministry of Trade, Industry and Energy**, in consultation with the **Ministry of Economy and Finance** `[REGULATORY STATUTE]`. There is no independent regulator standing between the company and the government, and no rate case in the Anglo-American sense — no adversarial proceeding, no published allowed return, no statutory test the ministry must satisfy before refusing.

That absence is the whole architecture. A US or UK utility that is refused a rate increase can point to a settlement it is entitled to; KEPCO can point to nothing.

### The one formula, and how it has actually behaved

The **Fuel Cost Adjustment Tariff** is the sole formulaic pass-through. Its bounds are statutory `[REGULATORY STATUTE]`:

- reference period: coal and LNG prices of the preceding three months
- adjustment band: **±KRW 5/kWh per quarter**
- minimum threshold: KRW 1/kWh

Two features of the design matter more than the formula. First, the band is narrow: KRW 5/kWh against an industrial tariff averaging roughly KRW 180/kWh is under 3% per quarter. Second, and decisively, **the formula has not been permitted to operate in either direction since Q3 2022** — roughly seventeen consecutive quarters pinned at the +KRW 5/kWh ceiling `[FACT]`. When falling fuel costs generated a downward adjustment factor, the rate was held at +5 anyway, citing KEPCO's finances and accumulated unadjusted charges `[FACT, 2025-12-22]`.

So the mechanism is asymmetric in practice: it is being used as a slow recovery instrument for past losses, not as an indexation formula. That has a consequence the bulls tend to miss — **the adjustment tariff is already at its ceiling, so it offers no protection against the next fuel spike.** H1 2026 fuel costs rose 8.8% to KRW 10.1tn into a frozen tariff with no headroom `[FACT, 2026-08-14]`.

### The political override

The mandate asks under what exact legal conditions the government can suspend a rate rise to curb inflation. I could not verify the statutory text `[GAP]`. What the record establishes is stronger than the statute anyway:

| Date | Action | Stated trigger | Effect |
|---|---|---|---|
| Q2 2022 | Announced increase postponed | Incoming President's pledge to freeze household bills | Direct contribution to the 2021–23 losses |
| Q3 2022 → | Adjustment pinned at +KRW 5/kWh | Inflation management | ~17 quarters, no movement either way |
| Oct 2024 | Industrial-only +9.7% (large 10.2%, SME 5.2%); households frozen | Compromise: KEPCO losses vs household inflation | Recovery loaded entirely onto industry |
| Q1 2026 | Frozen — government "notified KEPCO to maintain the current rate" | KEPCO finances, accumulated unadjusted charges | Explicit ministerial direction on a "formulaic" tariff |
| Q2–Q3 2026 | Frozen again | Financial troubles / inflation | Fuel +8.8% into a frozen tariff |
| Aug 2026 | Regional discounts, no metro premium | Regional industrial policy | ~KRW 2.8tn/yr foregone |

`[FACT]` throughout.

The 2021–23 episode is the calibration point: **KRW 43 trillion of combined losses** from selling below production cost while LNG and coal surged `[FACT]`. That is what the override costs equity holders when fuel moves against a frozen tariff. It is not a hypothetical.

### The SMP cap — real downside protection, with a limit

MOTIE's amendment to the *Notice on Capping Electricity Exchange Price* (24 May 2022) permits capping the System Marginal Price payable to generators during emergencies such as fuel-price spikes `[REGULATORY STATUTE]`. Since KEPCO is the buyer in the pool, a cap on SMP is a cap on its procurement cost.

This is genuine and it cuts KEPCO's way. But its value is bounded by two things:

1. MOTIE stated that generators **would be separately compensated for actual fuel prices paid**, and that private generators would be compensated where fuel costs exceed the cap `[REGULATORY STATUTE]`. The cap therefore transfers generator *margin*, not generator *cost*. In a genuine fuel spike, the cost still lands somewhere, and the compensation obligation limits how much of it stops at the generator.
2. Six of the gencos selling into the pool are KEPCO's own consolidated subsidiaries. Capping what they receive is an intra-group transfer that nets to roughly zero on consolidation. **Only the third-party IPP share is a real consolidated saving** `[ANALYST ESTIMATE]`, and I could not size that share `[GAP]` — it is the hinge of the whole downside-protection argument.

**Assessment of 1.1:** statutory formulae bound KEPCO's upside; ministerial discretion governs its downside, without a comparable bound. That asymmetry, not the fuel price, is the central risk in this name.

---

## 1.2 Regional tariffs and locational pricing

### The legal basis

The **Special Act on the Promotion of Distributed Energy** was enacted in June 2023 and entered force in June 2024 through its enforcement decree, creating the legal basis for regionally differentiated tariffs — a supplier "may set different electricity price by region in consideration of transmission and distribution costs in such region" `[REGULATORY STATUTE]`.

Note what the enabling language permits: differentiation *by cost to serve*. Note what was actually announced.

### What was announced, 26–27 August 2026

Four broad areas, subdivided into **11 final pricing zones** on regional-development criteria, Jeju excluded `[FACT]`:

| Zone | Change (KRW/kWh) | Change (%) |
|---|---|---|
| Southern Gyeongsang & Jeolla (Honam / Yeongnam) | **−13 to −18** | −7 to −10% |
| Gangwon, Daejeon, Chungcheong, Sejong | −10 to −15 | −5 to −8% |
| Northern Seoul, Incheon, northern Gyeonggi | −6 to −10 | −3 to −8% |
| **Southern Seoul & southern Gyeonggi** | **−0 to −1** | **~0%** |

*(Sources differ on presentation — some report four zones, others eleven. They describe the same scheme at different granularity; I have used both.)*

**Every zone that moves, moves down.** The highest-cost-to-serve region — the southern capital area, the one that requires the long-distance transmission the Act was written to avoid building — is the single region whose rate does not change. A scheme justified by locational cost has been implemented as a discount-only regional development subsidy.

### Net revenue impact on KEPCO

The stated benefit is **KRW 2.8 trillion a year** to industrial users outside the southern capital area, targeted for introduction by end-2026 `[FACT]`. Customer savings are supplier revenue foregone. Absent a compensating mechanism — and I found none `[GAP]`:

| Measure | Value | KRW 2.8tn as % |
|---|---|---|
| FY2025 operating profit | KRW 13.5tn | **20.7%** |
| H1 2026 revenue annualised | ~KRW 92.6tn | 3.0% |
| FY2025 total dividend | KRW 0.99tn | 283% |

`[ANALYST ESTIMATE]` — derived as 2.8/13.5 and 2.8/(46.3×2).

That third line is the one to sit with. **The annual revenue give-away is roughly 2.8× the entire FY2025 dividend.**

### Does the wholesale leg offset it?

This is the bull rebuttal: LMP reform lowers what KEPCO pays non-metropolitan generators, offsetting the retail discount. Academic modelling of Korean zonal pricing puts metro prices on average **10.16 KRW/kWh above non-metro**, against a uniform national SMP of 123–144 KRW/kWh `[ANALYST ESTIMATE, arXiv 2605.09318]`, and finds non-metro generators are overcompensated under uniform pricing despite transmission-constrained output. Directionally the offset is real.

Two things cut it down:

1. **The intra-group problem again.** Paying KEPCO's own six gencos less is not a consolidated saving. Only the third-party IPP share is `[GAP: unsized]`.
2. **The IPPs are objecting.** "Private generators balk" `[FACT, KED Global 2026-08-26]`. The retail discount has a date (end-2026); the wholesale offset has an argument.

A retail cut with a date, funded by a wholesale saving that is partly an internal transfer and partly still contested, is not a revenue-neutral reform. It is a dated cost with an undated offset.

---

## 1.3 Ownership, governance and shareholder alignment

### The structure

| Holder | Stake | Objective | Aligned? |
|---|---|---|---|
| Korea Development Bank | 32.9% | State policy instrument | No |
| Republic of Korea | 18.2% | Industrial competitiveness, consumer prices, inflation | No |
| National Pension Service | 7.51% | Investment return | Yes |
| Free float / other | ~41.4% | Investment return | Yes |

The **KEPCO Act requires** the Government, directly or through KDB, to hold **at least 51%** `[REGULATORY STATUTE]`. Combined: 51.1% — the floor, essentially exactly.

This is the part that cannot be reformed away by engagement. The conflict is not a governance failing to be fixed; it is a statutory design. Minorities hold ~49% of the economics and none of the control, and every stated objective of the controlling shareholder — industrial competitiveness, consumer inflation, regional development — is served by a *lower* tariff.

The mandate asks whether a state-controlled monopoly can legally and operationally prioritise minority returns when national industrial competitiveness demands low-cost power. On this evidence: **legally, perhaps; operationally, it never has when the two conflicted.** August 2026 is the most recent demonstration — a KRW 2.8tn transfer from the listed company to industrial users, announced as industrial policy.

### Value-Up: signal or substance?

- FY2025 dividend of **KRW 1,540/share, KRW 988.6bn total, 3.2% yield** — the second consecutive year after a four-year suspension `[FACT]`.
- The government framed the resumption of SOE dividends as a positive signal "in line with the Corporate Value-up Program" `[FACT, 2025-02-28]`.
- **756 listed companies had filed Value-Up plans by end-August 2026, covering 87.7% of KOSPI market value** `[FACT]`.
- **No KEPCO value-up plan with ROE or PBR targets could be located** `[GAP — high priority]`.

A dividend the government describes as a Value-Up signal is not the same as a filed plan with targets a board can be held to. Until that disclosure is found, the honest read is that KEPCO participates in the *rhetoric* of Value-Up while the state's other objectives continue to set the tariff.

### The structural discount

The derived numbers are stark. Shares outstanding ≈ **642 million** (KRW 988.6bn ÷ KRW 1,540) `[ANALYST ESTIMATE]`. A 3.2% yield on KRW 1,540 implies ~**KRW 48,100** at declaration in February 2026. The derived current price of ~KRW 33,600 is **~30% below that**, consistent with the ADR falling from a 52-week high of USD 23.41 to USD 12.26 `[ANALYST ESTIMATE]`.

**The equity has roughly halved during the best reported year in the company's history.** FY2025 delivered a record KRW 13.5tn operating profit `[FACT]`; the market responded by cutting the price in half.

That is not a market failing to notice cheapness. That is a market repricing the *claim* — deciding what a minority share of a policy instrument is worth — while H1 2026 profit fell KRW 976.8bn, fuel rose 8.8%, the regional discount was announced, and the 5× bond ceiling moved a year closer to expiry. A discount that behaves this way does not close because the multiple is low. It closes when the mechanism changes.

---

## What this phase establishes

1. **KEPCO does not set its price.** MOTIE approves with MOEF; the one formulaic mechanism has been pinned at its statutory ceiling for ~17 quarters and was explicitly directed to stay there. The formula bounds the upside at ±KRW 5/kWh; discretion governs the downside without bound.
2. **The override is the operating norm, not a tail risk.** Every documented episode since 2022 runs one direction, and KRW 43tn of 2021–23 losses is the price tag from the last time fuel moved against a frozen tariff.
3. **August 2026 is uncompensated regulatory action, live.** ~KRW 2.8tn/yr — 20.7% of FY2025 operating profit, 2.8× the dividend — with every moving zone moving down and the highest-cost region left unchanged.
4. **The wholesale offset is weaker than presented.** Six gencos are consolidated subsidiaries, so much of any SMP saving is an internal transfer; the genuinely external portion is unsized and the IPPs are objecting.
5. **The 51% is statutory.** Minorities hold ~49% of the economics and none of the control. The FY2025 dividend is real; a Value-Up plan with targets has not been found.

## What this phase could not establish

Ranked by how much the valuation depends on it:

1. **Whether the KRW 2.8tn regional discount is compensated.** The difference between a ~21% cut to operating profit and a revenue-neutral reallocation. → MOTIE implementing notice, expected before end-2026.
2. **The third-party IPP share of pool purchases.** Determines whether any wholesale saving is real on consolidation or an intra-group transfer. → KPX settlement data by generator ownership; 20-F segments.
3. **KEPCO's Value-Up plan, if one exists.** Governance catalyst or governance rhetoric. → DART search for 기업가치 제고 계획.
4. **The exact legal conditions for tariff deferral.** The record shows the government does it; the statutory basis and any limits remain unverified. → Electric Utility Act and the fuel cost adjustment notice.
5. **Primary-document verification of everything above.** → KEPCO 2025 Form 20-F, filed 2026-04-29.
6. **An observed KRX price.** Market-cap sources disagree by 29%. → a KRX quote for 015760.

## What it changes about the thesis

KEPCO is not a utility with a regulatory lag. It is a **policy instrument with a listed equity attached**, and the equity is a residual claim on whatever margin survives after industrial competitiveness, consumer inflation and regional development have been served.

The practical consequence for Phases 2–5: a bull case cannot rest on the low multiple, because the multiple has been low throughout and just got lower during a record year. It must rest on a **specific, dated mechanism that forces tariffs to follow cost**. The remaining phases should be read as tests of whether one exists — the grid programme (is the capex compensated, and does it enter a rate base?), the large-load demand (is it priced above marginal cost, and does the KRW 25tn prepayment request to Samsung and SK Hynix become a structural funding mechanism?), and the bond ceiling reverting from 5× to 2× at end-2027 (does the state finally have to choose between funding the grid and suppressing the tariff?).

That last one is the most interesting thing in this phase. **The state has, until now, been able to have both cheap power and a funded grid, because KEPCO's balance sheet absorbed the difference. In 2028 that stops being arithmetically possible.**

---

### Sources

Search-result summaries only; no primary document was retrievable from this environment.

[S&P Global — Korea raises industrial rates, freezes household bills](https://www.spglobal.com/energy/en/news-research/latest-news/lng/102324-south-korea-raises-electricity-rates-for-industrial-use-while-freezing-bills-for-households) ·
[Korea Times — KEPCO hikes industrial rates](https://www.koreatimes.co.kr/business/companies/20241023/kepco-hikes-industrial-electricity-rates-keeps-residential-fees-steady) ·
[Korea Times — rate frozen for Q1](https://www.koreatimes.co.kr/business/20251222/kepco-keeps-electricity-rate-frozen-for-q1) ·
[Asia Business Daily — Q1 freeze, fuel adjustment held at +5](https://cm.asiae.co.kr/en/article/2025122208535329107) ·
[UPI — fuel surcharge unchanged for Q2 2026](https://www.upi.com/Top_News/World-News/2026/03/23/electric-power-corp-unchanged-electricity-rates/1851774310122/) ·
[Korea Times — rates frozen for Q3 2026](https://www.koreatimes.co.kr/economy/20260622/kepco-to-keep-electricity-rates-frozen-for-q3-amid-financial-troubles) ·
[Korea Times — political pressure stalls rate rise (2022)](https://www.koreatimes.co.kr/www/tech/2022/03/419_325864.html) ·
[Shin & Kim — Cap on SMP in Emergencies](https://shinkim.com/eng/media/newsletter/1832) ·
[Lexology — Cap on SMP in Emergencies](https://www.lexology.com/library/detail.aspx?g=55f3fb28-aec6-4433-a4dd-26b1001644f7) ·
[Lexology — Special Act on Promotion of Dispersed Energy](https://www.lexology.com/library/detail.aspx?g=84bba4f2-2baf-4532-a5d3-e5991dcc16a1) ·
[Kim & Chang — Distributed Energy subordinate laws](https://www.kimchang.com/en/insights/detail.kc?sch_section=4&idx=28740) ·
[Korea Herald — regional power pricing, W2.8tr savings](https://www.koreaherald.com/article/10853269) ·
[Seoul Economic Daily — cut industrial rates up to 10% in southern regions](https://en.sedaily.com/finance/2026/08/27/korea-to-cut-industrial-power-rates-by-up-to-10-percent-in) ·
[KED Global — private generators balk](https://www.kedglobal.com/energy/newsView/ked202608260010) ·
[TechTimes — 11 electricity zones](https://www.techtimes.com/articles/325742/20260827/south-korea-creates-11-electricity-zones-slash-ai-data-center-costs.htm) ·
[Ajupress — southern industrial power rates](https://www.ajupress.com/view/20260826144118563) ·
[Seoul Economic Daily — record profit, $145bn debt](https://en.sedaily.com/finance/2026/02/27/kepco-posts-record-profit-but-145b-debt-and-grid-investment) ·
[Korea Times — dividend for first time in 4 years](https://www.koreatimes.co.kr/business/banking-finance/20250228/state-utility-korea-electric-power-corp-to-pay-dividend-for-1st-time-in-4-years) ·
[Globe and Mail — H1 2026 earnings](https://www.theglobeandmail.com/investing/markets/stocks/KEP-N/pressreleases/3823866/kepco-first-half-2026-earnings-show-profitability-strain-amid-flat-revenues/) ·
[Motley Fool — KEP Q2 2026 call transcript](https://www.fool.com/earnings/call-transcripts/2026/08/14/kep-q2-2026-earnings-call-transcript/) ·
[Investing.com — Q2 2026 slides, profit falls as fuel costs rise](https://in.investing.com/news/company-news/kepco-q2-2026-slides-profit-falls-as-fuel-costs-rise-net-zero-push-continues-93CH-5552659) ·
[Asia Business Daily — rates frozen, costs soaring; bond cap](https://www.asiae.co.kr/en/article/2026062609561371649) ·
[IEEFA — KEPCO cannot keep resorting to bonds](https://ieefa.org/resources/kepco-cannot-keep-resorting-bonds-pay-fossil-linked-debt) ·
[Seoul Economic Daily — Samsung/SK Hynix asked to prepay W25tn](https://en.sedaily.com/finance/2026/09/03/kepco-asks-samsung-sk-hynix-to-prepay-25-trillion-won-in) ·
[Seoul Economic Daily — Value-Up disclosures reach 756 firms](https://en.sedaily.com/finance/2026/09/03/value-up-disclosures-reach-756-percent-of) ·
[arXiv — Price Distortions in Korea's Electricity Market](https://arxiv.org/abs/2605.09318) ·
[Investing.com — KEP quote](https://www.investing.com/equities/korea-electric-power-corp) ·
[TradingEconomics — KRW](https://tradingeconomics.com/south-korea/currency)
