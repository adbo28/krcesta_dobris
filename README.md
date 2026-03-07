# Křížová cesta – Smíření

Jekyll static site deployed to GitHub Pages.

## Local development

**Prerequisites:** Ruby and Bundler installed.

Install dependencies:

```bash
bundle install
```

Start the local server:

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000/krcesta_dobris/`.

To also rebuild when files change, the `serve` command does this automatically. Use `--livereload` for auto browser refresh:

```bash
bundle exec jekyll serve --livereload
```

## Deployment

Pushing to the `main` branch automatically deploys to GitHub Pages via the workflow in `.github/workflows/pages.yml`.
