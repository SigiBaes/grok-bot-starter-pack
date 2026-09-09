# FIRST-WAKE — Speed-to-Lead (buyer-facing)

Run this **once** after install. Goal: prove the desk drafts (never sends) on a real or sample inbound.

## Before you start

1. Gmail (or inbox) connector connected.
2. Agent has `SYSTEM.md` + three skills loaded.
3. `qualify.md` matches **your** offer.
4. You have **not** given the bot permission to send mail.

## Script (say this to the bot)

> Scan my authorized inbox for warm leads in the last 14 days that match my qualify rules. Rank the top 3. For #1 only: draft a reply that answers their first questions and includes a soft payment ask with my public pay link (if I have one). **Do not send.** Show me the draft.

## What good looks like

- A ranked list (or “none found”) with one-line why.
- One draft reply in your voice, short enough to approve in one glance.
- Payment ask uses your own public pay link if you have one — **never IBAN / legal name in public drafts**.
- Bot stops without sending.

## Sample draft transcript (example)

```
Buyer bot: Top warm inbound (14d):
1. Alex — asked about AI inbox setup for their agency (Mon)
2. …

Draft for #1 (NOT sent):

Hey Alex — yes, we stand up a Speed-to-Lead desk on your Gmail: drafts in minutes, you tap send.
Two quick ones: (1) roughly how many inbound leads/week? (2) do you already use Grok Bot / Cursor agents?
If useful, I can adjust the qualify rules to your offer — drafts only until you say send.

You: looks good — I’ll send it myself.
```

## If nothing warm is in the inbox

Ask the bot to draft a **template** reply for a fictional lead matching `qualify.md`, still draft-only. That still counts as first-wake for DFY delivery.
