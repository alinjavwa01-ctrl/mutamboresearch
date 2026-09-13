# Mutambo Research — Zambia Beef Export Infrastructure

Research on what it would take to scale Zambia from its stated **$1 billion**
beef-export target to a **$10 billion** beef export industry — and the herd, rail,
cold-chain, energy, and financing infrastructure that implies.

## The site

A small static site (plain HTML, no build step) served from the repo root — deploy
it on Vercel as a zero-config static project.

| Page | What it is |
|---|---|
| [`index.html`](index.html) | Landing page — the Mutambo Research hub. |
| [`report.html`](report.html) | The $10B research report (charts, corridor schematic, interactive scenario model). |
| [`rail.html`](rail.html) | **Interactive rail & facilities map** — every corridor node sized by current cattle stock, with the abattoir / feedlot / cold / reefer / quarantine / power each needs, scaled to the $1B and $10B targets. |
| [`REPORT.md`](REPORT.md) | The written research brief (numbers, tables, sources). |
| [`site/index.html`](site/index.html) | Artifact-renderer source for the report (body-only; used by the Claude Artifact publish). |

### Deploying

The repo's default branch is the working branch and contains only static HTML at the
root, so Vercel's zero-config static preset serves it directly (`index.html` at `/`,
`cleanUrls` gives `/report` and `/rail`). Connect the repo to the Vercel project and
deploy the default branch — no framework, build command, or output directory needed.

### Also published as Claude Artifacts

- Report: https://claude.ai/code/artifact/f59c8f4e-a8a4-4da4-b85a-360c115a5db8
- Rail & facilities map: *(see session — published alongside the site)*

## Headline finding

A **$1B** beef industry is a commercial upgrade of what Zambia already has. A
**$10B** industry is a national transformation over 25–30 years: a national herd
approaching **~46 million cattle** (≈9× today's 5.1M), export earnings approaching
Australia's, and a cold-chain-grade logistics network laid over rails built for
copper. The cattle heartland (Southern Province) already sits on the existing rail
spine; the two ocean gates — **TAZARA** (east → Dar es Salaam → Gulf/Asia) and the
**Lobito Corridor** (west → Atlantic → EU/Americas) — are being rebuilt for
minerals and can carry reefer beef on the same trains.

## Scope & disclaimer

Independent research and scenario analysis, not a government plan or investment
advice. The $10B figure is an analytical anchor. Figures marked *illustrative*
(the scenario model, fleet counts, energy load, and capital stack) are
order-of-magnitude estimates built on the cited public data. Prepared September 2026.
