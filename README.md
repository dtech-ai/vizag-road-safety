# Road Safety Analysis Report, Visakhapatnam

Static site, ready for GitHub Pages. No build step.

## Contents

- `index.html` : the full report (data, maps, slides and PowerPoint files are embedded)
- `vendor/chart.umd.min.js` : Chart.js 4.4.1, served locally so charts do not depend on a CDN
- `.nojekyll` : tells GitHub Pages to serve the files as they are

## Publish

1. On github.com, create a new repository (for example `road-safety-report`).
2. Open the repository, choose **Add file > Upload files**, and drag in everything from this folder, including the `vendor` folder and `.nojekyll`. Commit.
3. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**. Save.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

## On the iPad

1. Open the link in Safari.
2. Tap **Share > Add to Home Screen**. The report then opens full screen from its own icon, without the Safari address bar.

## Notes

- On a free GitHub account, Pages only works from a public repository, so anyone with the link can open the report and see the files. The page asks search engines not to index it, but that is not access control.
- The only outside request is to Google Fonts. If it is blocked, the report falls back to the system font and still works.
- To update, upload a new `index.html` over the old one. The link stays the same.
