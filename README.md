# 🕹️ Glam Arcade

A neon retro-arcade machine with four mini-games, built with Claude. No ads, no tracking, works on phones and computers.

## ▶️ Play

**https://dubik.github.io/arcades/** *(after enabling GitHub Pages, see below)*

## Games

- 💄 **Lipstick Hit** — tap to shoot lipsticks into a spinning wheel. 3 rounds, beat the clock, don't clash!
- 💅 **Polish Stack** — drop and stack polish bars. Perfect drops build combos; 3 in a row regrows your bar.
- 🌸 **Perfume Pop** — spritz the rising scent bubbles before time runs out. Gems score triple, combos pay bonus — but don't pop the stinkers!
- 💎 **Gem Crush** — bejeweled-style match-3. Swap gems, chain cascades, and forge flame, lightning and prism gems for explosive combos.

Standalone versions of each game are in [`games/`](games/).

## Hosting with GitHub Pages

Deployment is automated via GitHub Actions ([`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml)). One-time setup:

1. Repo **Settings** → **Pages**
2. Under *Build and deployment*, Source: **GitHub Actions** → done
3. Every push re-deploys automatically; after ~1 minute, open https://dubik.github.io/arcades/

## Tech

Single self-contained HTML file per game — vanilla JS + Canvas, Web Audio chiptunes, CRT scanline effect. No build step, no dependencies.
