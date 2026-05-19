# AGENTS.md — Maikismo.com

## Project Type
Static HTML website. No build system, no package manager, no framework compilation.

## Entry Point
- `index.html` is the only page.
- Open directly in a browser or serve with any static file server.

## Assets
- `maik.jpeg` must remain in the repo root; `index.html` references it with a relative path.

## External Dependencies (CDN)
- Tailwind CSS: loaded from `https://cdn.tailwindcss.com`
- Google Fonts (Cinzel, Comic Neue): loaded from `https://fonts.googleapis.com`
- No local `node_modules`, `package.json`, or lockfiles exist. Do not run `npm install`.

## Development / Preview
- **Direct open**: Open `index.html` in a browser.
- **Static server** (optional): `python -m http.server` or `npx serve` from the repo root.

## Testing & Tooling
- No test suite, no linter, no formatter, no typechecker, and no CI configuration.
- Do not add new tooling or build steps unless explicitly requested.

## Language
All content is in Spanish. Maintain Spanish copy when editing.
