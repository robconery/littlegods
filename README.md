# Rob Conery · Satirical Résumé

A single-file site. `index.html` has everything inlined (fonts, photos, scripts), so it works from any static host with no build step.

## Publish on GitHub Pages

1. Create a repo (for example `resume`) and push this folder's contents to the root of the `main` branch.
2. In the repo: Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
3. Wait a minute, then open `https://<your-user>.github.io/resume/`.

`.nojekyll` is included so Pages serves the file as-is.

## Print / PDF

Open the page and print it (Cmd/Ctrl+P). It is laid out as two US Letter pages.
