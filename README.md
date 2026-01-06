# topoeval-site

This repository hosts the official static website for the **TopoEval** dataset.

## Website

- **Homepage**: `index.html`
- **Dataset download**: `data/TopoEval.zip` (uploaded separately)

The site is intentionally implemented as a **pure static website** (plain HTML/CSS),
with **no backend** and **no build system**, for long-term maintainability and easy
deployment on **Cloudflare Pages**.

## Repository layout

```
/
  index.html
  data/
    TopoEval.zip
```

## Future expansion (not implemented yet)

This repo structure is kept simple so that future additions can be layered in
without refactoring, for example:

- `docs/` (documentation pages)
- `benchmark/` (benchmark results)
- `leaderboard/` (leaderboard pages)