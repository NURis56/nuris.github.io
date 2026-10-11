# Nurislam — personal site

One-page portfolio for program applications. Plain HTML / CSS / JS — no frameworks, no build step.

## Run locally

Open `index.html` in a browser, or serve the folder (needed if you later add images):

```
npx serve .
```

## Deploy on GitHub Pages

1. Create a repository (e.g. `username.github.io` or any name) and push these files to the `main` branch root.
2. Repository → Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. Your site is live at `https://<username>.github.io/<repo>/`.

## Edit

All text lives in `index.html`. Search for `[` — every bracket is a placeholder to fill.
Search for `EDIT:` to find the spots that need your judgement (positioning line, interests, project links).

Design tokens (colors, fonts, spacing) are the `:root` block at the top of `style.css`.

## Files

- `index.html` — all content, semantic sections
- `style.css` — design tokens, 12-column grid, light/dark via `prefers-color-scheme`
- `script.js` — reveal-on-scroll + footer year (site works without it)
- `favicon.svg` — minimal "N." mark
