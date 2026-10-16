# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Expanded Personas and Role Interactions

To improve clarity, accountability, and handoffs, the following personas are proposed for inclusion. For each persona we provide a short responsibilities list and how they typically interact with existing roles.

1. Delivery Lead

Responsibilities
- Own day-to-day delivery cadence and sprint execution.
- Coordinate cross-team dependencies and maintain sprint commitments.
- Facilitate backlog grooming for in-sprint readiness and ensure stories meet DoD.
- Track capacity, impediments, and release readiness.

Interactions
- Works closely with Project Manager on scheduling and risk coordination.
- Partners with Product Manager to ensure scope aligns with sprint goals.
- Coordinates with Developers and QA on task breakdown and acceptance criteria.
- Escalates unresolved blockers to the PM or Product Lead.

Example deliverables: Sprint commitment plan, dependency tracker, daily delivery checkpoint notes.

2. Engineering Manager (EM)

Responsibilities
- Own team staffing, hiring priorities, and career development.
- Balance technical debt, architecture concerns, and delivery commitments.
- Support estimates and technical risk assessment.
- Conduct post-release technical reviews and promote engineering best practices.

Interactions
- Collaborates with Developers on capacity and technical feasibility.
- Works with Delivery Lead to align staffing to milestones.
- Communicates technical risks to PM and Product Lead for prioritization decisions.

Example deliverables: Capacity plans, technical risk register entries, staffing & growth plans.

3. UX / Product Designer

Responsibilities
- Lead user research, design, and prototyping for product features.
- Define UX acceptance criteria and accessibility requirements.
- Produce wireframes, mockups, and design specs for development.
- Validate UX changes during demos and post-release feedback cycles.

Interactions
- Partners with Product Manager to define user needs and success criteria.
- Works with Developers and QA to implement and test interaction details.
- Presents design decisions in sprint demos; incorporates stakeholder feedback.

Example deliverables: Wireframes, interaction specs, design review notes, usability test reports.

4. QA Lead / Test Architect

Responsibilities
- Define test strategy across unit, integration, and end-to-end testing.
- Ensure adequate test coverage and maintain automation tests for critical flows.
- Own release acceptance criteria and coordinate QA activities for releases.
- Maintain test data strategies and environment readiness.

Interactions
- Works with Developers to create acceptance tests and address regressions.
- Coordinates with Delivery Lead and PM on release readiness and QA timelines.
- Provides testing metrics to Product Manager and Data Analyst.

Example deliverables: Test strategy docs, automation coverage reports, release QA checklist.

5. Support Liaison / SRE Representative

Responsibilities
- Bridge product and operational concerns between engineering and support/on-call teams.
- Own runbook updates, deploy verification steps, and incident response coordination.
- Track operational KPIs and ensure observability/alerting coverage for releases.
- Lead post-incident blameless retrospectives and action tracking.

Interactions
- Works with Release Lead and PM during deployment planning.
- Collaborates with Developers on monitoring, alerts, and mitigations.
- Coordinates with Support to triage customer-impacting issues and maintain status comms.

Example deliverables: Runbooks, on-call handoff notes, incident postmortems, observability dashboards.

6. Data Analyst / Insights Partner

Responsibilities
- Define measurable success metrics and instrumentation requirements.
- Build dashboards and reports to track feature impact and product KPIs.
- Provide analysis to validate hypotheses and support prioritization.
- Advise on A/B measurement design and experiment results interpretation.

Interactions
- Works with Product Manager to define success criteria and dashboards.
- Provides data to PM and stakeholders during planning and retrospectives.
- Supports Developers and QA in validating telemetry and test metrics.

Example deliverables: Dashboards, metric definitions, experiment analysis, measurement plans.

Guidance for adding to docs
- For each persona in the document, include:
  - Responsibilities (short bullet list)
  - Typical touchpoints (who they collaborate with)
  - Escalation path (who they escalate to)
  - Example deliverables and success criteria
- Place this section in docs/octoacme-roles-and-personas.md under the heading "Expanded Personas and Role Interactions".
- Keep entries short (~5–8 bullets) and link to other process docs where appropriate (e.g., release checklist, risk register).
