---
name: mkt-scheduler
description: Schedule and publish posts across YouTube, Instagram, Facebook, LinkedIn, X, Threads, Pinterest, Google Business Profile and email from the content calendar — native formatting per platform, best times, queues, approval and publishing logs. Use when the user says "schedule my posts", "auto post", "publish to all platforms", "cross-post", or runs a weekly publishing batch.
---

# Cross-platform scheduling and publishing

## Before scheduling
- Content approved in the calendar (`mkt-content-calendar`).
- Platform-native versions: separate captions, sizes, hashtags/keywords, no watermarks; links placed per platform rules (first comment on LinkedIn/Facebook, bio/link stickers on Instagram).
- Accessibility: captions on video, alt text on images.

## Times
Use each account's own analytics for when followers are active; otherwise start with the audience's local lunch and evening hours and test. Avoid posting identical content on all platforms at the same minute.

## Publish methods (in order)
1. Connected official integration (YouTube, Facebook Pages, Instagram, LinkedIn, X, Pinterest, GBP, email tool).
2. A connected scheduler tool (e.g. Buffer, Later, Metricool, Publer) if the user uses one.
3. Native schedulers (YouTube Studio, Meta Business Suite) via the bot's logged-in browser session.

## Approval modes
- **Default**: queue drafts → user approves batch → schedule.
- **Auto-publish**: only for series the user explicitly approved (e.g. daily tip Shorts), still respecting `mkt-approvals-safety`.

## Log
Date/time | platform | post | URL | status | 24h results — written back to the calendar.
