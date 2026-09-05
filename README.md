# NetFlow ISP Web — GitHub Pages Ready

This package is prepared so the ISP Web opens directly from the repository root on GitHub Pages.

## Upload

Upload the CONTENTS of this folder to the root of your GitHub repository. Do not put them inside another folder.

The repository root must contain:

- `index.html` — ISP Web
- `CLOUD_TEST.html` — Cloud connection test
- `customer/` — Customer Portal files
- `sql/` — reference SQL files

## GitHub Pages

GitHub → Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

After deployment, open the GitHub Pages URL. The root URL opens NetFlow ISP Web automatically.

## Supabase

The ISP Web already contains the configured Supabase project URL and publishable key used by the current project. Never put a Supabase service-role key in browser code.

Customer Portal is available at `/customer/`.

## Important

For changes that require database functions, run the SQL in the `sql/` folder in Supabase SQL Editor.
