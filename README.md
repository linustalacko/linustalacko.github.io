# Personal site

A tiny static personal site — plain HTML and CSS, no build step.

## Edit

- `index.html` — your name, bio, and links
- `style.css` — colors and layout (supports light & dark mode automatically)

## Deploy to GitHub Pages

1. Create a repo on GitHub. For a site at `https://<username>.github.io`, name
   the repo exactly `<username>.github.io`. Any other name publishes to
   `https://<username>.github.io/<repo>/`.

2. Push these files:

   ```bash
   git init
   git add .
   git commit -m "Initial personal site"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages → Build and deployment**, set **Source** to
   *Deploy from a branch*, branch `main`, folder `/ (root)`. Save.

4. Wait a minute, then visit your URL.

## Preview locally

Just open `index.html` in a browser, or run:

```bash
python3 -m http.server
```
