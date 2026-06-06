# WebTokens
my 2nd game

## Hosting

This repository includes a GitHub Actions workflow that deploys the site to GitHub Pages on pushes to `main`.

- The workflow copies `myapp.html` to `index.html` and publishes it.
- After the first successful run, the site will be available at: https://ilovesuomi25-create.github.io/WebTokens/

To trigger deployment, commit and push these changes:

```bash
git add .github/workflows/deploy-pages.yml README.md
git commit -m "Add GitHub Pages deploy workflow"
git push origin main
```

It may take a few minutes for the site to become available after the workflow completes.
