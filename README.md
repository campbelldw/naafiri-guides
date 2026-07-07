# Naafiri Guides (+ friends) — Patch 26.13

Personalized League of Legends guides for **soup minion#NA1**. Phase 1 (2026-07-04): two adversarially-verified deep-research runs (100 + 104 agents) plus live match-history analysis. Phase 2 (2026-07-05): a third verified research run (13 agents — optimal bruiser, full itemization, top/bot lanes) plus in-game practice-tool damage measurements. Guest guides (2026-07-06+): commissioned for friends, same verification standard.

| Guide | Role | Pages |
|---|---|---|
| [naafiri-mid-guide.pdf](naafiri-mid-guide.pdf) | **Mid** (main) — personalized: combos & tech, four rune/build setups incl. research-optimal bruiser, full item encyclopedia, **measured** kill thresholds, KP fix, phase flowcharts, comp-audit framework (§3b) | 16 |
| [naafiri-top-guide.pdf](naafiri-top-guide.pdf) | **Top** (companion) — S+ at Gold; DFT/HoB pages, kill-lane summoners (no TP), full matchup table, W-first tech, comp adjustments | 5 |
| [naafiri-bot-guide.pdf](naafiri-bot-guide.pdf) | **Bot ADC** (companion) — honest niche-pick verdict, duo dynamics, Caitlyn counter; support = don't | 3 |
| [naafiri-jungle-guide.pdf](naafiri-jungle-guide.pdf) | **Jungle** (companion) — Conqueror build, clear mechanics, snowball levers, balance history | 3 |

## Guest guides

| Guide | For | Pages |
|---|---|---|
| [jarvan-jungle-guide.pdf](jarvan-jungle-guide.pdf) | **Jarvan IV Jungle** for **Jasio#NA1** — kit numbers, combos (insta-EQ, EQ-Flash, jail-break), Conqueror build, Season-2026 clear timers, two-path build chapter w/ item encyclopedia, full anti-invade chapter (*When Your Jungle Isn't Yours*), comp-audit path picker (§4d), Emerald+ matchups | 11 |
| [brand-jungle-guide.pdf](brand-jungle-guide.pdf) | **Brand Jungle** for **send help#2366** — beginner-detailed: Jungle 101 (Smite/pets/2026 timers/objective clock), Blaze monster math incl. the 26.13 nerf, combo table, DFT rune page, Liandry's→Sorcs→Rylai's core w/ first-back ladder & comp audit, first-clear route, gank/objective/invade playbooks, matchup table | 10 |
| [brand-roles-guide.pdf](brand-roles-guide.pdf) | **Brand Roles Companion** for **send help#2366** — support (home role, Zaz'Zak's core), bot APC (his best WR, Barrier tech), mid (W>E>Q flip), role report card + "which role tonight" picker | 3 |

Every claim is labeled **VERIFIED** (adversarial fact-check), **SINGLE SOURCE**, **REASONING** (derived from Riot Data Dragon 16.13.1 numbers), or **YOUR DATA / MEASURED** (match history + practice-tool tests).

## Rebuilding

```
chromium --headless=new --disable-gpu --no-pdf-header-footer \
  --print-to-pdf=naafiri-mid-guide.pdf src/mid.html
```

HTML sources and all images are in `src/` (images © Riot Games, via the Data Dragon CDN).

## Key sources
LoL Wiki (Naafiri + patch history), Riot patch notes 26.9/26.10/26.11, Riot Data Dragon 16.13.1, lolalytics (Emerald+/Gold/Master+ cuts), op.gg (incl. Master+ and NA leaderboard), Mobalytics, Skill-Capped, r/NaafiriMains (Mar–May 2025 archive via Pullpush), jungler.gg; player stats via op.gg/u.gg; practice-tool measurements 2026-07-05.
