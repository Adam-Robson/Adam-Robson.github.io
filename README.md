# adam-robson.github.io

Source for my personal site, live at **<https://adam-robson.github.io>**.

I build data pipelines, automation, and the software that connects them, working in TypeScript, Python, PowerShell, and T-SQL.

- Résumé: [view or download the PDF](https://adam-robson.github.io/assets/Adam-Robson-Resume.pdf)
- LinkedIn: [linkedin.com/in/adamrayrobson](https://linkedin.com/in/adamrayrobson)

## How the site is built

Plain HTML and CSS with no build step and no JavaScript. GitHub Pages serves the files as they are.

```txt
index.html              page content
css/styles.css          design tokens, then styles section by section
assets/
  Adam-Robson-Resume.pdf   résumé linked from the page
  contours.svg             generated topographic line art behind the hero
  icons.svg                icon sprite (Lucide, ISC license)
  favicon.svg
  og-image.png             link-preview image (1200 × 630)
  fonts/                   self-hosted Bricolage Grotesque and Literata (SIL OFL)
.nojekyll               tells GitHub Pages to skip Jekyll processing
```

To preview locally:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```
