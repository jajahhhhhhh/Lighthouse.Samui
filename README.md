# Lighthouse Samui

Landing site for **lighthousekohsamui.com** — property (villas, land, homes) on Koh Samui.

## Structure

- `index.html` — the full single-page site (self-contained: HTML + CSS + a little JS, no build step, no dependencies).

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on **Cloudflare Pages**, connected to this GitHub repo. Any push to `main` triggers a deploy.

- Build command: _(none)_
- Build output directory: `/` (repo root)
- Production branch: `main`

Custom domain: `lighthousekohsamui.com`
