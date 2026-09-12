# Colin Watson’s portfolio

Static portfolio hosted on GitHub Pages at https://colinwatson.me/.

Edit `dist/index.html`, `dist/styles.css`, and `dist/assets/`. Push to `main` to deploy automatically with GitHub Actions.

Local preview: `python3 -m http.server 4173 --directory dist`.

## Domain

Configure the apex (`@`) with A records for `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. Configure `www` as a CNAME to `watsoncolin.github.io`. Preserve mail and verification records.
