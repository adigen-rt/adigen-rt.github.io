# Project page: Are Good Generators Good Decision-Makers?

Static project page for [arXiv:2606.07399](https://arxiv.org/abs/2606.07399). No build step.

## Deploy on GitHub Pages
1. Create a repo (e.g. `adigen-po.github.io` under a new org, or `adigen-po` under your account).
2. Push this folder to `main`.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.

## Local preview
    python3 -m http.server 8000   # then open http://localhost:8000

## Contents
- `index.html`: the whole page (CSS inline, MathJax from cdnjs).
- `static/img/`: paper figures rasterized from the arXiv v3 source PDFs (200 dpi).
- `static/scenes/`: PhyWorld rollout clips re-cut from WorldModeling/FIGS_0929 GIFs (text removed; labels are in HTML).
- `static/cells/`: RxRx19a Cell Painting composites (VERO-1, site 1, central crop).

TODO: add the code link (search for "TODO" in index.html) and real author homepages.
