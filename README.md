[![make.fun](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126)
[![make.fun rank](https://make.fun/badge/news-image-20261126/Kiosbensin94/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![make.fun reward](https://make.fun/badge/news-image-20261126/Kiosbensin94/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126)

# The World Today — 26 November 2026

Entry for the [make.fun bounty "Sum up 26 November's world news in one image"](https://make.fun/bounty/news-image-20261126) ($100, 50 places paid).

## The image

A newspaper front page, "THE WORLD TODAY — 26 NOVEMBER 2026", summarising Thursday 26 November 2026's world news:

- **Main headline:** Houthis hit Saudi refinery (Ras Tanura) — Brent crude tops $94
- **NASDAQ down nearly 4%** — AI sell-off deepens
- **US proposes up to 15% tariffs on Taiwan**
- **Pakistan's first astronaut**, Muhammad Zeeshan Ali, docks at China's Tiangong space station
- **Japan–Europe mission reaches Mercury** after an 8-year journey
- In brief: Cairo tanker fire kills 31; Colombia marks 10 years of peace deal; North Korea expels Swiss diplomat

## How it works

`main.ts` (Node 22, standard library only, no network) copies the bundled `entry.png` (1024×1024, under 1 MiB) to `/output/entry.png` and verifies the copy is byte-identical (SHA256 checked). Running it twice writes the same bytes.

## Files

- `main.ts` — the entry program
- `entry.png` — the newspaper front page (1024×1024 PNG)
- `LICENSE` — MIT
