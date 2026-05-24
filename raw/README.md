# /raw — Source-of-Truth Inputs (IMMUTABLE)

> Drop raw material here. **Never overwrite or rewrite** a raw file's original content.
> Each raw file gets summarized + extracted into `/wiki`. See [[CLAUDE.md]] §2.

When you add a raw file, also add a short header (use `templates/raw_ingest.md`) and then
ask Claude to process it (summarize → extract → link → update INDEX + LOG).

## What goes in each subfolder

| Folder | Put here |
|---|---|
| `assets/` | Images, PDFs, screenshots, downloads, misc binaries |
| `transcripts/` | Video/podcast/webinar/content transcripts |
| `emails/` | Important email threads |
| `call_notes/` | Notes from calls (client, partner, lender) |
| `client_scenarios/` | Real (anonymized) borrower scenarios |
| `loan_programs/` | Program details, guidelines, matrices (mark unverified `TODO: verify`) |
| `builder_projects/` | Builder communities, projects, contacts |
| `realtor_relationships/` | Realtor partner notes + interactions |
| `reverse_mortgage/` | Reverse-specific notes, scripts, objections |
| `dpa/` | Down payment assistance programs + notes |
| `marketing/` | Marketing assets, plans, results |
| `social_content/` | Captions, posts, performance, scripts |
| `competitors/` | Competitor content + positioning |
| `market_research/` | Local market data, trends |
| `automation_systems/` | Workflow docs, automation specs/exports |
| `voice_notes/` | Voice memos + their transcripts |
| `crm_exports/` | CRM data exports (SENSITIVE — anonymize before reuse) |
| `case_studies/` | Detailed client win write-ups |
| `objections/` | Raw objections heard from buyers/partners |
| `underwriting/` | Underwriting edge cases + lessons |
| `sales_training/` | Sales training material + notes |
| `role_models/` | Source material from mentors (Hormozi, Miner, etc.) |

## Naming
- Prefix time-bound files with date: `2026-05-24-<slug>.md`
- Lowercase, hyphen/underscore separated, descriptive.
- Sensitive client data: anonymize before anything becomes public-facing.
