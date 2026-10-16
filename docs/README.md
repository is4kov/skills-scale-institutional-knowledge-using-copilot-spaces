# OctoAcme Project Management Docs

OctoAcme uses a lightweight, iterative project management approach focused on clear ownership, measurable outcomes, and continuous improvement. This docs/ README serves as the central index for process guidance and links to detailed playbooks for initiation, planning, execution, release, risk management, retrospectives, and roles.

Brief summary:
- Initiation with a Project One-pager to define the problem, objective, success metrics, and stakeholders.
- Planning that breaks approved initiatives into shippable increments with acceptance criteria, estimates, and a Definition of Done.
- Execution using a project board with clear states, small pull requests, CI checks, and regular demos and reviews.
- Risk management via a simple Risk Register and defined escalation paths; continuous improvement via retrospectives and tracked action items.

Key artifacts and links:
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

Overview of processes (summary)
OctoAcme follows an iterative, outcome-driven lifecycle: Initiation (create a one‑pager to validate the problem, stakeholders, and success metrics), Planning (kickoff, prioritized backlog, estimates, Definition of Done, and a release plan), Execution (deliver small, testable increments tracked on a project board), Release (pre-release checks, smoke tests, and rollback planning), and Close/Retrospective (capture learnings and convert them into backlog action items). Core artifacts — the Project One‑pager, Roadmap/Release Plan, backlog items with acceptance criteria, Risk Register, and retrospective action items — provide a single source of truth.

Workflows emphasize clear states and small, reviewable changes. Teams use a project board with columns such as Backlog 1 Ready 1 In Progress 1 In Review 1 QA 1 Done, and a consistent backlog-item template that includes acceptance criteria and estimates. The pull request workflow encourages small PRs (targeting 400 lines or fewer), requires an issue link and acceptance criteria in the PR description, and enforces CI checks (tests and linting) and at least one approval before merging. Planning is timeboxed and capacity-aware; items are pulled into work only when they meet the Definition of Done.

Roles and communication ensure alignment and accountability. Product Managers define outcomes and success metrics while Project Managers coordinate delivery and communications; Developers implement and test features and QA validates acceptance criteria. The communication cadence includes daily standups for blockers and progress, weekly delivery syncs, PM+PdM alignment meetings, sprint-end demos/reviews, and monthly stakeholder updates. QA practices require unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when needed. Pre-release checklists (passing CI/security scans, release notes, rollback plan), a maintained Risk Register, and structured retrospectives ensure releases are safe and that process improvements are tracked and measured.
