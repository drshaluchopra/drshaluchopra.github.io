# Dr. Shalu Chopra

Personal academic website of Dr. Shalu Chopra, media and mass communication scholar, researcher, and columnist.

Built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages.

## Develop locally

```bash
hugo server
```

Then open http://localhost:1313.

## Build

```bash
hugo --gc --minify
```

Deployment is automatic: pushing to `main` triggers the GitHub Actions workflow in `.github/workflows/hugo.yml`, which builds the site and publishes it to GitHub Pages.
