# gh-deployment-workflow

A static website deployed to GitHub Pages with GitHub Actions.

## How it works

- `index.html` is the whole site.
- `.github/workflows/deploy.yml` runs on every push to `main` that changes `index.html`.
- The workflow stages the file, uploads it as a Pages artifact, and deploys it.
- Pushes that don't touch `index.html` (for example README edits) do not trigger a deploy.

## Live site

https://hasitharao.github.io/gh-deployment-workflow/

