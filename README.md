# fieldmouseworks.github.io

Source for [fieldmouseworks.com](https://fieldmouseworks.com), the
[Fieldmouse Works](https://github.com/FieldmouseWorks) landing page.

Static HTML + CSS, no build step.

- `index.html` / `style.css` — the page
- `assets/` — mark, favicons, Open Graph image (from the logo kit)

## Deploy

Push to `main`. The Fieldmouse Works host checks this repository every five
minutes and publishes the newest `main` as fieldmouseworks.com, served by nginx.
Everything in the repository except this README and dotfiles is public on the
site.

GitHub Pages cannot be turned off for an `<org>.github.io` repository, so
fieldmouseworks.github.io still serves the same files. The page's canonical link
names fieldmouseworks.com.
