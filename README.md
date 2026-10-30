# getquoto.de

Statische Website für Quoto. Reines HTML und CSS, keine Build-Schritte, keine externen Abrufe.

- `index.html` Startseite, `impressum.html`, `datenschutz.html`
- `assets/style.css` Markenauftritt Variante B (Ablesa-Farben, Zählrolle)
- `assets/fonts/` Barlow, Barlow Condensed, Bricolage Grotesque (SIL OFL 1.1), lokal eingebunden
- Jeder Push auf `main` veröffentlicht über `.github/workflows/pages.yml` auf GitHub Pages.

Lokal ansehen: `python3 -m http.server` im Ordner, dann http://localhost:8000.
