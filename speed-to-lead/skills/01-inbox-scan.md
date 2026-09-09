# Skill: inbox-scan

**Use when:** waking Speed-to-Lead or running the inbox routine.

## Steps

1. Query authorized Gmail: unread or important, last 48h (narrower if flooded).
2. Drop obvious noise (noreply, receipts, CI, newsletters).
3. Rank remaining by buying intent.
4. Return ≤3 candidates: from, subject, 1-line why-warm, thread id/link.
5. Hand off to `draft-reply` skill. Silent if zero candidates.
