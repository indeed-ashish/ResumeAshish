# Ashish Ranjan Sinha — Portfolio

Static personal portfolio (semantic HTML5 + CSS3, no build step).

## Structure

```
.
├── index.html        # Home
├── about.html
├── education.html
├── experience.html
├── skills.html
├── contact.html
├── 404.html          # Custom GitHub Pages error page
├── css/style.css     # Shared stylesheet (required)
├── .nojekyll         # Serve files as-is, skip Jekyll
└── .github/workflows/pages.yml
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy on GitHub Pages

1. Push this folder to a GitHub repository (branch `main`).
2. Go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**
   (or choose **Deploy from a branch → main → / (root)** and delete the workflow file).
3. The site will be live at `https://<username>.github.io/<repo>/`
   (or `https://<username>.github.io/` if the repo is named `<username>.github.io`).

All links are relative, so the site works at both a root and a sub-path URL.
