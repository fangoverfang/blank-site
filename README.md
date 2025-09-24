
# Blank Site Repo

A super-minimal static site for learning deployments (Cloudflare Pages, Netlify, Vercel, GitHub Pages).

## Files
- `index.html` — intentionally minimal page.
- `robots.txt` — allows crawling and points to `sitemap.xml`.
- `sitemap.xml` — simple sitemap (replace example.com with your domain).
- `404.html` — optional not found page for nicer errors on static hosts.

## Quick start

1. Replace `https://example.com` in `robots.txt` and `sitemap.xml` with your domain.
2. Commit and push to a new GitHub repo.
3. Deploy on Cloudflare Pages (or any static host).

## Commands

```bash
git init
git add .
git commit -m "Initial blank site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```
