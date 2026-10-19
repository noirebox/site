# NoireBox — site

The press & communication site for [NoireBox](https://github.com/noirebox/noirebox), the flight data recorder for AI agents.

The technical reference lives in the main repository and is served at [code.noirebox.eu](https://code.noirebox.eu/). This repository holds everything that is *about* the project rather than *of* it:

| Page | What |
|---|---|
| `index.html` | landing — press kit, articles, code & reference |
| `press.html` | press & media kit (EN) |
| `presse.html` | dossier de presse (FR) |
| `assets/` | banner (JPG/PNG/WebP), architecture diagram, logo and mark (SVG) |

Static HTML, one shared stylesheet, one script, zero dependencies — same identity as the developer reference. Served by GitHub Pages from `main`.

Every figure on the press pages is sourced in the public repository (test count, releases, ADRs, schema versions, attack fixtures). When a release changes one of them, update the pages: the numbers are frozen text, not pulled live.

Press contact: press@noirebox.eu

MIT — see [LICENSE](LICENSE).
