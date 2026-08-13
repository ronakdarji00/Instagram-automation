# Instagram Auto-Reply — Frontend

A beautiful static dashboard for managing your Instagram auto-reply settings. All data is stored in the browser's `localStorage` — no database required.

## Features

- **Settings panel** — set your reply message, check interval, and max replies per run
- **Activity feed** — shows recent comments and the replies sent
- **Stats dashboard** — media tracked, comments seen, replies sent
- **localStorage only** — when new data arrives, old data is automatically replaced (keeps last 50)
- **No backend needed for UI** — fully static, deploys to Vercel for free

## Deploy to Vercel

1. Push this folder to GitHub: `https://github.com/ronakdarji00/Instagram-automation`
2. Go to https://vercel.com → Import the repo
3. Framework preset: **Other** (static site)
4. Deploy — done!

## Files

- `index.html` — main dashboard page
- `vercel.json` — Vercel deployment config
- `README.md` — this file

## How data flows

```
[Backend Python script] → replies comments → [This dashboard shows activity]
         ↑                                                      ↑
   Instagram Graph API                              localStorage (browser)
```

The backend runs separately (laptop/VPS/Railway) and handles the actual Instagram API calls. This frontend is a control panel for viewing settings and activity.
