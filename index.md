---
layout: home
title: Home
nav_order: 1
has_toc: false
---

<!-- markdownlint-disable MD033 -->

<section class="mnemo-hero">
  <div class="mnemo-hero__eyebrow">
    <span class="mnemo-logo-badge" aria-hidden="true">
      <img src="{{ '/assets/images/mnemo-icon.svg' | relative_url }}" alt="" />
    </span>
    <span>Public documentation hub</span>
  </div>
  <div class="mnemo-hero__layout">
    <div>
      <h1>Mnemo Docs</h1>
      <p class="mnemo-hero__lead">
        Mnemo is building a private Memory OS: a personal system for capturing fragments of life, keeping their context attached, and bringing them back when they matter.
      </p>
    </div>
    <aside class="mnemo-hero__panel">
      <p class="mnemo-hero__panel-label">Documentation</p>
      <div class="mnemo-stat-list">
        <div class="mnemo-stat-card">
          <strong>2 tracks</strong>
          <span>User manual and wiki, separated by purpose.</span>
        </div>
        <div class="mnemo-stat-card">
          <strong>Current scope</strong>
          <span>Local-first guidance with cloud account status, cloud sync availability, web caveats, and support routing.</span>
        </div>
      </div>
      <div class="mnemo-hero__actions">
        <a class="mnemo-button mnemo-button--primary" href="{{ site.baseurl }}/docs/user-manual/">Open user manual</a>
        <a class="mnemo-button mnemo-button--secondary" href="{{ site.baseurl }}/docs/wiki/">Open wiki</a>
      </div>
    </aside>
  </div>
  <div class="mnemo-pill-row">
    <span class="mnemo-pill">Offline-first today</span>
    <span class="mnemo-pill">Cloud account live</span>
    <span class="mnemo-pill">Cloud sync available</span>
    <span class="mnemo-pill">Web with caveats</span>
  </div>
</section>

This documentation site is the public hub for product guidance, project status, and issue reporting.

## What you can find here

<div class="mnemo-grid">
  <div class="mnemo-card mnemo-card--half mnemo-card--accent">
    <p class="mnemo-card__eyebrow">Getting started</p>
    <h3>User manual</h3>
    <p>Public guidance for the app as it exists today: capture flows, organization, settings, privacy, and supported user-facing workflows.</p>
    <a class="mnemo-link-card" href="{{ site.baseurl }}/docs/user-manual/">
      <strong>Open the manual</strong>
      <span>Start with current, supported app behavior.</span>
    </a>
  </div>
  <div class="mnemo-card mnemo-card--half mnemo-card--warm">
    <p class="mnemo-card__eyebrow">Project context</p>
    <h3>Wiki</h3>
    <p>Project-facing documentation for FAQs, troubleshooting, product status, and feedback routing.</p>
    <a class="mnemo-link-card" href="{{ site.baseurl }}/docs/wiki/">
      <strong>Open the wiki</strong>
      <span>Use this for status, expectations, and issue intake.</span>
    </a>
  </div>
</div>

## Current product state

- The Flutter app is currently centered on private, offline-first use.
- Local capture, organization, reminders, search, map, calendar, media, and export/import workflows already exist.
- Cloud account creation, verification, sign-in, password reset, delete-account flows, and provider sign-in are live through the Mnemo web/backend platform.
- Cloud sync for dataset and media continuity is available.
- Flutter Web is available on top of the same cloud layer, but still carries caveats around browser/runtime behavior.

<div class="mnemo-grid">
  <div class="mnemo-card mnemo-card--third">
    <h3>What is supported now</h3>
    <p>Private capture, structured recall, local-first usage, cloud account onboarding, and cloud sync are all part of the current product surface.</p>
  </div>
  <div class="mnemo-card mnemo-card--third">
    <h3>What is available with caveats</h3>
    <p>Cross-device continuity and the web surface are available, but they should still be documented with explicit caveats rather than as feature-perfect parity.</p>
  </div>
  <div class="mnemo-card mnemo-card--third">
    <h3>What is still open</h3>
    <p>Browser/runtime hardening, rollout edges such as app links, and residual reliability/observability gaps remain open work.</p>
  </div>
</div>

## Where to start

- New to Mnemo: read [Getting started]({{ site.baseurl }}/docs/user-manual/getting-started/)
- Want the current roadmap context: read [Project status]({{ site.baseurl }}/docs/wiki/project-status/)
- Need help or want to report something: read [Feedback and issues]({{ site.baseurl }}/docs/wiki/feedback-and-issues/)

## Notes on scope

This site should describe what is actually available, not what is merely scaffolded in code. If a feature is live but still caveated, document both parts: availability and caveat.

<!-- markdownlint-enable MD033 -->
