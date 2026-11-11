# Victor Ogomide - Author Visibility

Static multi-page site (Home, About, Services, Tools, Blog, Portfolio & Reviews, Contact) rebuilt from screenshots.
Pages are rendered client-side from `js/app.js` using hash routes (`#home`, `#about`, ...).

## Structure
- `index.html` - shell: header, footer, script/style links
- `css/style.css` - all styles
- `js/app.js` - page content and hash router
- `images/` - headshots and blog images

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## Deploy on GitHub Pages
Push to a repo, then Settings > Pages > Deploy from branch > `main` / root.

## Notes
Forms and the activation-code tools are visual only; no backend is included.
