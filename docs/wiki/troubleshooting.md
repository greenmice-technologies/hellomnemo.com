---
layout: default
title: Troubleshooting
parent: Wiki
nav_order: 5
---

# Troubleshooting

This page focuses on conservative guidance that matches the current product state.

## I expected cloud sync, but I cannot find it

Current public documentation treats Mnemo as local-first by default. If you are testing internal builds or following development work, remember that backend account integration and sync are planned layers, not baseline public behavior yet.

## I cannot find my saved data on another device

Until cloud-backed continuity is fully shipped, do not assume entries automatically appear across devices. Use the product according to the currently documented local/export-import flows.

## Search is not finding what I expect

- try broader search terms
- verify the entry actually exists in the current dataset
- check related organization surfaces such as folders, tags, timeline, or media views

## Reminders or notifications are missing

- verify your device notification permissions
- verify in-app notification settings
- verify the reminder was actually saved on the entry

## I am unsure whether a feature is supported or just planned

Use [Project status]({{ site.baseurl }}/docs/wiki/project-status/) as the reference page. If the docs are unclear, open an issue so the wording can be corrected.
