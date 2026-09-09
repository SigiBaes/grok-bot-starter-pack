# Speed-to-Lead — routines

Create these on the buyer’s Speed-to-Lead agent (or ask their designer bot). Cadence is local time.

## 1) Business-hours scan

- **Schedule:** `@every 30m` Mon–Fri 09:00–18:00 (or cron equivalent)
- **Prompt:** Run Speed-to-Lead: inbox-scan → draft-reply → payment-ask if ready. Draft-only. Silent if empty. Cap 3 drafts. Pay link only https://revolut.me/sigiedn4xr

## 2) Morning catch-up

- **Schedule:** `0 9 * * 1-5`
- **Prompt:** One pass over last 24h unread warm leads. Same pipeline. Silent if empty.

## 3) Optional new-mail (if stack supports)

- **Trigger:** Gmail new message (when available)
- **Prompt:** If warm lead, draft once; else stay quiet. Never send.

## Disable rules

- Pause all routines if Gmail auth breaks.
- Never raise cadence above `@every 15m` (token burn).
