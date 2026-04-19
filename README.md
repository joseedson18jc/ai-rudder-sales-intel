# Super Intel Center

AIRudder Brazil Sales Team · AI Sales Intelligence Platform

Powered by Engineer Jose Da Costa — All Rights Reserved — 2026

## Deploy

Production target: Vercel (static HTML, zero build step).

```bash
cd /Users/joseedsondacosta/Desktop/rudder_deploy
vercel login           # one-time, opens browser
vercel --prod          # deploy to production
```

## Files

- `index.html` — single-page application (bundle)
- `vercel.json` — security headers + cleanUrls config
- `_headers` — static-host fallback (Netlify/CF Pages)

## Latest release

- Smart Cadence Engine (templates + timeline + analytics)
- Weekly Action Board (7-day kanban, .ics export, keyboard shortcuts)
- Pain Explorer (intensity map, ROI calculator with best/base/worst scenarios)
- Decisor Intelligence (DISC profiling, playbooks, response probability)
- Full i18n: PT-BR, EN, ZH-CN
