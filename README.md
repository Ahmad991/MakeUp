# MakeUp — Health & Fitness Website

A simple two-page static website with general health and fitness information.
Built with plain HTML and CSS so it's easy to view and edit — no build tools,
frameworks, or installs required.

## Pages

- `index.html` — Home: overview of health & fitness, the four pillars of a
  healthy lifestyle, and why it matters.
- `tips.html` — Fitness & Nutrition Tips: workout ideas, a balanced-plate
  guide, and a daily habit checklist.
- `css/style.css` — shared styling for both pages. Change the colors in the
  `:root` block at the top to re-theme the whole site.

## Viewing the site

Just open `index.html` in any web browser. To preview with a local server
instead (optional):

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Editing

All content lives directly in the HTML files as plain text/tags — edit them
with any text editor. Shared look-and-feel (colors, spacing, fonts) lives in
`css/style.css`.
