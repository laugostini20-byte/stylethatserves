# Style That Serves

Digital shop guide for **Style That Serves: Runway to Benefit the Arts**, hosted by Meg Mundy Style LLC.

- **Date:** Saturday, May 29
- **Doors:** 5:30 PM &middot; **Show:** 7:00 PM
- **Venue:** Memorial Art Gallery &middot; 500 University Ave, Rochester, NY 14607

## What's in this repo

A single static page (`index.html`) listing the runway lineup, vendors, photography team, opening entertainment, and venue info. No build step, no dependencies — pure HTML + inline CSS + a small inline search script.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy to Vercel

This site is a static page. Vercel auto-detects it.

1. Push this repo to GitHub (already wired to `https://github.com/laugostini20-byte/stylethatserves`).
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo.
3. Framework Preset: **Other**. Root Directory: leave default. Build Command: leave empty. Output Directory: leave empty.
4. Click **Deploy**.

Every push to `main` redeploys automatically.

## Editing content

All cards live in `index.html` inside the `<section>` blocks (`#entertainment`, `#brands`, `#vendors`, `#photographers`, `#venue`). To add a card, copy any `<article class="card">…</article>` block and edit the eyebrow, name, description, and button URLs.
