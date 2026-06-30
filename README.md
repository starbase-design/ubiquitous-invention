# Don Dali — Notes

A single-page, self-contained web experience that collects a short set of
discovery questions from the artist **Don Dali** ahead of a growth/partnership
collaboration. Answers autosave to the browser and can be exported — no backend,
no account, nothing to install.

## Where it lives

- Source: [`site/index.html`](site/index.html) — one self-contained file (HTML +
  CSS + JS inline, no external runtime dependencies).
- Hosting: published to GitHub Pages from `site/` via
  [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml).

## Design

Built to the in-house design system — "analytics console on parchment":
near-monochrome on a warm mist canvas, white cards with elevation from contrast
(not heavy shadow), a single Signal Orange spark used only for progress and
focus, Carbon pill buttons. Space Grotesk for geometric labels, Inter for body.

## Custom domain

To serve from a custom domain, add a `CNAME` file inside `site/` containing the
domain (e.g. `dondali.link`) and point a DNS `CNAME` record at
`starbase-design.github.io`.
