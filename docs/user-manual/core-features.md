---
layout: default
title: Core Features
parent: User Manual
nav_order: 2
---

<!-- markdownlint-disable MD033 -->

Mnemo is built around one idea: personal memory should stay connected to its context.

<div class="mnemo-doc-intro">
  <p class="mnemo-doc-intro__eyebrow">Capability map</p>
  <p>The product already covers capture, organization, recall, account access, and cloud continuity as a coherent loop. This page tracks that loop without overstating the caveats that still exist on the web/runtime side.</p>
</div>

<div class="mnemo-doc-grid">
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Input</p>
    <h3>Capture</h3>
    <p>Text, media, links, and attachments are the raw fragments Mnemo helps preserve with context attached.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Structure</p>
    <h3>Organize</h3>
    <p>Folders, tags, related entries, time, place, and reminders turn collected fragments into retrievable memory.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Output</p>
    <h3>Recall surfaces</h3>
    <p>Timeline, search, map, calendar, and media views are designed to bring memories back when they matter.</p>
  </div>
  <div class="mnemo-doc-card">
    <p class="mnemo-doc-kicker">Storage</p>
    <h3>Local-first plus cloud continuity</h3>
    <p>Persistence, media storage, export/import, cloud accounts, and cloud sync now coexist in the current product surface.</p>
  </div>
</div>

## Capture

Mnemo supports multimodal capture for memory fragments such as:

- text entries
- photos
- audio and voice notes
- videos
- document attachments
- saved links

## Organize

Entries can be structured with:

- folders
- tags
- pinned/starred states
- references to related entries
- time metadata
- place metadata
- reminders

## Recall surfaces

Mnemo is not only a place to save things. It is designed to help you find them again through:

- timeline view
- search
- map view
- calendar view
- media-driven browsing
- reminder-based resurfacing

## Local-first data handling

Current supported behavior is centered on local persistence with cloud continuity available on top.

- the primary dataset is stored as `data.json`
- media is stored alongside the dataset
- ZIP import/export exists for portability and backup
- cloud accounts are live for identity and authentication flows
- cloud sync is available for dataset and media continuity
- manual and automatic sync paths may both appear depending on platform and current build
- local storage remains part of the product even when the cloud layer is enabled

Cloud continuity is now part of the documented product behavior, but web/browser caveats should still be called out explicitly.

## What is changing next

The next strategic steps are:

1. stronger reliability and observability for sync behavior
2. tighter browser/runtime hardening for Flutter Web
3. rollout hardening for account-related app links, universal links, and distribution touchpoints

Until those steps are finished, this manual should describe the app as local-first with cloud continuity available, and the web surface as available with caveats.

<!-- markdownlint-enable MD033 -->
