---
type: strategy
title: Database Reactivation Campaign
status: developing
tags: [leads, database, past-clients, reactivation, referrals]
sources: ["[[wiki/syntheses/lead-strategy-scale-referrals-first]]"]
related: ["[[LEAD_GENERATION.md]]", "[[wiki/sales_systems/referral-ask-system]]", "[[wiki/sales_systems/review-generation-system]]", "[[AUTOMATION_ROADMAP.md]]"]
created: 2026-05-24
updated: 2026-05-24
---

# Database Reactivation Campaign

**Objective (lever):** Leads + Revenue. Mine the database John **already owns** for the
fastest qualified-lead volume — repeat business, referrals, and reviews.

**Why:** His best clients are referrals, and the warmest, cheapest pipeline is the people
who already know and trust him. Most LOs let this asset go cold. Reactivating it is the
single fastest lead win — no ad spend, no new audience.

## Step 1 — Segment the database (in Salesforce)
| Segment | Who | Primary angle |
|---|---|---|
| **Past clients (funded)** | Closed loans | Referral ask + annual review + reviews |
| **Stalled / never-closed** | Pre-approved but didn't buy | "Still want to own? Let's revisit." |
| **Old leads** | Inquired, went cold | Re-engage with value (DPA/market) |
| **Sphere / personal** | Friends, family, network | Soft "here's what I do" + referral |
| **Partners** | Realtors/builders | Separate track → [[wiki/realtor_systems/realtor-referral-framework]] |

→ `TODO: get counts per segment from John` to scope effort + expected return.

## Step 2 — Pick value-first reasons to reach out
Never lead with "send me referrals." Lead with **something useful**:
- **Annual mortgage review** (equity/rate/term check — compliant, no promises).
- **Home value update** ("want your current estimated value?").
- **Market update** specific to Santa Clarita / LA.
- **Program news** (new DPA / first-time-buyer options — `TODO: verify` before sending).
- **Life-event check-in** (move-up, refi, HELOC, helping a kid buy).

## Step 3 — The multi-touch sequence (example, 30 days)
> Tone: human, helpful, zero pressure. Brackets = personalize. Tune channel to segment.

1. **Touch 1 — Email (value):** "Quick equity + rate check-in for [Name]" — offer the
   annual review, no ask.
2. **Touch 2 — Text (3–4 days):** "Hey [Name]! Sent you a note — want me to run your
   home's current value + see if a review makes sense? No pressure either way."
3. **Touch 3 — Call (1 week):** personal check-in; if it lands, schedule the review.
4. **Touch 4 — Value email (2 weeks):** market update / program news.
5. **Touch 5 — Referral ask (3–4 weeks):** use [[wiki/sales_systems/referral-ask-system]]
   ("who do you know who's renting but would love to own?").
- Anyone who engages → personal follow-up; anyone who closes → review ask.

## Step 4 — Capture + route
- Every reply/booking logged in Salesforce with a **source tag** ("reactivation").
- Hot responses → discovery call ([[SALES_SYSTEM.md]]).
- Build the campaign as a ClickUp list of touches/tasks (see [[AUTOMATION_ROADMAP.md]]).

## Metrics
- Contacts attempted · reply rate · reviews/calls booked · referrals generated ·
  reactivated deals (refi/move-up/HELOC) · cost ≈ $0.

## Compliance notes
- Equity/rate "reviews": discuss options, **no guarantees**; mark any rate/term `TODO: verify`.
- Honor Do-Not-Contact / TCPA for texts + calls (consent for marketing texts). `TODO: verify`
  current consent status of the list before bulk texting.
- Referral asks to clients = fine; no compensation that triggers RESPA Section 8.

## Build next
- Draft the actual email/text copy per segment → `/wiki/scripts`.
- Stand up the campaign in Salesforce/ClickUp once segments are counted.
