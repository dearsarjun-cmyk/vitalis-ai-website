# VITALIS AI website

A standalone, responsive website for the VITALIS AI project. It uses plain HTML, CSS, and JavaScript—no framework or build step is required.

## Preview locally
1. Extract this folder.
2. Open `index.html` in a browser.

For a local development server, from this directory run:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

## Publish it as its own public website
This folder contains the website files; it is not public on the internet until you deploy it and optionally connect a domain you own.
- Upload the files to a static hosting provider such as Cloudflare Pages, Netlify, or GitHub Pages.
- For a custom domain such as `vitalisai.com`, first check whether it is available and register it through a domain registrar. Domain names are not included in this ZIP.

## Notes
- This is a project landing page, not a functioning medical AI application or a claim of validated clinical capability.
- The site uses Google Fonts from a CDN. If offline, it falls back to system fonts.
- Update the project description, status labels, and links as the implementation evolves.
