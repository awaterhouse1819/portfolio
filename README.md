# portfolio

Anna Waterhouse, personal portfolio site. Plain static HTML/CSS/JS, served via GitHub Pages.

**Live:** https://awaterhouse1819.github.io/portfolio/

## Layout

```
index.html   # single-page site
style.css    # design tokens + components
script.js    # theme toggle, sticky header, scroll-reveal
.nojekyll    # disable Jekyll on GitHub Pages
```

## Local preview

```sh
python3 -m http.server 8765
```

Then open http://localhost:8765/.

## Deployment

Pushes to `main` deploy automatically via GitHub Pages (source: `main` / root).
