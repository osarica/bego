# Begum Karabiyikoglu: model portfolio

A static, single-page portfolio site. It has no build step, so the files can be uploaded as they are.

## Contents

- `index.html`: the whole site (HTML, CSS and JavaScript in one file)
- `img/`: full-size photos (1400 px, used on desktop and tablet)
- `img/m/`: smaller photos (900 px, served to phones automatically)

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `begum-portfolio`.
2. Upload everything in this folder (`index.html`, `README.md` and the `img` folder) to the repository root.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set Source to "Deploy from a branch", choose `main`, folder `/ (root)`, and save.
5. After about a minute the site is live at `https://<your-username>.github.io/begum-portfolio/`.

## After it is live

- Link previews (WhatsApp, iMessage, LinkedIn) need an absolute image URL. In `index.html`, change
  `<meta property="og:image" content="img/begum-01.jpg">` to the full URL, e.g.
  `https://<your-username>.github.io/begum-portfolio/img/begum-01.jpg`.
- To use a custom domain (e.g. begumkarabiyikoglu.com), add it under Settings > Pages > Custom domain.

## Editing

- Measurements: search for `class="card"` in `index.html`.
- Photo order: search for `data-spreads`. Numbers refer to `img/begum-NN.jpg`.
- Contact details: search for `class="lines"`.
