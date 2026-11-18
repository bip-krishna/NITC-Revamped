# NIT Calicut · Website Revamp

A static redesign concept for the NIT Calicut homepage. The prototype pairs a utility bar and main navigation with campus photography and an events section.

[Quick start](#quick-start) · [Design rationale](Readme) · [Pages workflow](.github/workflows/static.yml)

## Quick start

Run this from the repository root with Python 3 installed.

```bash
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000).

## Project layout

- [`index.html`](index.html) contains the navigation, event highlights, and campus sections.
- [`styles.css`](styles.css) defines the layout and responsive styling.
- [`static.yml`](.github/workflows/static.yml) deploys the site to GitHub Pages on pushes to `main`.
