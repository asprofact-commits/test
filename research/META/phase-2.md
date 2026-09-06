# Phase 2 — Productive asset base & physical bottlenecks
## Meta Platforms, Inc. (NASDAQ: META) · as of 2026-09-06

**The question:** what actually produces Meta's output, what does each unit cost, and what physically
limits expansion?

For an advertising business the productive asset used to be the app. It is not any more. Since 2024
the marginal unit of output — a ranked, predicted, priced impression — has been produced by
**accelerated compute**, and compute is a physical asset with a power connection, a construction
schedule and a depreciation life. Phase 1 established that Meta's price per ad is an output of its
ranking models. Phase 2 sizes the machine that runs them.

---

## 2.1 The asset base

### The capital programme

| Period | Capex incl. finance-lease principal | y/y | Source |
|---|---|---|---|
| FY2024 | ~$39bn | — | `[GAP]` Not independently sourced in this run; shown only as the base for the FY2025 comparison. Do not rely on it. |
| FY2025 | **$72.22bn** | ~+84% (implied) | [FACT] Q4/FY2025 results, reported 2026-01-28 |
| Q1 2026 | $19.84bn | — | [FACT] Q1 2026 results, 2026-04-29 |
| Q2 2026 | **$31.08bn** | +83% vs $17.0bn in Q2 2025 | [FACT] Q2 2026 results, 2026-07-29 |
| H1 2026 | $50.94bn | +66% vs $30.7bn | [FACT] Q2 2026 results |
| FY2026 guidance | **$130–145bn** | +80–101% | [MANAGEMENT GUIDANCE] Q2 2026, raised from $125–145bn at Q1 and $115–135bn originally |
| FY2027 | Not guided. "Maximising capacity in 2026 and 2027, with flexibility to keep growing in 2028 and beyond" | — | [MANAGEMENT GUIDANCE] Susan Li, Q2 2026 call, 2026-07-29 |

The single most important sentence in the Q2 call is the refusal to guide 2027. Meta has committed the
supply chain and the land; it has not committed the number. Phase 5 treats 2027 capex as the primary
swing variable, because it is.

### On-balance-sheet is not the whole asset base

Two structures move a large part of the productive base off Meta's balance sheet:

| Structure | Size | Meta's interest | Accounting |
|---|---|---|---|
| **Hyperion JV (Blue Owl)** — Richland Parish, Louisiana | $27bn A+-rated SPV debt + $2.5bn equity, anchored by PIMCO ($18bn) and BlackRock ($3bn), arranged by Morgan Stanley | **20%** — Blue Owl-managed funds hold 80% | SPV debt **off Meta's balance sheet**; Meta leases the completed 4m sq ft facility back |
| **Future lease commitments** — data centres, colocation, network | **~$279bn**, commencing from the remainder of 2026 through 2036 | 100% obligor | Disclosed as not-yet-commenced leases; enters the balance sheet as ROU assets and lease liabilities as each commences |
| **El Paso, Texas** | ~$13bn being raised | n/d | Reported as a further off-balance-sheet style raise |

[FACT] Reporting on the Meta/Blue Owl Hyperion financing (Business Standard 2025-10-17; Global Data
Center Hub; Data Center Frontier); $279bn lease-commitment disclosure per Meta filings as summarised
in the same reporting. **`[GAP]`** — the $279bn figure could not be tied back to a specific note in
the 10-Q under this session's egress policy; it is used as a directional magnitude, not a precise input.

**This is the phase's first load-bearing conclusion.** Meta's reported net debt of roughly **negative
$6.6bn** (cash and marketable securities $90.26bn against long-term debt $83.66bn at 2026-06-30
[FACT, Q2 2026 10-Q]) understates the claim on future cash by an order of magnitude. Adding the
$279bn of committed leases and Meta's share of SPV obligations turns a net-cash balance sheet into a
leveraged one. Phase 4 quantifies this; Phase 2 flags that the asset base and the liability base were
built together and must be read together.

### Physical capacity: named sites, named power

| Site | Capacity | Status / timing | Power |
|---|---|---|---|
| **Prometheus** — New Albany, Ohio | ~1 GW | Coming online **2026** | Grid + on-site gas |
| **Hyperion** — Richland Parish, Louisiana | Phase 1 **2028**; ~1.5 GW targeted online by end-2027 on one account; 2 GW by 2030; **5 GW** stretch | 4m sq ft, ~3,650 acres (expanded by 1,400 acres in Feb 2026) | **Entergy building 10 gas-fired plants**, tripled from the 3 originally planned; a March 2026 agreement added 7 plants / 5.2 GW |
| **El Paso, Texas** | n/d | Financing ~$13bn | n/d |
| Fleet total | **32 AI data centres** identified as of May 2026 | Mixed | Mixed |

[FACT] Data Center Frontier, Quartz (2026-07), The Next Web, redact.dev site census (May 2026).
The 1.5 GW-by-end-2027 and phase-1-in-2028 statements come from different sources and are not
obviously consistent; both are reported here as the range rather than reconciled silently.

**Note what the power column says.** To energise one campus, Meta's utility partner is building ten
gas-fired power stations. The binding input is not silicon. It is electricity, and Meta is now
effectively procuring generation.

### Human asset base

| Metric | Value | Date | Source |
|---|---|---|---|
| Headcount | ~74,700 | 2026-03-31 | [FACT] −3% from 76,834 at 2025-12-31 |
| Restructuring | ~8,000 roles cut from 2026-05-20; ~6,000 open roles cancelled; ~7,000 staff reassigned into AI pods; further cuts flagged for H2 2026 | May 2026 | [FACT] trade press |
| Meta Superintelligence Labs | ~1,300 researchers and engineers under Alexandr Wang; ~600 laid off from parts of MSL | 2026 | [FACT] trade press |
| Researcher compensation | Reported packages up to **$300m over four years**; one reported $250m package | 2025–26 | [FACT, press-reported] |

The workforce is being converted from a headcount base into a compute base: cash that used to pay
engineers is paying for GPUs and for a much smaller number of much more expensive researchers.

---

## 2.2 The unit cost curve — what a gigawatt costs and what it must earn

Meta does not publish cost per unit of compute. The following is built from disclosed capital costs
and stated asset lives; every input is labelled and the arithmetic is shown, so the reader can flex it.

### Inputs

| Input | Value | Label / source |
|---|---|---|
| All-in capital cost per GW (shell + power + IT) | **$40bn** | [ANALYST ESTIMATE] from the reported "$200bn, 5 GW" Hyperion programme figure ÷ 5 GW |
| Shell/power share of that | ~30% ($12bn) | [ANALYST ESTIMATE] anchored on the $29.5bn Hyperion SPV (debt + equity) funding the facility, IT excluded |
| IT equipment share | ~70% ($28bn) | Balance |
| Server / network asset life | **5.5 years** from 2025-01-01 | [FACT] Meta accounting-estimate change disclosed 2025-01-29, cutting FY2025 depreciation by ~$2.9bn. *A separate report claims a further extension to 7 years; unverified — see `[GAP]`* |
| Shell life | 20 years | [ANALYST ESTIMATE] standard |
| Utilisation | 85% load factor | [ANALYST ESTIMATE] |
| Power price | $60/MWh | [ANALYST ESTIMATE] large-load industrial with self-build generation |
| WACC | 9.5% | [ANALYST ESTIMATE] — derived in Phase 4 |

### The cost curve, per GW per year

```
IT depreciation        $28bn ÷ 5.5 yrs                      =  $5.09bn
Shell depreciation     $12bn ÷ 20 yrs                       =  $0.60bn
                                                    D&A subtotal  $5.69bn
Power        1 GW × 8,760h × 0.85 = 7.45 TWh × $60/MWh      =  $0.45bn
O&M, staffing, networking (est. 0.75% of capital)           =  $0.30bn
                                          Cash + D&A cost   =  $6.44bn
Capital charge         $40bn × 9.5% WACC                    =  $3.80bn
                            ECONOMIC COST PER GW PER YEAR   = $10.24bn
```

| Threshold | Incremental gross profit a GW must generate | What it means |
|---|---|---|
| Accounting breakeven | **$6.4bn/yr** | Operating income unchanged |
| **Economic breakeven (ROIC = WACC)** | **$10.2bn/yr** | The only threshold that matters |

**Convert to revenue.** Meta's incremental ad revenue carries roughly an 80% gross margin before the
infrastructure charge itself [ANALYST ESTIMATE, from FY2025 cost structure]. So:

```
Revenue required per GW to clear cost of capital  =  $10.24bn ÷ 0.80  ≈  $12.8bn per GW per year
```

### The mix-shift arithmetic

The classic Phase 2 question — what happens when expensive marginal output is displaced by cheap
baseload — inverts for Meta. Meta is not displacing an expensive unit with a cheap one. It is
**adding an expensive unit to raise the price of the existing one**. The arithmetic that matters is
therefore: does the price uplift the new compute produces exceed the cost of the new compute?

Q2 2026, actuals, annualised:

```
Price uplift capture   price per ad +12% on $59.36bn ad revenue
                       ≈ $6.36bn of quarterly revenue attributable to price
                       ≈ $25.4bn annualised

Cost of producing it   total costs +55% y/y  =  +$14.9bn in the quarter
                       ex the $2.4bn legal charge and severance  ≈ +$12.5bn
                       ≈ $50.0bn annualised (ex-legal)

Recovery ratio         $25.4bn ÷ $50.0bn  =  51%
```

[FACT] inputs: Meta Q2 2026 results. [ANALYST ESTIMATE] the attribution of the price term to compute.

**The price gain currently recovers about half of the cost increase that produced it.** The volume
term (+14% impressions) supplies the rest and more — which is why revenue still grew 28% — but the
volume term is a function of ad load and surface expansion, not of compute, and it is finite.

State it plainly, per the guardrail: **on the evidence of Q2 2026 the incremental compute is not yet
paying for itself out of price. It is being paid for out of ad load.**

### Retirement, replacement and the maintenance/growth split

| FY2026E | $bn | Basis |
|---|---|---|
| Total capex (guidance midpoint) | **137.5** | [MANAGEMENT GUIDANCE] $130–145bn |
| Maintenance capex ≈ D&A run-rate | **~30** | [ANALYST ESTIMATE] FY2025 D&A ≈ $18.6bn (FY2025 EBITDA ~$101.9bn less EBIT $83.28bn), scaled for the 2025–26 additions |
| **Growth capex** | **~107.5** | Balance — 78% of the programme |

Roughly **four-fifths of the 2026 capital programme is growth capex**: capital spent to produce output
that does not yet exist and is not yet contracted. That is the correct denominator for Phase 4's
incremental-return test, and it is the number that has to be defended.

---

## 2.3 The bottleneck

| Constraint | Binding? | Evidence | Resolution path | Execution risk |
|---|---|---|---|---|
| **Electric power & interconnection** | **Yes — the primary constraint** | Entergy building 10 gas plants for Hyperion, tripled from 3; a further 7 plants / 5.2 GW agreed March 2026 | Self-procured generation, behind-the-meter gas, long-dated PPAs | **High.** Gas turbine lead times run multi-year; each plant needs state PSC approval; Louisiana ratepayer and environmental opposition is live |
| **Capital** | **Yes — newly binding in 2026** | Buybacks suspended; $25bn bonds issued May 2026 at 4.55–6.45%; $30bn issued Oct 2025; $27bn off-balance-sheet SPV; ~$13bn El Paso raise; reported consideration of an equity offering | Debt, private credit, JV equity, and — if it comes — equity issuance | **Medium.** Access is not in doubt at AA−/Aa3; the *price* of access is rising |
| **Accelerator supply** | Partially | Not a disclosed constraint in 2026; Meta's spend implies allocation is being secured | Vendor contracts, MTIA silicon | Medium |
| **Land, water, permitting** | Localised | Hyperion footprint expanded 1,400 acres Feb 2026 — expansion succeeded | Site banking | Low–medium |
| **Talent** | Yes, at the frontier | ~1,300 MSL researchers; packages to $300m/4yrs; ~600 MSL layoffs indicate churn as well as scarcity | Compensation, acquisition | Medium |

### Modelling the delay

The Phase 5 scenarios need a delay case. Take the critical path — Hyperion phase 1, currently 2028 —
and slip it two years to 2030:

```
Capacity deferred            ~1.5-2.0 GW
Revenue deferred at $12.8bn/GW/yr (economic-breakeven revenue)   ≈ $19-26bn/yr from 2028
Capex NOT deferred           Land, shell, power contracts and lease commitments are already signed;
                             the $279bn lease schedule commences on the landlord's timetable, not Meta's
Net effect                   Cost enters the P&L on schedule; revenue does not.
                             Two years of D&A and lease expense (~$11-13bn/yr) against no
                             incremental revenue
```

This asymmetry — **committed cost, uncommitted revenue** — is the structural shape of the bear case,
and it is the single most important thing Phase 2 hands to Phase 5.

---

## 2.4 Is the capex compensated?

Meta is not a regulated business. There is no rate base, no allowed return, no true-up and no
regulatory lag. **Nothing compensates this capital except the auction.** Which means:

| Test | Regulated utility | Meta |
|---|---|---|
| Does capex enter a rate base? | Yes, at an allowed ROE | **No** |
| Is recovery legally assured? | Yes, subject to prudence review | **No** |
| What is the recovery mechanism? | Tariff | Higher clearing price in an auction Meta does not control |
| What if the output is not needed? | Stranded-cost recovery is often available | **Total loss**, depreciated over 5.5 years |
| Asset life | 30–60 years | **5.5 years for the 70% of cost that is IT equipment** |

The 5.5-year life is the crux. A regulated utility can be wrong about demand for a decade and still
earn a return. Meta's IT capital must be fully recovered inside 5.5 years or it is not recovered at
all. At $137.5bn of 2026 capex, the fleet added this year alone imposes roughly **$25bn a year of
depreciation for five and a half years** whether or not the revenue arrives.

---

## What this phase establishes

1. **The productive asset base is now power-constrained compute, not software.** Meta's utility partner
   is building ten gas-fired power stations to energise a single campus; the binding physical
   constraint is electricity, and Meta has moved to procuring generation to relieve it.
2. **Each gigawatt must produce roughly $10.2bn a year of incremental gross profit — about $12.8bn of
   revenue — to earn its cost of capital.** That is the hurdle every Phase 3 demand claim must clear.
3. **The price uplift currently recovers about half the cost increase that produced it** (~$25bn
   annualised price capture against ~$50bn annualised cost growth ex-legal). The gap is being filled by
   ad load, which is finite.
4. **About 78% of the 2026 programme (~$107bn) is growth capex** — capital committed to output that is
   neither contracted nor yet built.
5. **The liability side was built with the asset side.** A reported net-cash balance sheet sits
   alongside ~$279bn of not-yet-commenced lease commitments and a $27bn off-balance-sheet SPV in which
   Meta holds 20% of the equity and 100% of the operational need.

## What it could not establish

| Gap | Why it matters | Resolved by |
|---|---|---|
| Meta's actual installed and planned compute capacity in GW, company-stated | Every unit-economics calculation here is anchored on inferred capacity; a stated GW figure would convert a range of estimates into arithmetic | Meta disclosing fleet GW, as some peers now do |
| Whether server life was extended again from 5.5 to 7 years | A 7-year life would cut annual IT depreciation per GW from $5.1bn to $4.0bn — roughly a 10% cut in the economic hurdle, and a large boost to reported EPS with no cash effect | Meta's FY2026 10-K accounting-estimate note |
| Precise reconciliation of the ~$279bn lease-commitment figure to the filing | It is the largest single claim on future cash in this analysis | The 10-Q lease note — unreachable under this session's egress policy |
| Named project delays with dated slippage | The delay scenario is modelled generically because no specific slipped milestone was found in public sources | Construction filings, utility interconnection dockets |
| FY2025 D&A: derived at ~$18.6bn, but one data source reports TTM D&A of $37.4bn | Doubles or halves the maintenance-capex split | Primary cash-flow statement |

## What it changes about the thesis

Phase 1 said the price mechanism is bought with compute. Phase 2 prices the compute and finds the
hurdle: **$12.8bn of revenue per gigawatt per year**. It also finds that the current cost increase is
outrunning the price increase by roughly two to one, with ad load covering the difference. The thesis
now has a falsifiable test rather than a narrative: Phase 3 must find, in named and classified demand,
enough incremental revenue per gigawatt to clear $12.8bn — or the capital programme is dilutive by
construction.
