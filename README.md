# 🌻 Sunflower Bouquet

A tiny, dependency-free web page that **draws a bouquet of sunflowers** stroke-by-stroke when it opens, then lets the flowers gently sway. Built with plain HTML, CSS and a bit of vanilla JavaScript — no build step, no frameworks.

## Features
- **Self-drawing animation** — stems, leaves, petals and the kraft-paper wrapper are sketched in order using animated SVG `stroke-dashoffset`, with fills fading in behind each outline.
- **Two hand-generated sunflowers** — petals are drawn parametrically, so they look organic rather than copy-pasted.
- **Mobile-first & responsive** — scalable SVG (`viewBox`), fluid sizing, safe-area insets for notched phones, and a `prefers-reduced-motion` fallback.
- **Replay** — a *Draw again* button re-runs the whole animation.

## Run it
Just open `index.html` in any browser. That's it.

## Structure
- `index.html` — the entire project (markup, styles and script in one file).
