# Kin Arc

[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-2ea44f?logo=github)](https://melvinsalas.github.io/kinarc/)

**Live demo:** Kin Arc is published on GitHub Pages at [melvinsalas.github.io/kinarc](https://melvinsalas.github.io/kinarc/).

A private, client-side GEDCOM ancestor fan chart. Open `dist/index.html` through any static web server; no build step or backend is required.

## Run locally

```powershell
python -m http.server 4173 --directory dist
```

Then open `http://localhost:4173`.

## Static hosting

Publish the contents of `dist/` to GitHub Pages, Cloudflare Pages, Netlify, or any static host. All GEDCOM parsing happens in the visitor's browser through the File API. Files are never submitted to a server.

The page loads D3.js 7.9 and two webfont families from public CDNs. Vendor these files locally if the viewer must run without an internet connection.

## GEDCOM support

The parser accepts standard GEDCOM 5.x line records and reads `INDI`, `FAM`, `NAME`, `BIRT`, `DATE`, `PLAC`, `FAMC`, `HUSB`, `WIFE`, and `CHIL` structures. Unknown or ambiguous countries are deliberately labeled `Unknown`; the chart never silently assigns them.
