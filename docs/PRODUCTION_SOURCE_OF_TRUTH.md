# Production Source of Truth Before Redesign

## Purpose

Before redesigning `oaklandstreets.live`, confirm the production source of truth so STREETS / Pure Street work is not overwritten, fragmented, or lost.

The public website must become a polished civic-tech product, not an online notebook. At the same time, all prior strategy, grant language, architecture notes, pivots, blog concepts, city plans, legal caution, and feature inventory should be preserved privately as archive/reference material.

## Core principle

**Do not delete or overwrite anything until the production repo, branch, and deployment path are confirmed.**

The public site should be a **showroom, not a storage room**.

---

## Required confirmation

Confirm the following before any redesign merge:

- [ ] Which repo is currently connected to Vercel for `oaklandstreets.live`
- [ ] Which branch deploys to production
- [ ] Whether this repo is the active integrated production codebase
- [ ] Whether `MysticQuestion/sentinel-civic-heart` is historical, active, or reference-only
- [ ] Whether `MysticQuestion/Pure-Street-ESN`, `MysticQuestion/pure_street_esn`, and `MysticQuestion/ESN-Oakland` are archive/reference repos
- [ ] Current production deployment URL
- [ ] Current preview deployment URL, if any
- [ ] Build command, framework, and environment variables required for deployment
- [ ] Current source of homepage copy and core route structure
- [ ] Current source of dashboard/reporting components

---

## Repository strategy

### 1. Production site

Purpose: beautiful public-facing STREETS site.

Should contain only:

- polished homepage
- Oakland pilot
- dashboard preview
- report/documentation flow
- Pure Street services
- partner/funder CTA
- STREETS Dispatch
- methodology/privacy pages
- limited official-report guidance

Should **not** contain:

- raw strategy dumps
- repeated disclaimers
- giant internal notes
- every possible future feature
- speculative API/security claims presented as current infrastructure
- unverified claims of municipal authority, formal city partnership, deployed sensors, or agency integration

### 2. Archive / knowledge base

Purpose: preserve all ideas and reference material.

Move or preserve in `/docs/archive` or equivalent:

- old pivots
- grant language
- funder packet drafts
- legal caution language
- city-specific plans
- ESN architecture notes
- blog concepts
- feature inventory
- partner lists
- internal roadmap notes
- speculative future API/security architecture

### 3. Funder packet

Purpose: curated 6–8 page PDF or page for Crankstart, city staff, foundations, and corridor partners.

This should be separate from the public website and should not overload the homepage.

### 4. Internal roadmap

Purpose: what gets built next.

Include:

- feature inventory
- integration plan
- compliance checklist
- partner tracker
- pilot metrics
- blog pipeline
- funding pipeline

---

## Public site rule

A page belongs on `oaklandstreets.live` only if it helps one of these audiences act:

- A resident can document a condition.
- A small business can request or support corridor care.
- A funder can understand the pilot.
- A city/county staffer can see STREETS is complementary and disciplined.
- A partner can offer a corridor, intro, equipment, data, or support.
- A journalist can understand the model in 90 seconds.

Everything else belongs in the archive or internal documentation.

---

## Public site product standard

The homepage should feel like:

> STREETS helps Oakland see recurring street conditions clearly enough to act on them.

Then immediately prove it with:

- live/prototype dashboard preview
- report categories
- sample condition report
- Oakland pilot card
- Pure Street action layer
- partner CTA
- metrics cards
- before/after documentation placeholder
- STREETS Dispatch articles

---

## Redesign standard after source confirmation

Once the source of truth is confirmed, redesign the public site around this ratio:

- 80% proof of value
- 15% methodology
- 5% disclaimer

The site should lead with benefit, show the workflow, demonstrate the pilot, make Pure Street’s service layer tangible, and keep legal caution visible but contained.

---

## Public positioning guardrails

Use:

- independent civic intelligence layer
- corridor documentation platform
- pilot-stage civic-tech product
- Pure Street action layer
- structured evidence for cleanup, prevention, funding, and accountability
- resident reports, field observations, public data, and future sensor inputs

Avoid unless formally true:

- official City of Oakland service
- municipal cleaning agency
- formal city partner
- automated municipal dispatch
- zero human delay
- deployed ESN sensors
- public API availability
- immutable ledger database
- guaranteed cleanup
- guaranteed agency response
- enforcement targeting

---

## Related work

A detailed site repositioning issue exists in `MysticQuestion/sentinel-civic-heart` as Issue #17. Do not assume that repo is production until this checklist confirms source of truth.
