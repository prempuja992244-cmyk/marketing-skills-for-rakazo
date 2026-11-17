---
name: mkt-dm-automation
description: Turn comments and DMs into leads with keyword auto-replies and conversation flows on Instagram, Facebook Messenger and WhatsApp — "comment WORD to get the guide", FAQ replies, lead capture and handoff. Use when the user asks for "DM automation", "auto reply to comments", "comment to DM", "Messenger bot", or "send the link when people comment".
---

# Comment-to-DM and DM automation

## Use cases
- "Comment **GUIDE** and I'll DM you the checklist" → auto DM with link.
- FAQ replies: price, location, delivery, timing, sizes.
- Lead capture: ask name, need, city → save to sheet/CRM → notify the user.

## Flow design
1. **Trigger**: keyword in a comment on a specific post, or keyword DM, or story reply.
2. **Public reply** (optional): short friendly reply under the comment ("Sent! Check your DMs 📩").
3. **DM 1**: thank + deliver the promised item + 1 question.
4. **DM 2 (on reply)**: qualify (need, timeline) and offer the next step (book, order, WhatsApp).
5. **Handoff**: anything unusual → human (`mkt-approvals-safety`).

## Tools
Use the platform's official messaging/automation features or an approved integration connected in Rakazo (Meta-approved tools, WhatsApp Business). The bot drafts flows and reply texts; it does not run unofficial bots on the user's account.

## Rules
- Respect platform messaging windows and policies (Meta limits automated messages outside 24-hour windows to approved templates).
- Only message people who engaged first; honour "stop".
- Keep a log of leads with source post.
