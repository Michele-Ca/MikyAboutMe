# MikyAboutMe

Static "About Me" site for the Vibe Coding course. No build, tests, package manager, or dev server.

## Structure
- Site files live in `docs/`: `index.html`, `projects.html`, `style.css`.
- Shared top nav markup is duplicated in every page; keep them in sync when adding pages.
- Nav links to `about.html`, which does not exist yet — create it (and add its nav entry) if an About page is needed.

## Styling
- CSS uses British spelling (`colour-*` variables) and CSS custom properties defined in `:root` of `style.css`.
- Shared stylesheet is `docs/style.css`, linked relatively as `style.css`.
- Class names: BEM, lowercase with hyphens (e.g. `project-card__title`).
- No hex colours outside `:root`; always use `var(--colour-*)`.
- 2-space indentation. Every CSS block starts with a section comment, e.g. `/* Skills */`.

## Do not
- Do not use inline styles or `<style>` tags.
- Do not add JavaScript, libraries or external fonts.
- Do not invent or rewrite text content (bio, skills, links). Use `[TODO: ...]` placeholders and ask me.
- Do not delete or rename files without asking.

## When you finish a change
End your reply with a short list headed "Files changed".

## Preview
- Open `docs/index.html` directly in a browser (no dev server).
