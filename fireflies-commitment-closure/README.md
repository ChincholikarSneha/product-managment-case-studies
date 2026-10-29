# Fireflies.ai — Commitment Closure

**Six-month target: Increase 14-day commitment resolution from 28% to 45%.**

[View Prototype](https://firefly-sparkle-view.lovable.app/)

> Independent product case study. Metrics are proposed targets, not achieved results. External integrations are not implemented in the prototype.

## 1. Executive Summary

### The Pitch
Commitment Closure helps teams turn meeting commitments into explicit outcomes through confirmed ownership, contextual reminders, and shared status. It extends Fireflies' existing experience while preserving user control.

### My Role
Research, product teardown, integration testing, prioritisation, requirements, experience design, prototyping, and success measurement.

## 2. Problem & Business Opportunity

Meeting commitments can lose ownership, timing, and status after being handed to external tools.

In my Fireflies–Asana test:
- Commitment text transferred without structured assignee or timing fields.
- External completion and reassignment did not update Fireflies.

This creates duplicate administration, stale information, and manual follow-up.

**Target users:**
- **Owners:** Execute work without duplicate updates.
- **Managers:** Prepare for meetings with current risks and outcomes.
- **Dependent coworkers:** Understand changes affecting their work.

**Business opportunity:** Reduce coordination effort and strengthen recurring team adoption.

## 3. Research, Prioritisation & MVP

### Research
Combined hands-on teardown, Asana integration testing, secondary manager research, community discussions, and alternative-workflow analysis.

**Key insight:** Capturing commitments is insufficient unless ownership, context, and outcomes remain reliable.

### Prioritisation
Used **RICE** to evaluate ideas. Prioritised the Closure Foundation before advanced intelligence because recommendations require trustworthy commitment state.

### MVP
- Confirmed ownership or Needs Confirmation.
- Due or review dates.
- Source meeting and transcript context.
- Done, accepted Reassignment, and Deliberately Dropped outcomes.
- Bundled reminders and relevant dependency updates.

**Excluded:** Project boards, sprint management, employee rankings, and automatic scheduling or assignment.

## 4. Solution & Execution

### Commitment Closure Foundation
Maintain one shared commitment state within existing Fireflies surfaces. Owners review context, update status, and explicitly close commitments.

Reassignment requires acceptance; deliberate dropping requires a reason.

### Role-Aware Intelligence
A subsequent layer explains deadline collisions and dependency risks, suggesting actions while leaving decisions to people.

### UX Artifact
[Explore the Lovable Prototype](https://firefly-sparkle-view.lovable.app/)

Production delivery would require design, engineering, and analytics collaboration around shared state, permissions, notifications, and measurement.

## 5. Impact & Metrics

### Primary Metric
**14-Day Honest Commitment Resolution Rate**

Valid commitments resolved as Done, accepted Reassignment, or Deliberately Dropped within 14 days ÷ all eligible valid commitments.

**Case baseline: 28% | Target: 45%**

### User Metrics
- Ownership confirmation within 24 hours.
- Meaningful owner action within 24 hours.
- Time to resolution.
- Follow-up effort.

### Business Metrics
- Team activation and recurring adoption.
- Workspace retention.
- Paid conversion and team expansion.

### Guardrails & Next Steps
Monitor incorrect ownership, unusual drops, reopened commitments, notification opt-outs, and trust concerns.

Next: validate shared state across roles and pilot with recurring cross-functional teams before measuring impact.

## 6. Tools & Methods

- **Lovable:** Concept prototyping.
- **Fireflies and Asana:** Product teardown and integration testing.
- **RICE:** Prioritisation.
- **Mini PRDs:** Requirements and acceptance criteria.
- **Lifecycle and stakeholder mapping:** Problem analysis.
- **Event and cohort metrics:** Proposed measurement plan.

Slack, Jira, and Calendar connectivity remain proposed production considerations.
