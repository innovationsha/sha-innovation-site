# SHA Innovation — Website

The marketing site for **SHA Innovation** (shainnovation.com).
*Your vision. Our solution.*

## Structure
Four self-contained pages — each file has its styling and logo built in,
so it renders correctly on its own. No build step, no dependencies.

```
index.html       Home
services.html    Services
projects.html    Projects (detailed case studies)
contact.html     Contact (form + what happens next)
```

## How it goes live
Connected to Cloudflare Pages. Every push to `main` auto-deploys.
Cloudflare serves clean URLs (services.html -> /services).

## Editing
Open any .html file, change it, then:
```bash
git add -A
git commit -m "Describe your change"
git push
```
Live in ~30 seconds.

Note: the design styles live inside each page. If you want a shared
stylesheet later (edit the look in one place), it works once hosted —
ask and I'll set that version up.

## Cloudflare build settings
- Framework preset: None
- Build command: (empty)
- Build output directory: /
