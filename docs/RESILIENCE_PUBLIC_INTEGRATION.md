# Resilience Public Integration Standard

## Purpose

This document defines how Resilience Mode and Pure Street Resilience Services should be integrated into the STREETS / Pure Street ecosystem without turning the public site into inward-facing strategy notes.

The site must speak to residents, small businesses, corridor partners, grant writers, civic staff, foundations, and venture/impact investors. Internal reasoning, raw strategy, speculative technical language, and operational doctrine should remain in documentation, not public homepage copy.

---

## Primary public positioning

Pure Street should not present disaster preparedness as a separate emergency-response business.

Public-facing frame:

> Pure Street helps neighborhoods maintain cleaner, safer, more navigable public space before, during, and after environmental disruption.

Expanded public-facing frame:

> Pure Street Resilience Services help neighborhoods, business corridors, and community partners prepare for smoke, heat, storms, outages, earthquakes, flooding, and infrastructure disruption through preparedness education, environmental-condition documentation, resource mapping, corridor audits, and post-disruption cleanup support.

Funder-facing frame:

> Pure Street converts everyday public-space maintenance into climate resilience, public-health readiness, and neighborhood recovery capacity.

Technical/STREETS-facing frame:

> STREETS Resilience Mode adds offline-first condition reporting, resource mapping, preparedness resources, coordinator workflows, and disruption-aware documentation to the Environmental Sentinel Network.

---

## What must not appear as public-facing language

Avoid language that sounds like panic marketing, emergency cosplay, institutional overclaiming, or speculative survival tech.

Do not frame Resilience as:

- grid-down survival
- collapse readiness
- emergency command system
- community defense
- public safety replacement
- live tracking
- citizen monitoring
- private intelligence network
- emergency response business
- rescue, medical, evacuation, security, or public-safety operation

Avoid claims such as:

- We are disaster responders.
- We will protect people when the grid goes down.
- We operate emergency communications.
- We monitor vulnerable residents.
- Mesh networks will replace normal infrastructure.
- We provide rescue, medical care, evacuation, security, or official emergency services.

Use instead:

- preparedness education
- environmental hazard reduction
- offline civic reporting
- resource mapping
- neighborhood condition documentation
- cleanup and sanitation support
- corridor readiness
- post-disruption cleanup
- community coordination
- climate adaptation
- public-health resilience
- coordination with official emergency channels

---

## Required civic boundary

Every public Resilience page should include a concise version of this boundary:

> Pure Street supports official emergency systems. It does not replace 911, city emergency services, county alerts, fire response, medical care, evacuation orders, or public safety instructions.

This belongs on Resilience pages, resource pages, downloadable guides, and pilot/proposal pages. It should not dominate the homepage.

---

## Brand architecture

### 1. STREETS Resilience Mode

**Role:** software/intelligence layer.

**Route:** `/resilience-mode`

**Public purpose:**

STREETS Resilience Mode helps residents, field verifiers, corridor partners, and community organizations document disruption-related conditions, access preparedness resources, and maintain practical resource maps when normal infrastructure is strained.

**Feature set:**

- offline report drafts
- cached emergency/resource maps
- blocked-route and hazard notes
- resource checklists
- coordinator dashboards
- downloadable field guides
- future mesh-ready roadmap
- resilience-related report categories

### 2. Pure Street Resilience Services

**Role:** physical service and community operations layer.

**Route:** `/pure-street/resilience-services`

**Public purpose:**

Pure Street Resilience Services support neighborhoods and business corridors with preparedness education, corridor readiness audits, environmental-condition documentation, resource mapping, field verification, and post-disruption cleanup support.

**Service categories:**

- corridor readiness audits
- cleanup after storms/outages
- smoke/heat preparedness outreach
- debris and obstruction documentation
- neighborhood resource mapping
- field verification
- post-disruption sanitation support
- block captain / corridor partner training

### 3. STREETS + Pure Street Resilience Corridor Pilot

**Role:** city/funder-facing pilot package.

**Route:** `/proposals/resilience-corridor-pilot`

**Public purpose:**

The Resilience Corridor Pilot gives funders, cities, and corridor partners a practical 90-day deployment model with clear deliverables, budget bands, metrics, reporting cadence, and service boundaries.

---

## Navigation integration

Preferred tighter civic-tech navigation:

- Platform
- Cities
- Services
- Resilience
- Resources
- Pilots
- Contact

Alternate navigation:

- Home
- How It Works
- Cities
- Pure Street
- Environmental Intelligence
- Resilience Mode
- Resources
- Proposals
- Contact

Footer links:

- Resilience Mode
- Pure Street Resilience Services
- Emergency Field Guide
- Smoke & Heat Resources
- Corridor Readiness Audit
- Resilience Corridor Pilot

---

## Homepage integration

Do not turn the homepage into a disaster-preparedness page.

Add one polished section after the main STREETS explanation.

### Section title

Built for everyday conditions. Useful during disruption.

### Section copy

STREETS helps communities document illegal dumping, blocked sidewalks, biohazards, storm debris, smoke-day conditions, heat-related resource gaps, and corridor hazards. Pure Street extends that intelligence into field services, cleanup support, preparedness education, and neighborhood coordination.

### Cards

#### 1. Report conditions

Dumping, debris, blocked routes, biohazards, lighting issues, storm impacts.

#### 2. Map resources

Cooling centers, clean-air spaces, charging locations, water access, clinics, and community hubs.

#### 3. Coordinate locally

Block captains, corridor partners, volunteers, field verifiers, and service crews.

#### 4. Recover safely

Cleanup documentation, nonhazardous debris support, public-space restoration, and referral pathways.

### CTA buttons

- Explore Resilience Mode
- View Pure Street Services
- Download Field Guide

---

## STREETS platform integration

Resilience Mode should become a platform module, not a separate brand detached from STREETS.

### Suggested report categories

- Smoke / Air Quality Concern
- Extreme Heat / Cooling Access
- Power Outage Impact
- Blocked Road or Sidewalk
- Storm Drain / Flooding Concern
- Downed Tree or Debris
- Public Charging Need
- Water Access Need
- Clean-Air Resource
- Cooling Resource
- Vulnerable Corridor Condition
- Post-Storm Cleanup Need

### Suggested statuses

- Drafted Offline
- Needs Verification
- Verified Condition
- Routed to Official Channel
- Resource Confirmed
- Cleanup Eligible
- Partner Review Needed
- Resolved

### Resilience dashboard route

`/dashboard/resilience`

### Dashboard should show

- resilience-related condition reports
- resource map
- priority corridors
- unresolved blocked-access issues
- smoke/heat/outage notes
- coordinator checklist
- exportable summary packet

### Minimum offline-first UX

- Save report locally
- Add notes while offline
- Attach photo later
- Export as PDF/CSV
- Submit when online
- Download resource guide
- Cache key resource pages

Mesh networking should remain a future roadmap track unless implemented.

---

## Pure Street Resilience Services page

**Route:** `/pure-street/resilience-services`

### Hero headline

Pure Street Resilience Services

### Hero subheadline

Cleaner, safer, more navigable corridors before, during, and after disruption.

### Hero copy

Pure Street supports neighborhoods, business corridors, and community partners with preparedness education, corridor readiness audits, environmental-condition documentation, resource mapping, and post-disruption cleanup support.

### Service cards

#### Corridor Readiness Audit

Block-by-block review of dumping, debris, sidewalk access, storm drains, lighting, biohazards, and public-space risks.

#### Smoke & Heat Preparedness Support

Clean-air and cooling resource lists, printed guides, outreach materials, and resident-facing preparedness checklists.

#### Post-Disruption Cleanup

Nonhazardous debris removal, sanitation restoration, before/after documentation, and referral pathways for specialized hazards.

#### Resource Mapping

Cooling centers, clean-air rooms, libraries, charging sites, water access, clinics, community hubs, and partner locations.

#### Neighborhood Coordinator Support

Simple workflows for block captains, merchants, volunteers, faith groups, and community organizations.

#### STREETS Data Integration

Field conditions documented through the STREETS platform and summarized into public-facing or partner-facing reports.

### Boundary copy

Pure Street does not replace emergency services. Pure Street supports preparedness, documentation, cleanup, and resource coordination. Emergencies should always be directed to 911, official alerts, public agencies, and qualified responders.

---

## City page integration

Each city page should include a Resilience Conditions section tailored to local geography, risk, corridors, and public-space needs.

### Oakland

**Route:** `/oakland/resilience` or `/cities/oakland/resilience`

Focus areas:

- illegal dumping
- smoke days
- earthquake readiness
- storm drains
- encampment-adjacent sanitation without targeting people
- West Oakland truck corridors
- blocked sidewalks
- public-health cleanup

### Berkeley

**Route:** `/berkeley/resilience` or `/cities/berkeley/resilience`

Focus areas:

- hills fire risk
- students and renters
- cooling/clean-air sites
- neighborhood preparedness
- creek/stormwater issues
- Telegraph/Southside corridors

### Emeryville

**Route:** `/emeryville/resilience` or `/cities/emeryville/resilience`

Focus areas:

- dense mixed-use corridors
- flooding/sea-level exposure
- I-80/I-580 access issues
- business continuity
- pedestrian/bike access
- public-space cleanliness

### Richmond

**Route:** `/richmond/resilience` or `/cities/richmond/resilience`

Focus areas:

- refinery-adjacent environmental justice
- waterfront resilience
- multilingual outreach
- air quality
- industrial corridor conditions
- illegal dumping
- heat/smoke resources

### Hayward

**Route:** `/hayward/resilience` or `/cities/hayward/resilience`

Focus areas:

- industrial corridors
- hillside/fire interface
- renter-heavy neighborhoods
- storm debris
- transit access
- community resource mapping

---

## Resource library integration

**Route:** `/resources/resilience`

Include:

- STREETS Resilience Mode Field Guide
- 72-Hour Preparedness Checklist
- Smoke Day Checklist
- Extreme Heat Checklist
- Power Outage Checklist
- Earthquake Readiness Sheet
- Neighborhood Coordinator Checklist
- Ham Radio Beginner Guide
- Corridor Readiness Audit Template
- Post-Storm Cleanup Safety Sheet
- Resource Map Submission Form

Known existing resource path:

`/esn-resources/STREETS_Resilience_Mode_Field_Guide.pdf`

Build the resource hub around this existing downloadable guide.

---

## Funder/proposal integration

**Route:** `/proposals/resilience-corridor-pilot`

### Pilot title

STREETS + Pure Street Resilience Corridor Pilot

### Pilot scope

90 days. One corridor. Clear deliverables.

### Deliverables

- 1 corridor readiness audit
- 1 public resource map
- 150 documented conditions
- 50 verified priority hazards
- 4 community cleanup/service days
- 1 smoke/heat preparedness outreach packet
- 1 offline field guide distribution campaign
- 1 monthly dashboard
- 1 final resilience report

### Metrics

- hazards documented
- hazards resolved
- blocked access points cleared
- resource locations mapped
- residents reached
- businesses engaged
- cleanup hours completed
- official reports routed
- before/after evidence collected
- partner referrals made

### Budget bands

- $25,000 — Micro-pilot
- $50,000 — Corridor pilot
- $125,000 — Full 90-day city demonstration
- $250,000+ — Multi-corridor deployment

---

## Visual direction

Resilience Mode should feel related to STREETS but slightly more field-ready.

Use:

- darker environmental gradients
- map-grid backgrounds
- offline/cache icons
- field-guide cards
- resource map previews
- preparedness checklist components
- badge labels such as Offline Ready, Field Guide, Coordinator Mode, Resource Map

Avoid:

- apocalyptic imagery
- burning cities
- militarized visuals
- surveillance aesthetics
- panic language
- collapse branding

Visual tone:

> calm, civic, field-ready, data-informed, neighborhood-centered.

---

## Recommended file structure

```txt
src/pages/ResilienceMode.tsx
src/pages/PureStreetResilienceServices.tsx
src/pages/ResilienceCorridorPilot.tsx
src/pages/resources/ResilienceResources.tsx
src/components/resilience/ResilienceHero.tsx
src/components/resilience/CapabilityGrid.tsx
src/components/resilience/HamRadioCourse.tsx
src/components/resilience/FieldGuideDownload.tsx
src/components/resilience/PreparednessChecklists.tsx
src/components/resilience/ResilienceGuardrails.tsx
src/data/resilience.ts
public/esn-resources/STREETS_Resilience_Mode_Field_Guide.pdf
```

### Suggested routes

```tsx
<Route path="/resilience-mode" element={<ResilienceMode />} />
<Route path="/pure-street/resilience-services" element={<PureStreetResilienceServices />} />
<Route path="/proposals/resilience-corridor-pilot" element={<ResilienceCorridorPilot />} />
<Route path="/resources/resilience" element={<ResilienceResources />} />
```

### Suggested nav links

```tsx
<Link to="/resilience-mode">Resilience Mode</Link>
<Link to="/pure-street/resilience-services">Resilience Services</Link>
<Link to="/resources/resilience">Preparedness Resources</Link>
```

---

## Final public-facing model

The website should communicate this:

> STREETS sees and organizes the conditions. Pure Street acts on the conditions. Resilience Mode keeps the system useful when normal infrastructure is strained. The Resource Library teaches residents and partners what to do. The Pilot page gives funders and cities a concrete way to pay for deployment.

This turns resilience from a side idea into a disciplined business vertical: environmental maintenance plus climate resilience plus civic technology plus field operations.
