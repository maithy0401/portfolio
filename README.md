# Portfolio 2026

Portfolio of Vũ Mai Thy, UI/UX Design Lead and Product Owner in Ho Chi Minh City.

Live: https://maithy0401.github.io/portfolio/

## What's in this repo

- `index.html`: the whole site in one file. The home page and the four case studies live here; the case studies open at `#lotte-flex-design`, `#lotte-flex-onboarding`, `#web3-wellbeing-mvp` and `#prime-labo-team`.
- `assets/`: certificate images and the favicon.
- `.nojekyll`: tells GitHub Pages to serve the files as they are.

## Editing

Edit `index.html` and push to `main`. GitHub Pages republishes the site within a minute or two.

To add an image to an empty slot (a company logo, a case study cover or screenshot):

1. Put the file in `assets/`.
2. In `index.html`, find the `<script type="application/json" id="vmt-state">` block near the end and add an entry under `slots`: `"<slot name>": {"id": "<file name>", "cap": ""}`. Slot names are the `data-slot` attributes in the page, for example `logo-lotte` or `flex-data-cover`.

The upload buttons and Save bar only appear in the Claude artifact version of this page, so here images are added as files.

Icons: Lucide (ISC License). Illustrations: Humation (MIT License).
