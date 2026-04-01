# hellomnemo.com

Public documentation repository for the HelloMnemo mobile app.

This site is served via [GitHub Pages](https://hellomnemo.com) and contains user manuals, wikis, and guides for HelloMnemo users.

## Contents

- **User Manual** – Step-by-step guides covering getting started, core features, and account settings.
- **Wiki** – In-depth articles including FAQ, tips & tricks, and troubleshooting.

## Local Development

Requires Ruby and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000` in your browser.

## Deployment

The site is automatically built and deployed to GitHub Pages on every push to the `main` branch via the GitHub Actions workflow in `.github/workflows/pages.yml`.
