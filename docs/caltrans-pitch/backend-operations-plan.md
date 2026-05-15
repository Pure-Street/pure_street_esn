# ESN Backend Operations Plan

Prepared for Pure Street / Environmental Sentinel Network (ESN)

## Purpose
This document defines the practical backend work required to operate ESN during an agency pilot. It prevents the pilot from becoming an unbounded obligation and helps Pure Street price, staff, and scope the work responsibly.

## Operating Principle
ESN is not only a website or app. It is an operating system combining software, field verification, data quality, reporting, partner coordination, and public communications.

## Core Backend Workstreams

### 1. Product Administration
Tasks:

- Maintain public Caltrans pilot page
- Update download center documents
- Update dashboard screenshots and demo assets
- Maintain issue categories and labels
- Manage public disclaimers
- Keep agency-facing language current

Estimated effort:

- Lean pilot: 2-4 hours/week
- Standard pilot: 4-8 hours/week
- Full demonstration: 8-15 hours/week

### 2. Data Intake and Quality Control
Tasks:

- Review submitted hazard reports
- Check for duplicates
- Confirm location accuracy
- Clean category labels
- Identify missing information
- Flag urgent or unclear submissions
- Remove unusable or inappropriate submissions

Estimated effort:

- Lean pilot: 3-6 hours/week
- Standard pilot: 8-15 hours/week
- Full demonstration: 20+ hours/week or dedicated operator

### 3. Field Verification Coordination
Tasks:

- Assign verification tasks
- Track verifier safety and completion
- Confirm status updates
- Review before/after evidence
- Maintain verification confidence levels
- Escalate high-risk issues through proper channels

Estimated effort:

- Lean pilot: 3-6 hours/week
- Standard pilot: 8-20 hours/week
- Full demonstration: field manager required

### 4. Agency Coordination
Tasks:

- Prepare weekly agency summaries
- Track agency feedback
- Document meeting notes
- Manage requests for revisions
- Clarify jurisdiction and routing questions
- Maintain the disclosure log

Estimated effort:

- Lean pilot: 2-4 hours/week
- Standard pilot: 5-10 hours/week
- Full demonstration: 10-20 hours/week

### 5. Reporting and Evaluation
Tasks:

- Generate monthly impact reports
- Update metrics tables
- Prepare charts
- Summarize unresolved hazard age
- Track recurring hotspots
- Draft final evaluation report
- Translate findings into expansion recommendations

Estimated effort:

- Lean pilot: 4-8 hours/month
- Standard pilot: 10-25 hours/month
- Full demonstration: evaluator or analyst required

### 6. Document Control
Tasks:

- Maintain version numbers
- Update PDF exports
- Track draft/internal/final status
- Maintain source documents in GitHub
- Ensure public materials do not overclaim agency partnership
- Preserve dated records of what was shared

Estimated effort:

- Lean pilot: 1-2 hours/week
- Standard pilot: 2-4 hours/week
- Full demonstration: 5+ hours/week

### 7. Communications and Public Updates
Tasks:

- Prepare public impact updates
- Draft agency-safe website language
- Create social posts only after agency review where needed
- Avoid implying endorsement before formal agreement
- Maintain careful tone around public infrastructure and sensitive locations

Estimated effort:

- Lean pilot: 1-3 hours/week
- Standard pilot: 3-6 hours/week
- Full demonstration: communications lead recommended

## Minimum Team Model

### Lean Pilot
Can be run by founder plus occasional field support.

Suggested roles:

- Founder / project lead
- Part-time verifier
- Part-time design/document support

### Standard Pilot
Requires a small operating cell.

Suggested roles:

- Project lead
- Data/reporting operator
- Field verification coordinator
- 2-5 trained verifiers
- Design/document support

### Full Demonstration
Requires a structured team.

Suggested roles:

- Program manager
- Product/admin operator
- Data analyst
- Field operations lead
- Verification team
- Community/partner coordinator
- Evaluation/reporting lead
- Legal/compliance support

## Weekly Operating Rhythm

### Monday
- Review open hazards
- Prioritize verification list
- Check dashboard accuracy
- Send internal plan

### Tuesday-Wednesday
- Field verification
- Data cleanup
- Partner coordination

### Thursday
- Generate interim status summary
- Check unresolved hazard age
- Prepare agency notes

### Friday
- Send weekly summary
- Archive shared materials
- Update disclosure log
- Plan next week

## Monthly Deliverables

- Monthly impact report
- Updated dashboard snapshot
- unresolved hazard report
- repeat hotspot summary
- partner action summary
- document-control update
- risk/compliance update

## Backend Tools Needed

### Essential
- GitHub
- Lovable or Vercel-hosted site
- Canva or slide tool
- Google Drive or equivalent document storage
- spreadsheet or database
- form intake tool
- PDF export workflow

### Recommended
- Supabase or PostgreSQL for structured reports
- Mapbox or Leaflet for corridor mapping
- Airtable or Notion for operations tracking
- Loom or similar for walkthrough videos
- GitHub Issues or Linear for internal tasks
- Gitleaks or secret scanning for security
- basic analytics for page/document usage

## Data Fields for ESN-Lite

Minimum hazard report fields:

- report ID
- date/time
- location
- corridor
- issue category
- severity
- description
- photo/video reference
- reporter type
- verification status
- verifier notes
- resolution status
- agency/partner routing
- last updated
- public/private visibility flag

## Quality-Control Rules

- Every public metric should be traceable to source records.
- Every agency-facing document should have a version number.
- Every screenshot should use sample, staged, or approved data unless otherwise authorized.
- Every public claim should be reviewable and defensible.
- No public page should imply a formal partnership before one exists.

## Workload Warning
A serious ESN pilot can easily become a full-time workload. If Pure Street accepts a standard or full pilot, pricing must include founder/project management time, data operations, document production, field verification coordination, and reporting.

Do not treat backend work as invisible free labor. It is the operational core of ESN.
