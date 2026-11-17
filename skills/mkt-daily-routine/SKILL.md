---
name: mkt-daily-routine
description: Set up and run hands-free daily, weekly and monthly marketing routines for a Rakazo bot — morning brief, content drafting, scheduling, engagement, reviews, trend scan, weekly report and monthly plan — with one approval batch per day. Use when the user says "automate my marketing", "hands-free marketing", "daily marketing routine", "marketing bot", or wants recurring marketing tasks.
---

# Hands-free marketing routines

## Setup (once)
1. `mkt-brand-context` and `mkt-content-strategy` saved.
2. Accounts connected (`mkt-connect-accounts`).
3. Ask: time zone, working days, approval mode (batch approval default; list any auto-approved categories), daily time the user can spend (e.g. 15 minutes for approvals + 20 minutes recording).
4. Create the routines below in Rakazo ("add this to a routine").

## Daily — morning (e.g. 9:00)
1. Pull yesterday's results and new comments/DMs/reviews.
2. Draft replies (`mkt-auto-engagement`, `mkt-reviews`).
3. Check today's calendar posts are ready; draft missing captions; prepare Stories frames (`mkt-instagram-stories`).
4. Quick trend scan (`mkt-trends`) — suggest 0–1 timely post.
5. Send ONE approval message:
   `📅 Today's posts (n) · 💬 Replies (n) · ⭐ Reviews (n) · 🔥 Trend idea · 🎥 What to record today (script)`
6. Publish/schedule approved items (`mkt-scheduler`); log.

## Daily — evening
Reply round 2; log leads; note what to record tomorrow.

## Weekly (e.g. Monday)
Analytics report (`mkt-analytics-report`) → plan next week's calendar (`mkt-content-calendar`) → batch scripts (`mkt-short-video-script`) → newsletter draft (`mkt-newsletter`) → GBP post (`mkt-local-seo`) → collab outreach drafts (`mkt-collaborations`).

## Monthly
Strategy review, experiments results (`mkt-experiments`), competitor check (`mkt-competitor-watch`), SEO/AI visibility check (`mkt-ai-search-geo`).

## Rules
If a connection fails, report it in the brief; don't retry endlessly. Follow `mkt-approvals-safety` and `mkt-platform-rules` always.
