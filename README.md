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

https://harshithram.netlify.app (Netlify project `harshithram`, admin: https://app.netlify.com/projects/harshithram)

To publish changes, run from this folder:

```bash
npx netlify-cli deploy --prod --dir . --site harshithram
```

Or drag this folder onto the project's Deploys page in Netlify.

## Editing content

All text lives in `index.html`. Search for the section label (e.g. `04 / Experience`) to find it.
Contact email is `ram.h@aptivacorp.ae`; it appears in the contact section, the mobile menu and the
structured data at the top of the file.
