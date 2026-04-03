---
layout: default
title: Troubleshooting
parent: Support
nav_order: 3
permalink: /docs/support/troubleshooting/
---

<!-- markdownlint-disable MD033 -->

This page focuses on guidance that matches the current product state.

<div class="mnemo-doc-intro">
  <p class="mnemo-doc-intro__eyebrow">Expectation gaps</p>
  <p>Most friction points come from treating continuity as either automatic everywhere or absent everywhere. Start with the documented scope, then troubleshoot outward.</p>
</div>

<div class="mnemo-doc-grid">
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Sync</p>
    <h3>Another device is empty</h3>
    <p>Continuity is available, but another device may still require sign-in, unlock, or a manual retry before the archive appears.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Discovery</p>
    <h3>Search misses an entry</h3>
    <p>Broaden the query and verify related organization surfaces such as folders, tags, timeline, media, map, or calendar views.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Reminder system</p>
    <h3>Notifications do not appear</h3>
    <p>Check device permissions, in-app settings, and whether the reminder was actually saved on the entry.</p>
  </div>
</div>

## I expected cloud sync, but I cannot find it

Mnemo is local-first by design, with continuity available on top. If you cannot find sync behavior, check that you are signed in, that any required unlock step is complete, and that your build exposes the expected sync controls.

## I cannot find my saved data on another device

Start with the cloud path rather than assuming sync is absent:

- verify you are signed in with the same cloud account
- verify any required cloud unlock step is complete
- trigger a manual sync from settings if the current build exposes that control
- fall back to local/export-import flows if the current environment is still constrained or offline

## Search is not finding what I expect

- try broader search terms
- verify the entry actually exists in the current dataset
- check related organization surfaces such as folders, tags, timeline, or media views

## Reminders or notifications are missing

- verify your device notification permissions
- verify in-app notification settings
- verify the reminder was actually saved on the entry

## I am unsure whether a feature is supported or just planned

Use [Availability notes]({{ site.baseurl }}/docs/support/availability/) as the short reference page. If the docs are unclear, open an issue so the wording can be corrected.

<!-- markdownlint-enable MD033 -->
