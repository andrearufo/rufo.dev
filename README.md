# rufo.dev

Personal website for Andrea Rufo — Sviluppatore full-stack e consulente software.

The project is completely static and has no runtime dependencies or build step:

- `index.html` contains the page content and metadata.
- `css/style.css` contains the responsive light and dark themes.
- `fonts/` holds Inter and Newsreader, subset to Latin (`pyftsubset --unicodes="U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+20AC,U+2122,U+2190-2199,U+2212,U+2215" --layout-features='*' --flavor=woff2`).
- `og-image.png` (1200×630) is the social sharing preview.

## Local

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Served by GitHub Pages from the `master` branch root. The `CNAME` file binds the custom domain `rufo.dev`; `www.rufo.dev` redirects to it.
