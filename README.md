# StockLive Dairy MLT Builder v6.5

Static browser-based Dairy MLT Builder for preparing NextLot MLT upload files.

## Package contents

- `index.html` — live site file used by Netlify.
- `Dairy_MLT_Builder_v6_5.html` — versioned backup/reference copy.
- `netlify.toml` — publishes the repository root as a static Netlify site.
- `README.md` — deployment notes.

## Upload to GitHub

Upload all files in this folder to the root of the GitHub repository.

For future updates:
1. Replace `index.html` with the latest Dairy MLT Builder HTML.
2. Add or replace the versioned backup HTML.
3. Commit/push the changes to GitHub.

## Deploy to Netlify from GitHub

If your Netlify site is already connected to this GitHub repository, committing the updated files should trigger a redeploy.

For a new Netlify site:
1. Choose **Add new site** / **Import an existing project**.
2. Connect the GitHub repository.
3. No build command is required.
4. Publish directory: `.`
5. Deploy.

## Manual Netlify deploy

Unzip this package and drag the folder into Netlify's manual deploy area.

## Notes

The builder is a static browser application and loads SheetJS from its CDN.

Saved column mappings are stored in the browser's local storage. They stay with that browser/device unless recreated there.
