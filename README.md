# Qmaz Solutions — dashboard template

A static admin-dashboard starter: sidebar, top bar, four KPI tiles, revenue chart,
activity feed and a projects table. No build step, no JavaScript.

## Files
- `index.html` — the page. Search for `[PLACEHOLDERS]` and replace them with real content.
- `css/style.css` — keep it in a `css/` folder next to `index.html`.

## Customising
- **Colors / fonts:** all are tokens at the top of `css/style.css` (`--accent`, `--side`, `--bg`, `--font-head` …).
  Change `--accent` to rebrand the sidebar highlight, buttons and chart. The logo square in `index.html`
  uses the same color (`fill="#0F766E"`).
- **Chart:** each bar is `<i style="--h:120px">`; change the number to change its height.
- **Sample data:** all numbers, names and dates are placeholders.

## Publish with GitHub Pages
Upload `index.html` and the `css` folder to a public repository, then
Settings > Pages > Deploy from a branch > main > / (root).
