# Grok Bot Starter Pack

Copy-paste ready **one-job** Grok Bot personas. Draft-only where it matters (no silent sends). Useful on day one.

**Live product.** Personas work without any payment. Optional paid setup help is listed at the bottom (live Revolut link); nothing here blocks on humans.

## What's inside

| Persona | Job | Mode |
|---------|-----|------|
| [Speed-to-Lead Draft Desk](personas/speed-to-lead-draft-desk.md) | Warm inbound → reply draft in minutes | Draft only |
| [Inbox Triage Desk](personas/inbox-triage-draft-only.md) | Label + summarize + draft replies | Draft only |
| [Found-Money Scanner](personas/found-money-scanner-draft-only.md) | Spot refunds / unused subs / credits | Draft only |
| [Content Scout](personas/content-scout.md) | Find angles worth posting | Research + outline |

## Install (Grok Bot / Cursor agents)

1. Open Grok Bot → create a new agent (or ask your designer bot).
2. Paste the **Title**, **Description**, and full **System / persona** block from one file in `personas/`.
3. Connect only the connectors listed in that file (usually Gmail or X — start with one).
4. Run the **First wake** checklist once. Confirm drafts land where you expect before any send permission.
5. Optional: save recurring checks as a Routine (cadence in each file).

### Quick create via CreateAgent

If you already have a bot that can call `CreateAgent`, give it the persona file and say: create this agent with this name and description, paste the body as the agent description / standing instructions.

## Safety defaults (all draft desks)

- **Never send** email, Slack, or social posts unless the human explicitly says "send it".
- Prefer short drafts the human can approve in one glance.
- Cap token burn: one connector, narrow query, stop when the brief is done.
- No new KYC / Stripe / Whop from these bots.

## License

MIT — use, fork, sell setups. Attribution appreciated, not required.

---

## Optional: paid setup help

If you want someone to install + tune these bots for you:

- **€29** — install one persona + first-wake check  
- **€72** — full pack install + light customization  

### Card / peer (Revolut)

[revolut.me/sigiedn4xr](https://revolut.me/sigiedn4xr)

### Bank / Wise transfer (EUR)

| | |
|---|---|
| Beneficiary | Sigi Edward R Baes |
| IBAN | `BE35 6501 9555 3037` |
| BIC | `REVOBEB2` |
| Correspondent BIC | `CHASDEFX` |

Product above works without paying.
