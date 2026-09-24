# Case Study Generator

Upload the module-activation sheet and the service-ticket export (.xlsx) and download a
finished case study HTML file. Runs fully in the browser; no server code and no build step.

## Files

- `index.html` the whole tool (UI + generator + case study template)
- `xlsx.full.min.js` SheetJS, bundled locally so the site does not depend on a CDN
- `vercel.json` clean URLs and two basic security headers

## Deploy on Vercel

Option A: GitHub

1. Push this folder to a GitHub repo.
2. Vercel dashboard > Add New > Project > import the repo.
3. Framework Preset: Other. Build Command: empty. Output Directory: empty (root). Deploy.

Option B: CLI
npm i -g vercel
cd case-study-generator
vercel --prod

## Run locally

    npx serve .
