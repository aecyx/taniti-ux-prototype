# Guerrilla Usability Testing — Plan and Summary

This document contains the test plan, participant notes templates, and a consolidated summary marking which feedback is actionable and how it will influence the prototype.

## Test Plan (15–20 minutes per participant)
- Device: Mobile first (phone), optional desktop follow-ups
- Prototype: `prototype/index.html` (hosted via URL for remote testers)
- Script:
  1. Warm‑up: “You’re planning a trip to Taniti. Please think aloud.” (1 min)
  2. Tasks (unmoderated-style, facilitator present): (see Five Tasks in docs/usability-tasks.md)
  3. Debrief: One thing you liked, one thing that confused you. (2 min)
- Data captured: Success/failure, time to complete (rough), notes, quotes, severity

## Participant Notes Template
- Participant (A/B/C):
- Device/Browser:
- Tasks results:
  - T1:
  - T2:
  - T3:
  - T4:
  - T5:
- Quotes:
- Observations:
- Pain points & severity:

## Qualitative Feedback — Consolidated Summary (Example from 3 testers)
Note: Replace with your actual observations if you run new sessions. These examples are grounded in typical findings for this IA and content.

1) Navigation label “Plan Trip” not obvious for booking info (A,B)
- Actionable: Yes. Severity: Medium.
- Rationale: Users expected “Plan Trip” or “Book/Plan” to be a prominent button on Home and in the top nav. They missed it when it looked like a normal link.
- Change: Promote CTA styling and place above the fold; add synonyms in copy like “Plan Your Trip: Booking & Essentials.”

2) Ground transportation hours hard to find (A,C)
- Actionable: Yes. Severity: Medium.
- Rationale: Visitors need bus hours (5 a.m.–11 p.m.) and options quickly.
- Change: Add a “Getting Around” panel on Home with hours and icons; add anchors within page.

3) FAQ about alcohol hours / drinking age (B,C)
- Actionable: Yes. Severity: Low–Medium.
- Rationale: Common pre‑travel questions.
- Change: Add FAQs with alcohol hours (no sales 12:00 a.m.–9:00 a.m.) and drinking age (18, loosely enforced).

4) Wanted a concise “Top 5 Things To Do” (A)
- Actionable: Yes. Severity: Low.
- Rationale: Skimmers prefer curated list.
- Change: Add a featured list at the top of Explore.

5) Visual style feedback (contrast, spacing) (B)
- Actionable: Partially. Severity: Low.
- Rationale: Prototype is low‑fi; contrast/readability are in scope; brand polish is out of scope.
- Change: Ensure AA contrast and adequate spacing; defer branding.

6) Request for live booking inside site (C)
- Actionable: Not now. Severity: Out‑of‑scope.
- Rationale: Government site will link to providers; no direct transactions.
- Change: Provide clear “Book via partner” links.

## Implementation Plan (How feedback will be incorporated)
- Elevate “Plan Your Trip” to a primary CTA in header and hero.
- Add Getting Around quick facts to Home and a full section: buses (5 a.m.–11 p.m.), taxis, rentals, bikes/helmets.
- Add FAQs for alcohol hours, drinking age, currency/cards, power outlets, holidays closures, safety/health.
- Add a curated “Top 5 Things To Do” near the top of Explore.
- Keep links to booking providers clearly visible; no on‑site transactions.
- Improve contrast and spacing while remaining low‑fi.
