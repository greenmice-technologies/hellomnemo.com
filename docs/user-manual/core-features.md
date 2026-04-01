---
layout: default
title: Core Features
parent: User Manual
nav_order: 2
---

# Core Features

Mnemo is built around one idea: personal memory should stay connected to its context.

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

Current supported behavior is centered on local persistence.

- the primary dataset is stored as `data.json`
- media is stored alongside the dataset
- ZIP import/export exists for portability and backup

Cloud sync is not yet the documented baseline behavior for end users.

## What is changing next

The next strategic steps are:

1. backend-backed account creation and sign-in
2. cloud sync for data and media continuity
3. stronger support for Flutter Web once sync exists

Until those steps ship, this manual should describe the app as local-first.
