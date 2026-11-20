# SANGAR Coastal, LLC website

Static site for www.sangarcoastal.com, served by GitHub Pages from the `docs/` folder.

## Update the site
1. Edit files in `docs/` (`index.html`, `css/styles.css`, `js/main.js`, `images/`).
2. Commit on a branch, open a pull request, and merge it to `main`.
3. GitHub Pages republishes within a minute or two of the merge.

## Files
- `docs/CNAME`: the custom domain. Don't delete it.
- `docs/.nojekyll`: serves files as-is (no Jekyll processing).
- `docs/404.html`: shown automatically for missing pages.

## DNS (at Network Solutions)
- `@` A records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `www` CNAME: jsantoyo-r11.github.io

## Headshots (optional)
Add `docs/images/javier.jpg` and `docs/images/norma.jpg` (square, 300x300 or larger), then swap each
`<div class="avatar">` in `index.html` for the commented `<img>` line next to it.
