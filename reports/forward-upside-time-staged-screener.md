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
| **S3 — Avoid new entries** | DELL, INTC, TXN, **VRT**\*, PLTR**, AVGO*** | Catalyst realized / parabolic / valuation stretched. \*VRT = **+115% YTD, mean analyst target BELOW current price** (corrected — was wrongly listed as a buy in v1.0). **PLTR = P/S ~50x, consensus target ≈/below price. ***AVGO = near 52-wk high, only ~9–10% target upside. |
| **S2 — Ownable, less upside** | CEG | Quality leader, catalyst partly priced; ~20–33% target upside. |
| **S1 — Primary buy zone (catalyst ahead)** | **ORCL, VST, NVDA** | Confirmed catalyst, revenue still ramping into the P&L; ~40%+ consensus upside. |
| **Broken / special** | NOW, ADBE, WDAY | "SaaSpocalypse" downtrends; no current catalyst — not forward-upside candidates despite being in the disclosure table. |

---

## 5. Ranked forward-upside watchlist (the *fresh* ones)

Ranked by remaining upside × catalyst-still-ahead × growth. **Illustrative, not advice; numbers
approximate as of late May 2026.**

| # | Ticker | Stage | Fwd valuation | ~12-mo target upside | Catalyst *still ahead* | Why it ranks here |
|---|---|---|---|---:|---|---|
| **1** | **ORCL** Oracle | **S1** | **−49% from $345 ATH**; heavy debt + neg FCF (risk) | **~40%** (cons. ~$261; Mizuho $400) | **RPO ~$553B (+325% YoY)** + Stargate; OCI +84% — almost all future revenue not yet recognized | **Top quality.** Largest unrecognized backlog, most beaten-down. Downside risk is the **balance sheet**, not the multiple |
| **2** | **VST** Vistra | **S1** | fwd P/E **~18** for **~77% EPS growth**; **−27% from high (not extended)** | **~40–60%** (cons. ~$225–233) | Meta nuclear PPAs + Cogentrix 5.5GW gas; >30% EPS growth to 2028 not in run-rate | **Best valuation / risk-reward.** Cheap growth + real catalyst ahead |
| **3** | **NVDA** Nvidia | **S1–S2** | **PEG ~0.5** (cheapest mega-cap AI on growth) | **~40%** (cons. ~$300) | **H200 China = $0 in guidance, zero deliveries yet** → pure incremental upside | Most de-risked; sheer size caps the absolute %, quality highest |
| **4** | **CEG** Constellation | **S2** | fwd P/E ~24; ~25% EPS growth '26 | ~20–33% (cons. ~$346) | Calpine accretion + MSFT/Meta nuclear deals still ramping | Solid, but less upside than top 3 |
| **5** | **AVGO** Broadcom | **S2–S3** | near 52-wk high; fwd P/E ~27–39x | **only ~9–10%** (cons. ~$472–482) | XPU customers 3→6+, Anthropic 3GW ramp — **largely priced in** | Strongest AI ramp but **least target headroom** |

**Excluded (fail the "future upside, not already run" test):** **VRT** (+115% YTD parabolic; mean target ~$296 *below* ~$312 price), **TXN** (analog cycle already re-rated, ~0% target upside), **PLTR** (priciest by far, P/S ~50x; consensus ≈/below current price). *Numbers verified late May 2026; aggregator targets move daily — flagged where sources conflicted (PLTR/VRT target dispersion is wide).*

**Bottom line for "future upside, not what already ran":** **ORCL** is the top-quality S1 name —
its catalyst (Stargate/OCI **$553B RPO**) is *contracted and visible* but *not yet in earnings*,
with ~40% consensus upside and the deepest drawdown (−49% from ATH); its risk is the balance
sheet (debt/negative FCF). **VST** is the **best valuation/risk-reward** — fwd P/E ~18 for ~77%
EPS growth, not extended, with the Meta/Cogentrix ramp ahead. **NVDA** is the **most de-risked**
(PEG ~0.5, China H200 revenue at $0 in guidance = pure upside). The disclosure-table darlings
that already tripled (**DELL/INTC**), the parabolic **VRT**, and the priced-for-perfection
**PLTR/AVGO/TXN** are explicitly **out** for *new* entries.

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

## 9. Appendix — Live "Trump shout-out" tracker (as of 2026-05-30)

A real-world application of the S0–S3 model to the *actual* Trump-mention flow of the last
~6 weeks. **Provenance bombshell:** the disclosed-buy table in the core report's §8.1 is
**Trump's own Q1-2026 personal trade disclosure** (OGE filing, ~3,700 trades, $220M–$750M),
released ~May 14–15, 2026. So "follow the disclosed buys" ≈ following Trump's own portfolio plus
his subsequent public praise. The White House states a **trust** manages the account without his
input; ethics watchdogs dispute this.

### 9.1 The repeatable 3-step playbook

> **Step 1 — Buy** (often a dip) → **Step 2 — Publicly praise** (rally / Fox / White House) →
> **Step 3 — Administration delivers a catalyst** (Pentagon contract, export approval, tariff
> exemption, China order, **government equity stake**).

Documented arc: **Intel → Dell → Micron → Nvidia → Boeing** all followed this sequence
([Benzinga](https://www.benzinga.com/markets/prediction-markets/26/05/52809541/donald-trump-shouted-out-intel-then-dell-then-micron-look-at-his-own-stock-filings-to-see-who-may-get-the-next-shoutout)).

### 9.2 Recent shout-out timeline (newest first)

| Date | Name | Event | Stage now |
|---|---|---|---|
| May 27–28 | **DELL** | $9.7B Pentagon software deal (after Feb buy + "go buy a Dell"); +33% May 29 on earnings | **S3** played out |
| May 26 | **MU** Micron | "Micron's great" (May 22) → +35%/5d, first $1T cap. *Real driver: UBS PT $535→$1,625* | **S3** played out |
| **May 21** | **Quantum basket** (RGTI, QBTS, INFQ, IBM, GFS…) | **$2B CHIPS grants for govt equity stakes** in 9 firms; QBTS +33%, RGTI +30% same day | **S0–S1 — earliest, catalyst ahead** |
| May 18 | **INTC** | Trump: "should've asked for more" of the US 10% stake; ~6x run already done | **S3** played out |
| May 15 | **PLTR** | Disclosed Q1 buy; Truth Social praise was back on **April 10** | priced-in |
| May 14 | **BA** Boeing | China 200-jet order announced; reaction **negative** (hoped ~750) | **upside still unrealized** |

### 9.3 Mechanism upgrade: tariffs → government equity stakes

Markets are desensitized to tariffs. The tool that now *moves* stocks is the **government taking
an equity stake** (Intel was the template; the **May 21 quantum basket** is the newest copy).
To hunt the next one, watch **which strategic industries the government might take a stake in next.**

### 9.4 "Who's next" — names Trump disclosed owning but hasn't fully cashed the catalyst on

Cross-referenced with the forward-upside screen (catalyst ahead + not extended):

- 🎲 **Highest beta / earliest:** **RGTI, QBTS, INFQ** (quantum) — deals are *letters of intent*;
  definitive agreements / milestone funding still pending. **Most catalyst-rich, most
  speculative (pre-revenue small caps) — size as a speculative position.**
- 🛡️ **Quality / playbook not finished:** **ORCL** (owned; Stargate $553B RPO ahead; no big solo
  shout-out yet) — top pick. Then **AVGO** (new position), **AMD** (owned, China-chip angle).
- ✈️ **Theme-scaling:** **BA** — China order could scale 200 → ~750 jets (upside unrealized).

### 9.5 🚨 Red lines (do not chase blind)

- **Options front-running:** minutes before the May 22 Micron remark, ≥9 deep-OTM call blocks
  (>$7.3M premium, strikes to $1,400) hit the tape
  ([BigGo](https://finance.biggo.com/news/Gv3EWZ4BmHHDnbgy76Ul)). Chasing *after* the public
  mention can make you exit liquidity for whoever positioned first.
- **Conflict-of-interest / regulatory & headline-reversal risk:** Trump profits from companies
  his administration helps; WaPo/AP/ethics groups are actively scrutinizing
  ([Washington Post](https://www.washingtonpost.com/politics/2026/05/28/dell-inks-97-billion-pentagon-contract-after-trump-acquires-stock-praises-company/)).
- **Mention ≠ cause:** Micron's move was *primarily* the UBS target hike + HBM-sold-out
  fundamentals; the shout-out amplified an existing setup. **Both axes must be real (core
  report §2).** "Trump theme" ≠ "Trump named it" — note **DJT (Trump Media) is down ~77%.**

*Sources: [CNBC Q1 trades](https://www.cnbc.com/2026/05/15/trump-stock-trade-tech-oge.html) ·
[Axios](https://www.axios.com/2026/05/19/trump-stocks-nvidia-boeing) ·
[247 Wall St — Micron](https://247wallst.com/investing/2026/05/26/trump-said-microns-great-on-may-22-the-stock-is-up-20-today/) ·
[CNBC — Dell/DoD](https://www.cnbc.com/2026/05/27/dell-dod-pentagon-software-deal-digital-infrastructure-trump.html).
All figures approximate; this is a fast-moving, headline-driven situation.*

---

*Companion to the Trump-Catalyst Breakout Screener. Educational framework — **not financial
advice.** All figures approximate as of 2026-05-30 and must be re-verified live.*
