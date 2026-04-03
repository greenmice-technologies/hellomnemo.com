# docs.hellomnemo.com

Technical repository for the Mnemo GitHub Pages site.

This repo publishes the static user-facing documentation surface for Mnemo at `https://docs.hellomnemo.com`. It is not the canonical source for product contracts, backend behavior, or persisted model details.

## Canonical technical references

- Cross-repo assessment and shared documentation policy: [`../hellomnemo.com/docs/index.md`](../hellomnemo.com/docs/index.md)
- Persisted model mirror and compatibility notes: [`../hellomnemo.com/docs/models/README.md`](../hellomnemo.com/docs/models/README.md)
- Cloud account and sync configuration catalog: [`../hellomnemo.com/docs/configuration.md`](../hellomnemo.com/docs/configuration.md)
- Web/backend repository: [`../hellomnemo.com/README.md`](../hellomnemo.com/README.md)
- Flutter client repository: [`../mnemo/readme.md`](../mnemo/readme.md)

Use this repository for the static user site only. Shared technical references remain upstream in `hellomnemo.com/docs/`.

## Site structure

- `index.md`: public homepage for Mnemo users
- `docs/user-manual/`: getting started, features, privacy/settings, and cloud/sync guidance
- `docs/wiki/`: FAQ, troubleshooting, support routing, and secondary status notes
- `_config.yml`: Jekyll and Just the Docs configuration

## Stack and prerequisites

- Ruby
- Bundler
- Jekyll
- GitHub Pages / Just the Docs theme configuration in this repo

## Local development

Install dependencies and run the local site:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

Build locally without serving:

```bash
bundle exec jekyll build
```

## Deployment

The site is deployed through GitHub Pages via `.github/workflows/pages.yml` on pushes to `main`.

If the site is served from `docs.hellomnemo.com`, keep Pages and DNS aligned:

- repository Pages settings use the correct branch and custom domain
- DNS for `docs.hellomnemo.com` points to GitHub Pages
- HTTPS is enabled in Pages settings after DNS resolution
