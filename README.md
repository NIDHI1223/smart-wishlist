# Wishlist-to-purchase

Two static sites, published at **https://nidhi1223.github.io/smart-wishlist/**

| Path | What it is |
|---|---|
| [`engine/`](engine/) | **Discovery Engine** — read-only interface over the validated research artifacts: insights, the evidence trail behind each, themes, runs, reports, and an Ask box that answers by retrieval only. |
| [`prototype/`](prototype/) | **Smart Wishlist** — a working shopping app on a 60-product catalogue, with a wishlist layer that resurfaces a saved item only when something changed on it or it genuinely matches what is on screen. |

Both pages are single self-contained HTML files: no server, no build step, no dependencies, no
tracking. Open either one from disk and it works.

This repo holds only the published output. It is generated from the research repo — the engine page
by `python3 app/build_static.py`, the prototype by `python3 tools/build_catalog.py --inline`.

Product photography and copy in the prototype belong to Myntra and are shown for design review only.
