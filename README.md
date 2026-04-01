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

Mnemo is documented here as a private, offline-first memory system.

Current public guidance should reflect the real product state:

- local-first usage is the current default
- cloud account integration is planned next
- cloud sync and full Flutter Web support come after account integration

Do not publish docs that imply cloud sync, multi-device continuity, or fully supported web app flows until they are actually available.

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
