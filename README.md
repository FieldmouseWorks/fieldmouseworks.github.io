# fieldmouseworks.github.io

Organization landing page for [Fieldmouse Works](https://github.com/FieldmouseWorks).

Static HTML + CSS, no build step. GitHub Pages serves the repo root.

- `index.html` / `style.css` — the page
- `assets/` — mark, favicons, Open Graph image (from the logo kit)
- `.nojekyll` — tells Pages not to run Jekyll

## Deploy

Push to `main` in the `FieldmouseWorks/fieldmouseworks.github.io` repository and
enable Pages (Settings → Pages → Deploy from branch → `main` / root).

## Custom domain

When `fieldmouseworks.com` is registered, add a `CNAME` file containing the
domain, point DNS at GitHub Pages, and update the `og:image` URL in `index.html`.
