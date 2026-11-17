# MikyAboutMe

Static "About Me" site for the Vibe Coding course. No build, tests, package manager, or dev server.

## Structure
- Site files live in `docs/`: `index.html`, `projects.html`, `style.css`.
- Shared top nav markup is duplicated in every page; keep them in sync when adding pages.
- Nav links to `about.html`, which does not exist yet — create it (and add its nav entry) if an About page is needed.

## Styling
- CSS uses British spelling (`colour-*` variables) and CSS custom properties defined in `:root` of `style.css`.
- Shared stylesheet is `docs/style.css`, linked relatively as `style.css`.

## Preview
- Open `docs/index.html` directly in a browser (no dev server).
