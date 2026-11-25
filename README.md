# SECUTE workshop website

This is a static website published with GitHub Pages. Each edition has its own
pages and assets in `editions/<year>/`. The root `index.html` redirects visitors
to the current edition, SECUTE 2027.

The 2027 pages contain the announced ICST workshop details. The workshop date,
program and accepted papers are still to be announced.

## Adding an edition

1. Copy the previous edition into a new `editions/<year>/` directory and update
   its content and assets.
2. Update the Editions menu on every edition's pages.
3. Change both the refresh target and the JavaScript and fallback links in the
   root `index.html` to point to the new edition.

The old root-level 2026 pages and the original `2024/` page URLs redirect to
their archived equivalents. The original asset directories remain available
for existing direct links; edit the assets in the relevant edition instead.
Relative links make the site usable at the root of a domain or under a GitHub
Pages project path.
