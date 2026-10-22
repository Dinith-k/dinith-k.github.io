# Aplogon apps site

Served by GitHub Pages at https://dinith-k.github.io/ (this repo must stay named `dinith-k.github.io`, publishing the root of `main`).

- `app-ads.txt` — AdMob authorised sellers for every app (one publisher id).
- `<app>/privacy.html`, `<app>/terms.html`, `<app>/icon.png`, `<app>/index.html` — one folder per app.
- `snowsurvival/` (Unity game, iPhone and Android) has `support.html` instead of `terms.html`: the game has no terms.
- `index.html` — the apps list; add a card for each new app.
- `style.css` — shared light/dark styles. `404.html` uses root-absolute paths.

Each app's Play listing uses https://dinith-k.github.io as its website, so AdMob finds `app-ads.txt`.
