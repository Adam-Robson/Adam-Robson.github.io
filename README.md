# adam-robson.github.io

This is the source code for a personal site: live at **<https://adam-robson.github.io>**.

I build automation workflows, data pipelines, and the software that connects
them. I work working in TypeScript, Python, PowerShell, and SQL.

- Résumé: [view or download the PDF](https://adam-robson.github.io/assets/Adam-Robson-Resume.pdf)
- LinkedIn: [linkedin.com/in/adamrayrobson](https://linkedin.com/in/adamrayrobson)

## Architecture

Plain HTML and CSS with no build step and no JavaScript.

GitHub Pages serves the files as they are.

```txt
index.html              page content
css/styles.css          design tokens, then styles section by section
assets/
  Adam-Robson-Resume.pdf   résumé linked from the page
  icons.svg                icon sprite (Lucide, ISC license)
  favicon.svg
  og-image.png             link-preview image (1200 × 630)
  fonts/                   self-hosted Sofia Sans Semi-Condensed
.nojekyll              tell GitHub Pages to skip Jekyll processing
```

To preview locally:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```
