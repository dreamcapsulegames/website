# website

Static site for [dreamcapsulegames.com](https://dreamcapsulegames.com), hosted on GitHub Pages.

## Structure

- `index.html` — the page
- `style.css` — styles
- `CNAME` — custom domain for GitHub Pages
- `.github/workflows/deploy.yml` — deploys to Pages on push to `main`

## Deployment

Every push to `main` triggers the workflow, which publishes the repo root to GitHub Pages.

**One-time setup** (in the repo on GitHub): Settings → Pages → Build and deployment → Source = **GitHub Actions**.
