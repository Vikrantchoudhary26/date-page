# For Ravleen

A tiny self-contained interactive page. Pure static HTML/CSS/JS — no build step, no dependencies.

## Deploy to Vercel

**Option A — drag & drop (fastest)**
1. Go to https://vercel.com/new
2. Drag this whole folder into the upload area.
3. Done. Vercel serves `index.html` at the root automatically.

**Option B — Vercel CLI**
```bash
npm i -g vercel
cd ravleen
vercel        # preview deploy
vercel --prod # production deploy
```
Accept the defaults when prompted — no framework, no build command, no output directory.

**Option C — Git**
Push this folder to a GitHub repo, then "Import Project" in Vercel. It deploys on every push.

## Local preview
Just open `index.html` in a browser, or run any static server:
```bash
npx serve .
```

## Files
- `index.html` — the entire app
- `vercel.json` — clean URLs + basic security headers (optional, safe to keep)
