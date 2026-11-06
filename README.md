# Diep Bao Han Personal Workbench

Static GitHub Pages package for the interactive workbench.

## Publish

Create a public GitHub repository and add `index.html` and `app.js` at the repository root. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. GitHub Pages will publish the site at the repository's Pages URL.

The page uses a Netlify Functions API for shared notes and updates. GitHub Pages serves the frontend only; the existing API endpoint must remain available for shared interactions. If that service is unavailable, the page falls back to browser-local storage.
