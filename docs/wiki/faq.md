---
layout: default
title: FAQ
parent: Wiki
nav_order: 1
---

<!-- markdownlint-disable MD033 -->

<div class="mnemo-doc-intro">
  <p class="mnemo-doc-intro__eyebrow">Quick answers</p>
  <p>Use this page when someone needs the short version: what Mnemo is, what is already supported, and where cloud and web support currently stand.</p>
  <div class="mnemo-doc-tags">
    <span class="mnemo-doc-tag">Product framing</span>
    <span class="mnemo-doc-tag">Cloud status clarity</span>
    <span class="mnemo-doc-tag">Web support caveats</span>
  </div>
</div>

<div class="mnemo-callout mnemo-callout--accent">
  <p><strong>Default answer posture:</strong> document current user reality as local-first by design, describe cloud accounts and cloud sync as live, and describe the web surface as available with caveats.</p>
</div>

## What is Mnemo?

Mnemo is a private Memory OS: a personal system for capturing fragments of life, preserving their context, and resurfacing them later through timeline, search, map, calendar, reminders, and related views.

## Is Mnemo just a journaling app?

No. Mnemo overlaps with journaling, but its framing is broader. It is meant to connect notes, media, links, places, reminders, and reflection into a retrievable personal memory layer.

## Is Mnemo cloud-based today?

Partially.

The current product is still centered on local-first usage, but it now also includes cloud-backed continuity. Cloud account integration and cloud sync are live, while the user experience still needs caveat language around browser/runtime limits and rollout hardening.

## Does Mnemo already have a backend?

Yes. `hellomnemo.com` already functions as the public site and editorial backend, and it also powers the shipped cloud account, dataset, and vault layers used by the Flutter app.

## Can I use Mnemo on the web?

A Flutter Web surface exists and participates in the same cloud-backed continuity layer. Public docs should treat web support as available with caveats rather than as full browser-parity across every scenario.

## Where should I report bugs or request features?

Use the public repository issue tracker referenced from [Feedback and issues]({{ site.baseurl }}/docs/wiki/feedback-and-issues/).

<!-- markdownlint-enable MD033 -->
