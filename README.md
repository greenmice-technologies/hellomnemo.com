# Mnemo Docs

Public documentation repository for Mnemo.

This repository is the public entrypoint for:

- user-facing documentation
- project status and rollout notes
- issue tracking and feedback routing

Repository: `greenmice-technologies/hellomnemo.com`

The site is published with GitHub Pages and is intended to live at `https://docs.hellomnemo.com`.

## Site structure

- `index.md`: documentation hub home
- `docs/user-manual/`: public user guidance for supported app workflows
- `docs/wiki/`: project FAQ, status notes, troubleshooting, and feedback/issue routing

## Product framing

Mnemo is documented here as a private, offline-first memory system with cloud continuity available.

Current public guidance should reflect the real product state:

- local-first usage is the current default
- cloud account integration is live
- cloud sync is available
- Flutter Web is available with caveats rather than documented as feature-perfect parity

Do not publish docs that deny real sync capabilities, but do not overstate browser support or continuity reliability beyond what is actually documented.

## Local development

Requires Ruby and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Deployment

The site is deployed through GitHub Pages via `.github/workflows/pages.yml` on pushes to `main`.

If the site is served from `docs.hellomnemo.com`, make sure:

- the repository Pages settings use that custom domain
- DNS for `docs.hellomnemo.com` points to GitHub Pages with a `CNAME`
- HTTPS is enabled in Pages settings once DNS resolves correctly
