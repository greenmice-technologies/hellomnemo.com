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
    <p>The app is local-first for data today, while the site/backend already serves as the public, editorial, and account/auth foundation.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Next</p>
    <h3>What unlocks continuity</h3>
    <p>Sync is the next functional layer that moves Mnemo beyond authenticated but still local-first usage.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Policy</p>
    <h3>How docs should speak</h3>
    <p>Describe shipped account flows as supported and sync-dependent work as planned, without blending the two into implied availability.</p>
  </div>
</div>

## Current state

- The Flutter app is primarily local-first.
- Core memory capture and recall workflows already exist.
- The public website already works as a marketing/editorial backend.
- Cloud account creation, verification, sign-in, password reset, deletion, JWT auth, and provider sign-in are live across supported app surfaces.
- The public website/backend actively powers the shipped account layer.

## Next major milestones

1. Add cloud sync for dataset and media continuity.
2. Turn Flutter Web from an auth-capable target into a supported product surface.
3. Finish rollout hardening for universal links, app links, and other external operational dependencies.

## Documentation policy

Public docs should:

- describe shipped user behavior as supported
- describe planned work as planned
- describe cloud accounts as live
- avoid implying automatic sync or full web support until those flows are live

<!-- markdownlint-enable MD033 -->
