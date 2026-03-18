# Elisa Bergamotti — Personal CV Site

A single-page personal CV website built with pure HTML, CSS and JavaScript. No frameworks, no build step — just open `index.html`.

## Deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `elisabergamotti.github.io` for a user site, or any name for a project site)
2. Upload all files from this folder to the repository
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder
6. Click **Save**
7. Your site will be live at `https://<username>.github.io/<repo-name>/` within a few minutes

### Custom domain (optional)

To use a custom domain like `elisabergamotti.com`:

1. Add a `CNAME` file to the repo containing your domain name
2. Configure your domain's DNS to point to GitHub Pages (see [GitHub docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-github-pages))

## Files

- `index.html` — The complete single-page CV site (self-contained, no external dependencies except Google Fonts)
- `README.md` — This file

## Tech

- Pure HTML5 / CSS3 / Vanilla JS
- Google Fonts (Open Sans + Playfair Display)
- Scroll reveal animations via IntersectionObserver
- Responsive design (mobile-friendly)
- Profile photo embedded as base64 (no external image files needed)
