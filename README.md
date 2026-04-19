# Super Intel Center

AIRudder Brazil Sales Team · AI Sales Intelligence Platform

Powered by Engineer Jose Da Costa — All Rights Reserved — 2026

## Run locally

```bash
npm start              # serves on http://localhost:3000
# or
python3 -m http.server 3000
```

Open `http://localhost:3000`.

## Deploy

This is a zero-build static SPA. Pick any host:

### GitHub Pages (automatic)
A workflow at `.github/workflows/deploy.yml` publishes `main` to GitHub Pages on every push.
Enable Pages once: **Repo → Settings → Pages → Build and deployment → Source: GitHub Actions.**

### Vercel
```bash
vercel login
vercel --prod
```
`vercel.json` ships SPA rewrites + security headers.

### Netlify
```bash
netlify deploy --prod
```
`netlify.toml` ships SPA redirects + security headers.

### Cloudflare Pages / static hosts
Use the included `_headers` file. Set the publish directory to repo root.

## Files

- `index.html` — single-page application (bundled)
- `404.html` — SPA fallback (mirrors index.html for client-side routing)
- `vercel.json` — Vercel rewrites + security headers
- `netlify.toml` — Netlify redirects + security headers
- `_headers` — static-host header fallback (Netlify/CF Pages)
- `.github/workflows/deploy.yml` — GitHub Pages CI
- `package.json` — local dev server scripts

## Latest release

- Smart Cadence Engine (templates + timeline + analytics)
- Weekly Action Board (7-day kanban, .ics export, keyboard shortcuts)
- Pain Explorer (intensity map, ROI calculator with best/base/worst scenarios)
- Decisor Intelligence (DISC profiling, playbooks, response probability)
- Full i18n: PT-BR, EN, ZH-CN
