# Forward-Upside Screener — the Time-Staged (Catalyst-Lifecycle) Companion

### Stop buying catalysts that already happened. Rank candidates by *where they sit in the catalyst lifecycle* and only hunt the ones whose move is still ahead.

**Version 1.0 · Compiled 2026-05-30 · Companion to [`trump-catalyst-stock-screener.md`](./trump-catalyst-stock-screener.md)**

---

> ## ⚠️ Not financial advice
> Educational framework only, built on **public** information (policy actions, filings, price
> data — never material non-public info). Forward upside is inherently uncertain; political and
> AI catalysts can reverse fast. Analyst targets are moving consensus aggregates. Tickers are
> **illustrative**, not recommendations. All numbers are approximate and must be re-verified
> live. Do your own research; consult a licensed professional.

---

## 1. Why this report exists

The core screener ([`trump-catalyst-stock-screener.md`](./trump-catalyst-stock-screener.md))
answers *"is this a Trump-catalyst breakout?"* — but it scored **realized** catalysts and
**realized** price strength highly. Run blindly, it surfaces names that have **already run**:

| Name | 2026 YTD (approx.) | Status |
|---|---:|---|
| Dell (DELL) | ~+234% | **Late** — parabolic, catalyst realized |
| Intel (INTC) | ~+190% | **Late** — govt-stake re-rating done, weak earnings |
| Texas Instruments (TXN) | ~+51% | **Late-ish** — breakout largely priced, PEG >2 |

Buying these *now* is buying the catalyst **after** it hit the tape. **Future upside lives
earlier in the lifecycle.** This report adds the missing **TIME axis**: classify every candidate
by its **catalyst stage**, and only take new positions in stages where the move is *still ahead*.

---

## 2. The Catalyst Lifecycle model (the time axis)

Every Trump-catalyst trade moves through four stages. Future upside is highest at **S0–S1** and
collapses by **S3**.

| Stage | Name | What it looks like | Numbers vs price | Entry posture |
|---|---|---|---|---|
| **S0** | **Latent / Pre-catalyst** | Theme exists, but no company-specific catalyst yet. Stock basing. Insiders may be *quietly* accumulating (your disclosure table is an S0 tell). | Cheap-to-fair; estimates flat | **Accumulate** on base breakout — max upside, max uncertainty |
| **S1** | **Ignition** | Catalyst **announced** (deal / EO / contract / backlog) but **not yet in earnings**. Backlog/RPO building. | **Estimates lag the news** — the gap *is* the opportunity | **Primary buy zone** — catalyst confirmed, P&L hasn't caught up |
| **S2** | **Recognition** | Catalyst now **flowing into results**; beats, upgrades, steady uptrend, not parabolic. | Estimates rising to meet price | **Ownable**, trail stops; chase less |
| **S3** | **Euphoria / Extended** | Catalyst **fully realized**, parabolic (+150–250%), crowded, stretched valuation. | Price ahead of even raised estimates | **Avoid new entries** / take profits — this is DELL/INTC today |

**The single most valuable signal is S1**: a *confirmed* catalyst whose revenue is **contracted
but not yet recognized** (e.g., remaining performance obligations / backlog). The market can see
the catalyst but the income statement can't — yet.

---

## 3. Forward-upside scoring (what changes vs the core model)

Keep the core `√(BP × TC)` engine, but replace the soft "Timing multiplier" with a **hard Stage
gate**, and add explicit **remaining-upside** measures:

```
Stage gate:   S3  → new-entry score capped (treat as exit/avoid)
              S2  → ×1.00
              S1  → ×1.15   (catalyst ahead — preferred)
              S0  → ×1.10   (early, higher uncertainty)

Remaining-Upside (RU, 0–100), three inputs:
  • Analyst 12-mo target upside %      (more = better)
  • Valuation vs growth (PEG / EV-Sales vs growth; cheaper = better)
  • "Backlog-not-yet-recognized" (RPO/order-book growth as % of revenue)

Forward score = √(BP × TC) × StageGate × (0.5 + RU/200)
```

The RU term *rewards cheapness-relative-to-growth and unrecognized backlog* — exactly what the
late-stage runners lack.

---

## 4. Stage map of the current universe (late vs early)

| Stage | Tickers | Read |
|---|---|---|
| **S3 — Avoid new entries** | DELL, INTC, TXN, AVGO*, PLTR** | Catalyst realized / valuation stretched. *AVGO = pricey (PEG ~1.6, modest remaining upside). **PLTR = forward P/E ~180–220x, PEG >5, targets *below* price — highest downside risk. |
| **S2 — Ownable, less upside** | NVDA, CEG | Quality leaders, catalyst partly priced; 10–19% target upside. |
| **S1 — Primary buy zone (catalyst ahead)** | **ORCL, VRT, VST** | Confirmed catalyst, revenue still ramping into the P&L. |
| **Broken / special** | NOW, ADBE, WDAY | "SaaSpocalypse" downtrends; no current catalyst — not forward-upside candidates despite being in the disclosure table. |

---

## 5. Ranked forward-upside watchlist (the *fresh* ones)

Ranked by remaining upside × catalyst-still-ahead × growth. **Illustrative, not advice; numbers
approximate as of late May 2026.**

| # | Ticker | Stage | Fwd valuation | ~12-mo target upside | Catalyst *still ahead* | Why it ranks here |
|---|---|---|---|---:|---|---|
| **1** | **ORCL** Oracle | **S1** | P/E ~28–32x, PEG ~1.3–1.6 | **~20–30%** | **~$455B RPO** (Stargate/OCI) ramping FY26–28 — contracted, not yet recognized | **Best risk/reward.** Confirmed backlog, not hope; cheapest large-cap vs its accelerating cloud growth |
| **2** | **VST** Vistra | **S1–S2** | P/E ~20–25x, PEG ~1–1.5 | **~15–25%** | Data-center power PPAs + capacity-price tailwinds still building | **Cheapest power-for-AI** play; more leverage/upside than CEG |
| **3** | **VRT** Vertiv | **S1–S2** | P/E ~35–45x, PEG ~1.3–1.7 | **~15–25%** | Multi-year data-center power/cooling **backlog (book-to-bill >1)** | Purest **pick-and-shovel** to the Stargate buildout; high beta |
| **4** | **NVDA** Nvidia | **S2** | P/E ~38–40x, PEG ~1.2–1.4 | ~15–19% | **China H200 re-opening** is incremental — *excluded* from current guidance | Best fundamental quality; size caps the % upside |
| **5** | **CEG** Constellation | **S2** | P/E ~28–32x, PEG ~1.5–2 | ~10–20% | Nuclear/AI-power PPAs, nuclear EOs | Strong theme but more priced-in after a big 2024–25 run |

**Bottom line for "future upside, not what already ran":** **ORCL** is the standout S1 name — the
catalyst (Stargate/OCI backlog) is *contracted and visible* but *not yet in earnings*, with
~20–30% consensus upside at a reasonable PEG. **VST** and **VRT** are the higher-beta
"buildout" follow-ons with similar upside. **NVDA/CEG** are quality but further along (S2). The
disclosure-table darlings that already tripled (**DELL/INTC**) and the priced-for-perfection
**PLTR** are explicitly **out** for *new* entries.

---

## 6. How to catch S0 (pre-catalyst) names early — the real edge

The biggest future upside is buying **before** S1. Leading indicators to watch:

1. **Disclosed insider/official accumulation *ahead of* a catalyst** (your DPA overlay) — quiet
   buying in a name with *no* announced deal yet.
2. **Backlog/RPO growth outrunning revenue** — the income statement hasn't caught up.
3. **A base/consolidation** (not extended) in a confirmed Trump theme (§4 of the core report).
4. **An *upcoming* policy event** — a pending EO, tariff ruling, budget vote, or federal RFP the
   company is positioned to win.
5. **Second-derivative suppliers** to a confirmed S2/S3 winner that haven't re-rated yet
   (power, cooling, networking, packaging, EDA-ex-China).

A name hitting 3+ of these in a **base** = an S0 candidate with the most runway.

---

## 7. Risks & caveats (in addition to the core report's §9)

- **"Catalyst ahead" is a forecast.** Backlog can slip, PPAs can renegotiate, EOs can stall.
  RPO is contracted but **execution/margin** (e.g., Oracle's Stargate capex) is debated.
- **S1 ≠ immediate move.** The gap between announcement and earnings can take quarters; you may
  sit through dead time. Size for it.
- **Cheap can stay cheap; high-beta cuts both ways** (VST/VRT swing hard if AI capex wobbles).
- **Analyst targets move** and are often anchored to price — treat upside % as directional only.
- **Don't anti-chase into broken names** (NOW/ADBE/WDAY) just because they're "down a lot" —
  a falling knife without a catalyst is not an S0 setup.
- Same ethics/legal rules as the core report: **public data only, no MNPI, not advice.**

---

## 8. Sources

- Oracle RPO / Stargate backlog: https://www.cnbc.com/2025/09/10/oracle-stock-rpo-cloud-stargate.html
- Oracle forecast/targets: https://www.tipranks.com/stocks/orcl/forecast
- Nvidia China H200 / forecast: https://www.tipranks.com/stocks/nvda/forecast · https://builtin.com/articles/trump-lifts-ai-chip-ban-china-nvidia
- Broadcom valuation: https://www.tipranks.com/stocks/avgo/forecast
- Texas Instruments breakout: https://247wallst.com/investing/2026/04/29/texas-instruments-breakout-was-5-years-in-the-making-does-it-have-legs/
- Vertiv forecast: https://www.tipranks.com/stocks/vrt/forecast
- Constellation forecast: https://www.tipranks.com/stocks/ceg/forecast
- Vistra forecast: https://www.tipranks.com/stocks/vst/forecast
- Palantir valuation: https://www.tipranks.com/stocks/pltr/forecast

---

*Companion to the Trump-Catalyst Breakout Screener. Educational framework — **not financial
advice.** All figures approximate as of 2026-05-30 and must be re-verified live.*
