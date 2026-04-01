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
          <span>Offline-first app guidance with product status and support routing.</span>
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
    <span class="mnemo-pill">Cloud account next</span>
    <span class="mnemo-pill">Sync before full web support</span>
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
- Cloud account integration is planned next through the Mnemo web/backend platform.
- Cloud sync and a fully supported Flutter Web experience come after account integration.

<div class="mnemo-grid">
  <div class="mnemo-card mnemo-card--third">
    <h3>What is supported now</h3>
    <p>Private capture, structured recall, and local-first usage are the current product baseline.</p>
  </div>
  <div class="mnemo-card mnemo-card--third">
    <h3>What is coming next</h3>
    <p>Backend-backed accounts and JWT-authenticated continuity from the app to the web platform.</p>
  </div>
  <div class="mnemo-card mnemo-card--third">
    <h3>What depends on sync</h3>
    <p>Cross-device continuity, cloud media flows, and a product-ready Flutter Web surface.</p>
  </div>
</div>

## Where to start

- New to Mnemo: read [Getting started]({{ site.baseurl }}/docs/user-manual/getting-started/)
- Want the current roadmap context: read [Project status]({{ site.baseurl }}/docs/wiki/project-status/)
- Need help or want to report something: read [Feedback and issues]({{ site.baseurl }}/docs/wiki/feedback-and-issues/)

## Notes on scope

This site should describe what is actually available, not what is merely scaffolded in code. If a feature is planned but not yet user-ready, document it as planned, not as supported.

<!-- markdownlint-enable MD033 -->
