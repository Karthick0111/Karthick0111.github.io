# karthick0111.github.io

Personal portfolio — data, experimentation, and causal inference.

Single-file site: `index.html`. No build step, no framework, no dependencies.
Everything (styles, scripts, both canvas simulations, both SVG charts) is inline.

## What's in it

- **Live Thompson Sampling simulation** — three arms with hidden CTRs, Beta posteriors
  updating in real time via a Marsaglia-Tsang gamma sampler, tracking cumulative regret.
- **Receipts section** — the Qini curve and calibration curve from
  [`churn-retention-copilot`](https://github.com/Karthick0111/churn-retention-copilot),
  redrawn as animated SVG.
- **Light / dark themes** — toggle in the nav, preference persisted.
- Interactive particle network, filterable project grid, animated timeline.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages, `main` branch, root folder. No configuration needed.
