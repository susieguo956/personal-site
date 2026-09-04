# personal-site

Susie Guo's personal website. Plain static HTML/CSS, deployed to GitHub Pages via GitHub Actions on push to `main`.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

1. Create a GitHub repo named `personal-site` under your account.
2. Push this repo to it.
3. In the repo's Settings → Pages, set the source to "GitHub Actions".
4. Push to `main` to trigger the deploy workflow.

Site will be live at `https://<username>.github.io/personal-site/`.
