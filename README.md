# Play Console Guide

A hands-on, click-through simulation of the real Google Play Console — from opening a
developer account through publishing, testing, revenue, billing and growth — narrated by a
voice guide ("Maya") with live Q&A. Built as a training/demo tool; not affiliated with
Google.

## Pages

Once GitHub Pages is enabled on this repo (Settings → Pages → Deploy from branch `main` /
root), these are served at `https://milindw1612.github.io/play-console-guide/`:

- **[index.html](index.html)** — the 44-screen Play Console walkthrough (account →
  payments → store listing → build & test → release → revenue & billing → marketing &
  growth), with voice narration and an "Ask Maya" chat.
- **[demo.html](demo.html)** — a self-playing, narrated product demo ("FocusGarden Goes
  Live") for the "Everything After the Build" platform concept.
- **[strategy.html](strategy.html)** — the product/business strategy document behind the
  concept.

## Notes

- Pure static HTML/CSS/JS — no build step, no dependencies to install.
- `index.html`'s "Ask Maya" live-answer feature only activates inside Claude's own artifact
  viewer; opened here on GitHub Pages it falls back to its built-in notes and local search
  automatically.
- Voice narration and voice input use the browser's built-in Web Speech APIs (best support:
  Chrome / Edge).
