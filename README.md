# Rahma Hafiz — Portfolio

A single-page portfolio site (plain HTML/CSS/JS, no build step).

## Deploying on Vercel

1. Push this repo to GitHub (make sure `index.html` and `vercel.json` are at the **root** of the repo).
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo.
3. Framework Preset: choose **"Other"** (this is a static site — no framework, no build command, no output directory needed).
4. Leave *Build Command* and *Output Directory* blank/default and click **Deploy**.

Vercel automatically serves `index.html` at the root, so no further config is needed beyond what's in `vercel.json`.

### Notes
- `.github/workflows/static.yml` deploys this same site to **GitHub Pages** and is unrelated to Vercel — you can safely keep it (for GitHub Pages) or delete it if you only want Vercel.
- If you previously tried to deploy and got a 404, it was because the site's HTML file was named `rahma_hafiz_portfolio_3.html` instead of `index.html`. Vercel (like most static hosts) looks for `index.html` at the root by default — that's now fixed here.
