# TYDTU

Static site scaffold for GitHub Pages.

## Local Preview

Open `public/index.html` in a browser to preview the site locally.

## Deployment

The site deploys through GitHub Actions. On each push to `main`, the workflow in
`.github/workflows/pages.yml` uploads the contents of `public/` and publishes it
to GitHub Pages.
