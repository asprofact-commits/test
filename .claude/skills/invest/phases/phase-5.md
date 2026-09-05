# Phase 5 — Valuation, stress tests & investment committee memo

**The question:** what is it worth, what would make us wrong, and what do we do?

Run this only after Phases 1–4, or load what exists and declare in `meta.assumedContext` what you had to assume.

## 5.1 Peer benchmarking

- Select **8–10 genuine comparables**, mixing global sector leaders with regional peers that share the jurisdiction, ownership model or regulatory regime. Justify each inclusion in one line; a peer set chosen to flatter is worthless.
- Tabulate: EV/EBITDA, P/E, P/B, asset-base multiple (EV/RAB, EV/IC or P/NAV), Net debt/EBITDA, ROE, dividend yield, and 3-year revenue and EBITDA CAGR.
- Compute the median and the company's position against it.
- **Defend the discount or premium analytically.** Not "it trades cheap" — decompose the gap into what is explained by lower ROE, higher leverage, worse governance, jurisdiction risk or slower growth, and what is left unexplained. The unexplained residual is the opportunity, and it is usually much smaller than the headline gap.

## 5.2 Three scenarios

Build **bear / base / bull** as coherent states of the world, each internally consistent across all four prior phases. Each scenario needs an explicit trigger set, not just different numbers.

- **Bear** — input-cost shock, price increases frozen or reversed, the Phase 2 bottleneck binds, the Phase 3 demand slips into later years or evaporates.
- **Base** — normalised input prices, price mechanism works with its usual lag, utilisation holds, demand ramps on the announced schedule less a realistic slippage factor.
- **Bull** — the favourable mix shift lands, reform lowers procurement cost, premium commercial structures are approved, and governance reform forces capital return.

Assign each a probability. They must sum to 1. Justify the weights from evidence, not symmetry — 25/50/25 should be earned, not assumed.

For each scenario produce **five forward years of free cash flow**, plus the WACC and terminal growth rate you consider appropriate *for that state of the world* — a bear case with an unchanged WACC is not a stress test.

## 5.3 Triangulated valuation

Run every method the sector profile marks as applicable. Supply the inputs to `model`; the workspace computes and displays the outputs, so do not pre-compute them.

1. **DCF** — five explicit years plus a Gordon terminal value. State WACC and terminal growth per scenario and defend both. Terminal growth above long-run nominal GDP is not defensible.
2. **Asset-base multiple** — forward asset base × a normalised multiple. The multiple is the market's verdict on whether the allowed return exceeds the cost of capital; anchor it to the ROIC−WACC spread from Phase 4, not to a peer average.
3. **P/B vs normalised ROE** — justified P/B = (ROE − g) / (COE − g). Present the matrix across the plausible ROE and COE ranges; it is usually the most honest single view of a book-value business.
4. **SOTP** — separate businesses with genuinely different economics: regulated network from merchant generation, each operating subsidiary, minority stakes. State the method and multiple per segment and the stake held.

Triangulate: state which method you weight most and why, and give a probability-weighted fair value.

## 5.4 The investment committee memo

Conclude decisively. An IC memo that hedges is a memo that wasted the committee's time.

- **Rating:** `STRONG BUY` | `TACTICAL BUY` | `HOLD / NEUTRAL` | `AVOID`
- **Fair value today** — bear / base / bull, in the local line and any ADR line, with the FX rate used.
- **3-year target price and expected IRR** — bear / base / bull, including dividends, as a CAGR.
- **Why the market is mispricing this — three non-consensus points.** Each must be genuinely non-consensus: state what the market believes, what you believe, and the specific evidence from Phases 1–4 that separates the two. If a point would appear in any sell-side note, it is not one of your three.
- **What the consensus is correctly terrified of — three structural risks.** Steel-man the bear case. If you cannot state the bear case better than a bear would, you do not understand the asset.
- **Catalyst calendar, next 12–36 months** — dated, ranked by impact (`High`/`Medium`/`Low`) and probability. Distinguish catalysts that re-rate the multiple from those that change the cash flows.
- **Trigger-to-sell conditions** — measurable, falsifiable thresholds that invalidate the thesis. "Deteriorating fundamentals" is not a trigger. "Allowed ROE cut below X%", "the interconnection queue slips past 20XX", "net debt/EBITDA exceeds Y for two consecutive quarters" are triggers.

## Required output

Full peer table, scenario assumption table, all valuation outputs, and the complete memo. Write the memo's structured conclusions into the `memo` block (`rating`, `weighting`, `nonConsensus`, `fears`, `sellTriggers`) and mark the subject company's own row in `model.peers` with `"self": true`. Populate `model` fully — `fcf`, `wacc`, `terminalGrowth`, `assetBase`, `book`, `sotp`, `peers`, `targets`, `probabilities` — so the workspace reproduces every number and the user can flex any assumption.

**Do not state a rating that the arithmetic does not support.** If the probability-weighted fair value is close to the current price, the answer is HOLD, and the honest memo says so.
