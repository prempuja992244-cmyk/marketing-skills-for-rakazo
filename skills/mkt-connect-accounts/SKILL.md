---
name: mkt-connect-accounts
description: Connect Gmail, YouTube, Instagram, Facebook Pages, LinkedIn, X, Pinterest, WhatsApp Business, Google Business Profile, Search Console, Sheets and design tools to the Rakazo bot safely — official integrations first, one-time browser login second — so automation runs hands-free without sharing passwords. Use when the user asks "auto login", "connect my accounts", "give the bot access to YouTube/Gmail/Facebook", or a skill reports a missing connection.
---

# Connect accounts (hands-free without sharing passwords)

The bot never stores or types the user's passwords. Hands-free automation comes from connections that stay signed in.

## Option 1 — Integrations (best)
In Rakazo open **Integrations** and connect via OAuth (Composio / Pipedream Connect or an MCP server). The user signs in on the official page once; the bot then acts through the platform's API within the permissions granted.
Typical toolkits: Gmail, Google Calendar, Google Sheets/Drive/Docs, YouTube, Instagram (Business/Creator), Facebook Pages, LinkedIn, X, Pinterest, Google Business Profile, Search Console, Mailchimp/Brevo, WhatsApp Business, Canva, Notion.

## Option 2 — Bot computer, one-time login
For tasks with no API (some Story features, Channels, groups), the user logs in once on the bot's computer browser using Rakazo's **Protected input** so the password isn't recorded. The session stays signed in for future routines. The bot pauses and asks the user if a login, 2-step code or CAPTCHA appears — it never solves CAPTCHAs or bypasses security.

## Setup flow
1. List the channels from `brand-context.md`.
2. For each: check if a connection exists; if not, tell the user exactly which integration to connect and the minimum permissions needed.
3. Test with a harmless read action (list recent posts/emails).
4. Record status in `connections.md` (channel | method | permissions | tested date).

## Rules
Never ask for passwords in chat; never share credentials between accounts; use Business/Creator accounts where APIs require them; revoke access the user no longer wants.
