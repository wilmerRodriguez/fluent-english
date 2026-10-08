# Fluent — l'anglais pour francophones

An English-learning site for French speakers, focused on the mistakes they make most: false friends, present perfect vs. passé composé, and English sounds French doesn't have.

**Live site:** https://wilmerrodriguez.github.io/fluent-english/

## Highlights

- **Hover translation (EN ↔ FR):** a glossary tooltip engine annotates English and French terms across the page. It walks text nodes with a `TreeWalker` and uses a `MutationObserver` to annotate content added later, with an EN→FR / FR→EN / Off toggle.
- **Sound trainer:** minimal pairs (think / sink, three / tree) with IPA and pronunciation tips.
- **Printable worksheets:** targeted exercise sheets that can be printed or downloaded.
- **Plans and messaging:** pricing cards, a first-contact form and a demo chat with the teacher.
- **Responsive:** works from small phones up to desktop.

## Stack

A single, dependency-free `index.html`: semantic HTML, modern CSS (custom properties, grid) and vanilla JavaScript (DOM APIs). No build step.

## Run locally

Open `index.html` in a browser.

---

Built by [Wilmer Rodriguez](https://wilmerrodriguez.github.io/cv_landingPage/).
