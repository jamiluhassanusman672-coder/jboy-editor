# J BOY EDITOR

**My personal artwork and graphic design website.**

A single-file, no-build portfolio site — dark pixel-inspired theme, fully
responsive, with a click-to-enlarge gallery.

## Live site

https://jamiluhassanusman672-coder.github.io/jboy-editor/

## Features

- Single `index.html` — no frameworks, no build step
- Responsive layout with a working mobile menu
- Filter-free gallery grid with a lightbox preview
- Scroll-in animations (respects `prefers-reduced-motion`)
- Custom pixel logo, SVG favicon and Open Graph tags

## Sections

| Section | What it holds |
|---|---|
| Hero | Name, tagline, CTAs, quick stats |
| Marquee | Scrolling list of services |
| Work | Six project tiles (edit `data-title` / `data-desc`) |
| About | Bio, bullet points, toolkit bars |
| Services | Three service cards |
| Contact | Email button + social links |

## Editing content

1. **Gallery tiles** — each tile is a `<button class="tile">`. Swap the
   `data-key` (gradient class `g1`–`g6`) for a real image by replacing the
   `.thumb` div with `<img src="images/your-file.jpg" alt="..." />`.
2. **Contact email** — search for `hello@jboyeditor.com` (appears twice) and replace.
3. **Social links** — update the `href` values in the `.socials` block.
4. **Stats / toolkit** — edit the numbers directly in the HTML.

## Run locally

Just open `index.html` in a browser. Nothing to install.

## Deploy with GitHub Pages

1. **Settings → Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main` · **Folder:** `/ (root)`
4. **Save** — the site is live in about a minute.

> The entry file **must** be named `index.html` (lowercase). GitHub Pages is
> case-sensitive and will 404 on `Index.html`.

## License

© J BOY EDITOR. All artwork and design rights reserved.

