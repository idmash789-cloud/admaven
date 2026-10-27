# admaven — Confirmation Page

A single-file confirmation page (`index.html`), no build step. Fully in English.

## How it works

A centered pop-up shows a "Secure Connection" status, with an animated 5-second countdown (number + shrinking progress bar).

- **Next** → https://www.fb.com
- **Close** (and the `×` button in the pop-up corner) → https://www.home.com
- **No choice within 5 seconds** → automatically redirected to https://www.save.com

Clicking Next or Close cancels the countdown timer, so the chosen link always wins. The buttons are plain links (`<a href>`), so they still work if JavaScript is disabled — only the auto-redirect needs JavaScript.

## Run / deploy

- Locally: open `index.html` in a browser.
- GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root, then open this repo's Pages URL.
- Cloudflare Pages: connect this repo, empty build command, root output directory.

Note: this is a generic, self-made confirmation pop-up, not an official Cloudflare page.
