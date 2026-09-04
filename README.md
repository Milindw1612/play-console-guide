# Play Console Guide

A hands-on, click-through simulation of the real Google Play Console — from opening a
developer account through publishing, monetizing, testing, revenue, billing and growth —
narrated by a voice guide ("Priya") with live Q&A. Built as a training/demo tool; not
affiliated with Google.

## Pages

Once GitHub Pages is enabled on this repo (Settings → Pages → Deploy from branch `main` /
root), these are served at `https://milindw1612.github.io/play-console-guide/`:

- **[index.html](index.html)** — the 55-screen Play Console walkthrough (account →
  payments → store listing → monetization setup → build & test → release → revenue &
  billing → marketing & growth, including paid social, influencers, referral and
  retention), with voice narration and an "Ask Priya" chat.
- **[demo.html](demo.html)** — a self-playing, narrated product demo ("FocusGarden Goes
  Live") for the "Everything After the Build" platform concept.
- **[strategy.html](strategy.html)** — the product/business strategy document behind the
  concept.
- **[legal-brief.html](legal-brief.html)** — a Phase 0 research briefing on how the
  platform can legally collect its 15% revenue share in India (Payment Aggregator
  classification, UPI AutoPay limits, GST, TDS, DPDP). Research, not legal advice — built
  to prepare for a CA/lawyer consultation.

## Notes

- Pure static HTML/CSS/JS — no build step, no dependencies to install.
- `index.html`'s "Ask Priya" live-answer feature only activates inside Claude's own artifact
  viewer; opened here on GitHub Pages it falls back to its built-in notes and local search
  automatically.
- Voice narration and voice input use the browser's built-in Web Speech APIs (best support:
  Chrome / Edge).
