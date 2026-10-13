# Mercer's Coffee

Website for **Mercer's Coffee**: espresso bar, matcha and bakery at MM Square, Gulberg 2, Lahore.

A static, single-page site with no build step: plain HTML, CSS and JavaScript.

## Structure

```
index.html            # the whole page (styles + scripts inline)
favicon.svg
robots.txt
.nojekyll             # tells GitHub Pages to serve files as-is
assets/
  images/             # photos (photo-01.jpg … photo-19.jpg)
  fonts/              # Fraunces + Hanken Grotesk (woff2, self-hosted)
  video/              # mercers-film.mp4 (background film)
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, pick **Deploy from a branch**, then branch `main` and folder `/ (root)`.
4. Your site goes live at `https://<username>.github.io/<repo-name>/`.
