# Economics Studio

One front door to three economics sites. **→ https://xyjiapku.github.io/**

| Site | What it is | URL |
|---|---|---|
| **Economics Mini Lab** | 26 small single-file interactive tools (Chart.js) | `/economics_mini_lab/` |
| **Intelligent Textbook** | Three interactive economics books, one front door | `/intelligent-textbook/` |
| **Courseware** | Projector-ready HTML decks: AP Micro, AP Macro, IGCSE Econ | `/econ-courseware/` |

This repository holds only the landing page (`index.html`). The three sites are
separate repositories, each published from `main` / root on GitHub Pages.

## Publishing notes

- Served from `main` / root; `.nojekyll` is present so Pages serves files as-is.
- Self-contained: the masthead typeface is embedded as a base64 subset, so the page
  needs no network request (see `FONT-LICENSE.md`).
- Card links are absolute (`https://xyjiapku.github.io/...`) because the three
  projects live in their own repositories.

## Related

- 互动小程序 · Economics Mini Lab — https://xyjiapku.github.io/economics_mini_lab/
- 智能教材 · Intelligent Textbook — https://xyjiapku.github.io/intelligent-textbook/
- 课件 · Courseware — https://xyjiapku.github.io/econ-courseware/
