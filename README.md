# Wikidata PubMed referencer

Static website (no backend). It calls the Wikidata API, Wikidata Query Service and NCBI E-utilities directly from the browser; all three allow cross-origin requests.

## Run locally
    cd site && python3 -m http.server 8000   # then open http://localhost:8000

## Deploy on GitHub Pages
1. Push this folder to a GitHub repository (branch `main`).
2. Settings > Pages > Source: **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` publishes `site/` on every push.
