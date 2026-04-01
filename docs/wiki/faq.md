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
  <p><strong>Default answer posture:</strong> document current user reality as local-first, and refer to cloud accounts, sync, and fuller web support as planned until rollout changes.</p>
</div>

## What is Mnemo?

Mnemo is a private Memory OS: a personal system for capturing fragments of life, preserving their context, and resurfacing them later through timeline, search, map, calendar, reminders, and related views.

## Is Mnemo just a journaling app?

No. Mnemo overlaps with journaling, but its framing is broader. It is meant to connect notes, media, links, places, reminders, and reflection into a retrievable personal memory layer.

## Is Mnemo cloud-based today?

Not as the default documented user experience.

The current product is centered on local-first usage. Cloud account integration and sync are planned next, but public docs should not describe them as already available unless the product rollout changes.

## Does Mnemo already have a backend?

Yes. `hellomnemo.com` already functions as the public site and editorial backend, and it also contains backend foundations for account/authentication and object storage. The next product step is to connect the Flutter app to that backend for cloud accounts.

## Can I use Mnemo on the web?

A Flutter Web target exists in the codebase, but complete product support depends on cloud account and sync work. Until that layer is finished, public docs should treat web support as emerging rather than fully available.

## Where should I report bugs or request features?

Use the public repository issue tracker referenced from [Feedback and issues]({{ site.baseurl }}/docs/wiki/feedback-and-issues/).

<!-- markdownlint-enable MD033 -->
