# Four Laws

A field guide to the machinery of the universe — Newton's laws, E = mc², the
Schrödinger equation, and resonance, each told at four levels of complexity
(plain sight → high school → university → frontier), grounded in 29 verified
academic sources.

- **Explainer figures** under each law, with symbol-by-symbol equation keys.
- **Nine "all four at once" ensembles** — the Sun, GPS, the LHC, a power plant,
  a smartphone, a thunderstorm, a gasoline engine, an LED video wall, and a
  broadcast cable run — each with an interactive canvas simulation and
  fact-checked "go deeper" panels.
- **96-term glossary** (`glossary.html`) with in-page definition popovers on
  the main page; the Back button returns to your exact reading position.

Buildless: two self-contained HTML files, no dependencies, no build step.

## Run locally

```bash
python3 -m http.server 8611 --directory .
```

## Deploy

Static site on Render — `render.yaml` is a ready Blueprint: Dashboard → New →
Blueprint → select this repo. Auto-deploys on push.

## QA hooks

`?lvl=N` presets all reading levels · `?demo=1` pre-poses every simulation ·
`?open=1` expands all go-deeper panels · `?figs=0` collapses the figures ·
`?shotid=<section-id>` frames a section for headless capture.
