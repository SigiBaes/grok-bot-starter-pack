# DELIVERY — seller checklist (after pay clears)

Use this for every `Paid €29` / `Paid €72` GitHub issue. Cap burn. Draft-only until the buyer says send.

## 0. Confirm pay

- [ ] Issue title is `Paid €29` or `Paid €72`
- [ ] Contact + buyer offer one-liner present
- [ ] Revolut.me amount matches SKU (honor system + issue timestamp; refund if we miss 24h)

## 1. Create the agent

- [ ] Create Grok Bot / Cursor agent named **Speed to Lead** (or buyer’s preferred name)
- [ ] Paste full body from `speed-to-lead/SYSTEM.md` into the agent description / standing instructions
- [ ] Set voice: terse closer; anti-jobs: never send without buyer’s exact yes

## 2. Skills

- [ ] Add / save skill from `speed-to-lead/skills/01-inbox-scan.md`
- [ ] Add / save skill from `speed-to-lead/skills/02-draft-reply.md`
- [ ] Add / save skill from `speed-to-lead/skills/03-payment-ask.md` (pay link: `https://revolut.me/sigiedn4xr` unless buyer supplies their own public pay link)

## 3. Qualify + routines

- [ ] Customize `speed-to-lead/qualify.md` to the **buyer’s** offer (replace placeholders)
- [ ] Propose routines from `speed-to-lead/routines.md` — **do not enable** until buyer confirms cadence

## 4. Connectors

- [ ] Guide buyer to connect **Gmail** (or their inbox connector) for the desk
- [ ] Confirm draft-only: no auto-send

## 5. First-wake

- [ ] Run [speed-to-lead/FIRST-WAKE.md](speed-to-lead/FIRST-WAKE.md) with the buyer (or on a sample thread)
- [ ] Paste a short sample draft transcript into the GitHub issue comment
- [ ] Confirm buyer sees where drafts land

## 6. €72 only — pack extras

- [ ] Install remaining personas from `personas/` the buyer wants
- [ ] One light tune pass (niche words in qualify + one skill example)

## 7. Close the issue

- [ ] Comment: delivered checklist + first-wake time (Brussels)
- [ ] If anything blocked on buyer (connector login), note it and pause the 24h clock until they reconnect

**Refund trigger:** steps 1–5 not done within 24h Brussels after a complete Paid issue → refund via Revolut.me.
