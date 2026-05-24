---
type: strategy
title: Automation Roadmap
status: developing
tags: [automation, ai, systems, workflow]
created: 2026-05-24
updated: 2026-05-24
---

# AUTOMATION_ROADMAP.md — AI & Automation Buildout

> Goal: use AI/automation to generate revenue, save time, and improve conversion — not
> for novelty. Automate the **repeatable, high-frequency, low-judgment** work first.

## Prioritization filter
Score each automation by: **(Time saved or Revenue gained) ÷ Effort to build**, and
whether it touches one of the 6 levers. Build highest-ROI first.

## Phase 1 — Capture & knowledge (this vault)
- [x] Second Brain vault structure + ingest loop.
- [ ] Frictionless capture: voice note / transcript → `/raw` → auto-summarize → `/wiki`.
- [ ] Weekly "what got smarter" digest from `LOG.md`.

## Phase 2 — Content engine
- [x] **ClickUp Content Pipeline LIVE** — "Content Pipeline" list in *Mortgage Content
  Marketing* (id `901416713938`), seeded with START-HERE + 6 batch-01 script tasks.
  Built 2026-05-24. (TODO: set board statuses in UI.)
- [ ] Transcript → hooks + scripts + captions (CONTENT_STRATEGY).
- [ ] Repurposing pipeline: 1 long-form → shorts/posts/email.
- [ ] Comment/DM mining → new objections into `/raw/objections`.

## Phase 3 — Lead response & nurture
- [ ] Speed-to-lead auto-response (< 5 min).
- [ ] AI intake/qualification → route to right track.
- [ ] Automated nurture sequences by segment (FTB, reverse, investor).

## Phase 4 — Sales support
- [ ] Pre-call briefs (pull client scenario + likely objections).
- [ ] Post-call notes → CRM + `/raw/call_notes` auto-filed.
- [ ] Follow-up reminders + draft messages.

## Phase 5 — Partner systems
- [ ] Realtor/builder update automations (deal status → make John look great).
- [ ] Co-marketing asset generation on demand.

## Tooling inventory (confirmed 2026-05-24)
| Function | Tool | Status |
|---|---|---|
| CRM / pipeline | **Salesforce** | active — fire referral/review triggers off loan-status changes |
| Ops / project mgmt | **ClickUp** | active — **Claude has direct ClickUp access (MCP)** |
| Content/scheduling | `TODO` | |
| Automation (Zapier/Make/n8n) | `TODO` | |
| Transcription | `TODO` | |
| AI assistant | Claude Code (this) | active |

### Integration opportunities (high-leverage)
- **ClickUp (direct):** build a "Referral & Review Engine" with recurring task triggers at
  funding/closing/30-day/anniversary (from [[wiki/sales_systems/referral-ask-system]]);
  track a database-reactivation campaign as a ClickUp list. _Needs John's OK + a look at
  his workspace before creating anything._
- **Salesforce:** Flow/automation to auto-create the referral + review ask task when a loan
  hits "funded"; tag + report referral sources for [[LEAD_GENERATION.md]].

## Open questions for John
1. What repetitive task eats the most of your time each week?
2. What tools are already in your stack (CRM, scheduler, etc.)?
3. Where do leads/deals leak due to slow or missed follow-up?

Related: [[LEAD_GENERATION.md]] · [[CONTENT_STRATEGY.md]] · [[SALES_SYSTEM.md]]
