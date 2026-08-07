# Trevor Henry Chiboora — Portfolio

Static site served from `/public`. No build step. Deployed to Render via `render.yaml`.

## Local preview
Open `public/index.html` in your browser, or run:

    cd public && python3 -m http.server 8080

## Deploy (Render Blueprint)
Render Dashboard → New → Blueprint → select this repo → Deploy.

## Structure
- `public/index.html` — the entire site (HTML + CSS + JS in one file)
- `public/404.html` — not-found page
- `public/assets/` — resume PDF; add lab screenshots here when ready
