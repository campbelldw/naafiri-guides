# Naafiri Guides — Patch 26.13

Personalized League of Legends guides for **soup minion#NA1**. Phase 1 (2026-07-04): two adversarially-verified deep-research runs (100 + 104 agents) plus live match-history analysis. Phase 2 (2026-07-05): a third verified research run (13 agents — optimal bruiser, full itemization, top/bot lanes) plus in-game practice-tool damage measurements.

| Guide | Role | Pages |
|---|---|---|
| [naafiri-mid-guide.pdf](naafiri-mid-guide.pdf) | **Mid** (main) — personalized: combos & tech, four rune/build setups incl. research-optimal bruiser, full item encyclopedia, **measured** kill thresholds, KP fix, phase flowcharts | 13 |
| [naafiri-top-guide.pdf](naafiri-top-guide.pdf) | **Top** (companion) — S+ at Gold; DFT/HoB pages, kill-lane summoners (no TP), full matchup table, W-first tech | 4 |
| [naafiri-bot-guide.pdf](naafiri-bot-guide.pdf) | **Bot ADC** (companion) — honest niche-pick verdict, duo dynamics, Caitlyn counter; support = don't | 3 |
| [naafiri-jungle-guide.pdf](naafiri-jungle-guide.pdf) | **Jungle** (companion) — Conqueror build, clear mechanics, snowball levers, balance history | 3 |

Every claim is labeled **VERIFIED** (adversarial fact-check), **SINGLE SOURCE**, **REASONING** (derived from Riot Data Dragon 16.13.1 numbers), or **YOUR DATA / MEASURED** (match history + practice-tool tests).

## Rebuilding

```
chromium --headless=new --disable-gpu --no-pdf-header-footer \
  --print-to-pdf=naafiri-mid-guide.pdf src/mid.html
```

HTML sources and all images are in `src/` (images © Riot Games, via the Data Dragon CDN).

## Key sources
LoL Wiki (Naafiri + patch history), Riot patch notes 26.9/26.10/26.11, Riot Data Dragon 16.13.1, lolalytics (Emerald+/Gold/Master+ cuts), op.gg (incl. Master+ and NA leaderboard), Mobalytics, Skill-Capped, r/NaafiriMains (Mar–May 2025 archive via Pullpush), jungler.gg; player stats via op.gg/u.gg; practice-tool measurements 2026-07-05.
