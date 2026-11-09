# CrumbleCV

A one-page CV for Muhammad Huzaifa, written as a single static `index.html` (no build step, no dependencies).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy to Vercel

**From the dashboard**

1. Push this repo to GitHub.
2. In Vercel, choose **Add New → Project** and import the repo.
3. Leave **Framework Preset** as `Other`, and leave the build command and output directory empty.
4. Click **Deploy**.

Every push to `main` redeploys automatically.

**From the CLI**

```bash
npm i -g vercel
vercel          # preview deployment
vercel --prod   # production deployment
```

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The CV page (HTML, CSS and JS inline) |
| `favicon.svg` | Cookie favicon |
| `vercel.json` | Clean URLs and security headers |
| `.vercelignore` | Keeps this README out of the deployment |
