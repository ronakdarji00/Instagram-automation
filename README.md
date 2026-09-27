# 🖥️ Instagram Auto-Reply — Frontend Dashboard

A modern, dark-themed dashboard to control Instagram Comments and Direct Messages (DMs) auto-reply automation. Built with pure HTML5, modern Tailwind CSS, and Vanilla JavaScript with zero npm build step required.

## Key Features

- **📊 Dashboard Overview** — Real-time metrics for comments replied, DMs replied, reels scanned, and token validity.
- **💬 Comments Auto-Reply** — Custom response templates, Quick Template chips, and "Save as Permanent Default".
- **⚡ Older Comments & Deep Scan** — Toggle deep pagination across previous reels and past comment threads.
- **🔁 Force Re-Reply & Cache Reset** — Option to reply to previous comments again and clear cache.
- **📩 Direct Messages (DMs)** — Automated responder for your Instagram inbox with custom messaging and rate limit control.
- **🔍 Live Token Health Verification** — Live status dot and diagnosis banner for Meta token expiration.
- **📝 Activity Feed & Filters** — Filter between All, Comments, and DMs with local persistence.

## How to Run Locally

```bash
python -m http.server 3000
```
Open **`http://localhost:3000`** in your browser.

## Deployment to Vercel

1. Import this repository into Vercel.
2. Framework Preset: **Other**.
3. Output Directory: `./`.
4. Deploy!
5. In the dashboard **Settings**, point the backend URL to your Render deployment.
