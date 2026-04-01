---
layout: default
title: Project Status
parent: Wiki
nav_order: 2
---

<!-- markdownlint-disable MD033 -->

This page exists to separate current reality from future intent.

<div class="mnemo-doc-intro">
  <p class="mnemo-doc-intro__eyebrow">Roadmap context</p>
  <p>Use this page to explain where the product is today, what the next milestones are, and how that should constrain public-facing documentation.</p>
</div>

<div class="mnemo-doc-grid">
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Current</p>
    <h3>What is already real</h3>
    <p>The app is local-first today, while the site/backend already exists as the public and editorial foundation.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Next</p>
    <h3>What unlocks continuity</h3>
    <p>Account creation, sign-in, and sync are the next functional layers that move Mnemo beyond single-device local usage.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Policy</p>
    <h3>How docs should speak</h3>
    <p>Describe shipped behavior as supported and planned work as planned, without blending the two into implied availability.</p>
  </div>
</div>

## Current state

- The Flutter app is primarily local-first.
- Core memory capture and recall workflows already exist.
- The public website already works as a marketing/editorial backend.
- Backend foundations for accounts, JWT auth, OAuth configuration, and object storage already exist.

## Next major milestones

1. Connect the Flutter app to the backend for cloud account creation and sign-in.
2. Add cloud sync for dataset and media continuity.
3. Turn Flutter Web from a technical target into a supported product surface.

## Documentation policy

Public docs should:

- describe shipped user behavior as supported
- describe planned work as planned
- avoid implying automatic sync or full web support until those flows are live

<!-- markdownlint-enable MD033 -->
