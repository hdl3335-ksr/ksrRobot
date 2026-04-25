# GitHub Pages Blog

This repository is configured for a GitHub Pages site using the
[Just the Docs](https://github.com/just-the-docs/just-the-docs) theme.

## Included

- `Gemfile` for local Jekyll builds
- `_config.yml` for Just the Docs site settings
- `.github/workflows/pages.yml` for GitHub Pages deployment
- sample markdown pages to get started quickly

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. Open `Settings > Pages`.
3. In `Build and deployment`, set `Source` to `GitHub Actions`.
4. Update `_config.yml`:
   - set `url` to `https://YOUR-USERNAME.github.io`
   - set `baseurl` to `/<YOUR-REPO-NAME>` if this is a project site
   - update `aux_links.Repository` to your actual repository URL

## Local preview

If Ruby, Bundler, and Jekyll are installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
