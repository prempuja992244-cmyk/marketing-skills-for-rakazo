---
name: mkt-email-deliverability
description: Make marketing emails reach the inbox and meet Gmail/Yahoo sender rules — SPF, DKIM, DMARC, one-click unsubscribe, spam-complaint rate, list hygiene, warm sending. Use when the user asks "emails going to spam", "Gmail sender requirements", "set up my domain for email", or before sending newsletters.
---

# Email deliverability (Gmail and Yahoo rules)

## Requirements (as published and enforced by Google/Yahoo)
- **Authentication**: SPF and DKIM; bulk senders (around 5,000+ messages/day to Gmail) also need DMARC (at least `p=none`) aligned with the From domain.
- **One-click unsubscribe**: marketing mail needs RFC 8058 List-Unsubscribe headers plus a visible unsubscribe link; process requests within 2 days.
- **Spam complaints**: keep Gmail user-reported spam rate below 0.1% and never reach 0.3%.
- Valid forward/reverse DNS, TLS, proper message formatting, no impersonating Gmail From addresses.

## Practical setup
1. Send from your own domain (not @gmail.com) through an email service that handles headers and unsubscribes.
2. Add SPF, DKIM, DMARC records (prepare exact records; the user/IT applies them or approves the change).
3. Register the domain in Google Postmaster Tools to watch spam rate and reputation.
4. Warm up new domains with small, engaged segments first.

## Habits
Send only to opted-in contacts; remove bounces and long-inactive subscribers; make unsubscribe easy; consistent schedule; avoid heavy images/link-only emails; encourage replies.

## Check routine (weekly)
Spam rate, bounce rate, unsubscribe rate, open/click trend, blacklist check. If spam rate rises, pause and investigate before the next send.
