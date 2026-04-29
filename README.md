# portfolio

A static personal portfolio site (single-page HTML + images).

## Local preview

Option A (quickest): open `index.html` in your browser.

Option B (simple local server):

```zsh
python3 -m http.server 8000
```

Then visit:

- http://localhost:8000

## Project structure

- `index.html`: main page
- `favicon.svg`: site icon
- `images/`: image assets

## GitHub Pages (Actions)

This repo includes a GitHub Pages workflow at:

- `.github/workflows/pages.yml`

Make sure GitHub Pages is set to **GitHub Actions** in repo settings.
After pushing to `main`, the workflow deploys the site.
