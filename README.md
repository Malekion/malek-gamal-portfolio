# Malek Gamal — Esports Operations Portfolio

Personal portfolio of Malek Gamal, Senior Operations Executive and Stage Manager in the MENA esports scene.

- `index.html` — the website (single static page, no build step)
- `malek-gamal-portfolio.pdf` — the same content as a 16:9 PDF deck
- `img/` — event photos

## Updating the PDF

The PDF is printed from `index.html` using the print styles in the page:

```
msedge --headless=new --no-pdf-header-footer --virtual-time-budget=10000 --print-to-pdf=malek-gamal-portfolio.pdf index.html
```

Event attendance and reach figures come from organiser and press reports.
