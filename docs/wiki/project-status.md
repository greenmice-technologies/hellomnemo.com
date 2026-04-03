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
    <p>The app is still local-first by design, while the site/backend now serves as the public, editorial, account/auth, and cloud-sync foundation.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Available with caveats</p>
    <h3>What needs careful wording</h3>
    <p>Sync-backed continuity and the web surface are real, but they still need explicit caveats around browser/runtime limits and rollout hardening.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Policy</p>
    <h3>How docs should speak</h3>
    <p>Describe account and sync as supported, describe the web surface as available with caveats, and keep residual rollout work clearly separated from shipped capability.</p>
  </div>
</div>

## Current state

- The Flutter app is primarily local-first.
- Core memory capture and recall workflows already exist.
- The public website already works as a marketing/editorial backend.
- Cloud account creation, verification, sign-in, password reset, deletion, JWT auth, and provider sign-in are live across supported app surfaces.
- Cloud dataset and media sync are available through the same backend.
- The public website/backend actively powers the shipped account layer and the live continuity layer.

## Next major milestones

1. Reduce residual browser/runtime caveats on the web surface.
2. Improve reliability, observability, and UX around sync and recovery flows.
3. Finish rollout hardening for universal links, app links, and other external operational dependencies.

## Documentation policy

Public docs should:

- describe shipped user behavior as supported
- describe cloud accounts and cloud sync as live
- describe the web surface as available with caveats
- describe planned work as planned
- avoid claiming feature-perfect parity where residual caveats still exist

<!-- markdownlint-enable MD033 -->
