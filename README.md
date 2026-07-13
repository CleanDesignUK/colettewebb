# Colette Webb Static Website

This is the plain static HTML/CSS version of the original Django project.

## Files

- `index.html` – home page
- `services.html` – services page
- `about.html` – about page
- `contact.html` – contact page
- `assets/css/` – shared and page-specific styles
- `assets/images/` – local badge images
- `assets/documents/` – downloadable certificates
- `robots.txt` and `sitemap.xml` – SEO files

## Run locally

Open `index.html` directly in a browser, or run a simple local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Hosting

Upload the entire folder to any static website host, including Hostinger, Netlify, Cloudflare Pages, GitHub Pages, or cPanel public_html.

The contact form remains connected to Web3Forms and does not require Django or a database.
