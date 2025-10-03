# Tejas Shrestha — 11ty site

This is a minimal Eleventy (11ty) static site configured to deploy to GitHub Pages using GitHub Actions.

How it works:
- Source files live in `src/`.
- Build output goes to `_site/`.
- On push to `main`, GitHub Actions builds the site and deploys with `actions-gh-pages`.

Local commands:

```powershell
npm install
npm run build   # build into _site/
npm run start   # dev server with live reload
```

To enable GitHub Pages: in the repository Settings → Pages, choose the `gh-pages` branch (deployed by the workflow).
