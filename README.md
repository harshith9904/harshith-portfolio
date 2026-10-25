# Harshith Ram — Portfolio

Static site, no build step. Everything needed to publish is in this `site/` folder.

```
site/
├── index.html        the portfolio
├── 404.html          "page not found" page
├── favicon.svg
├── robots.txt
└── assets/
    ├── harshith.jpg          photo (compressed)
    ├── og.jpg                link preview image (LinkedIn, WhatsApp, X)
    └── apple-touch-icon.png
```

## Live site

https://harshithram.com (also https://harshithram.netlify.app; Netlify project `harshithram`, admin: https://app.netlify.com/projects/harshithram)

Publishing is automatic: every push to `main` on GitHub
(https://github.com/harshith9904/harshith-portfolio) deploys to Netlify within about a minute.
Settings live in `netlify.toml` (no build step; the repo root is published as-is).

```bash
git add -A && git commit -m "Update portfolio" && git push
```

## Editing content

All text lives in `index.html`. Search for the section label (e.g. `04 / Experience`) to find it.
Contact email is `ram.h@aptivacorp.ae`; it appears in the contact section, the mobile menu and the
structured data at the top of the file.
