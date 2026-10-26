# StockLive Dairy MLT Builder v6.6

Static browser-based Dairy MLT Builder for preparing NextLot MLT upload files.

## Package contents

- `index.html` — live site file used by Netlify.
- `Dairy_MLT_Builder_v6_6.html` — versioned backup/reference copy.
- `netlify.toml` — publishes the repository root as a static Netlify site.
- `README.md` — deployment notes.

## Upload to GitHub

Upload all four files to the root of the GitHub repository.

If files with the same names already exist, replace the existing `index.html` and update the other files as required, then commit the changes.

## Netlify

If Netlify is already connected to the GitHub repository, committing the updated files should trigger a redeploy automatically.

No build command is required.

Publish directory: `.`

## Notes

Saved column mappings are stored in browser local storage. Deploying a newer builder version does not move mappings between different browsers or devices.

Use `Download Current Mapping Excel` inside the builder to review the current mapping configuration.
