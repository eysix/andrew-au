# andrew-au

Andrew Au's portfolio site, laid out after tianhuiyang.me: a seal logo and a short menu
(experience · projects · about · contact) on every page.

- `index.html`: experience (work, leadership, education, skills). Each entry is one line,
  with the full resume bullets under a "more" toggle.
- `projects.html`: side projects.
- `about.html`: a short letter.

Plain HTML and CSS with no build step. The only JavaScript is `theme.js`, which powers the
light/dark toggle (it follows the system setting until a visitor picks one).

## Run locally

Open `index.html` in a browser, or use the VS Code Live Server extension.

## Update content

- Words live in the three HTML files. The header and icon footer are repeated on each page.
- Colours and fonts are CSS variables at the top of `style.css`.

## Deploy

Hosted on GitHub Pages: Settings → Pages → Deploy from a branch → `main`, `/ (root)`.
Custom domain `andrewau.is-a.dev` is set in `CNAME`. Every push to `main` redeploys the site.
