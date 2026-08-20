# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management framework. This documentation provides comprehensive guidance on how we run projects, from initiation through retrospective and continuous improvement.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction to our roles, artifacts, and lifecycle.

## OctoAcme Project Management Overview

OctoAcme follows a structured, five-phase project lifecycle that emphasizes customer value, iterative delivery, and data-informed decision-making. Beginning with Initiation—where business needs are validated through a lightweight Project One-pager and stakeholder alignment—projects move into Planning, where work is broken into shippable increments with clear acceptance criteria and a defined Definition of Done. The Execution phase focuses on daily delivery management with structured team rhythms (daily standups, weekly delivery syncs), while the Release phase ensures standardized, low-risk deployments to production. Finally, the Close & Retrospective phase captures learnings and converts them into continuous improvements. Throughout all phases, OctoAcme prioritizes psychological safety, clear ownership, and transparent communication.

OctoAcme operates with clearly defined roles that enable efficient cross-functional collaboration. The Product Manager (PdM) defines outcomes, prioritizes the backlog, and measures success through data-driven metrics. The Project Manager (PM) coordinates delivery activities, manages risks and dependencies, and ensures transparent communication across stakeholders. Developers implement features, write tests, and participate in design and code reviews, while QA/Testing validates quality and acceptance criteria. This role clarity eliminates ambiguity and ensures each person understands their contribution to project success. Regular synchronization—weekly PM-PdM alignment, twice-weekly standups, and monthly stakeholder updates—maintains alignment across the organization.

Quality is embedded throughout OctoAcme's execution workflow rather than treated as an afterthought. The process mandates unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Automated testing and linting run in CI before PR reviews, with a requirement for at least one approval before merging. Beyond testing, OctoAcme maintains a formal Risk Register that tracks risks by ID, description, impact, likelihood, owner, and mitigation plan, reviewed weekly during syncs. A three-level escalation path—from team-level triage in standups, to PM escalation to Product Leads, to sponsor-level escalation for business-impacting issues—ensures blockers are quickly identified and resolved. Security scanning is integrated into CI pipelines, and manual QA validates feature acceptance when needed.

OctoAcme establishes a disciplined communication cadence that keeps all stakeholders informed and aligned. Status updates follow a consistent template (Progress, Next Steps, Risks & Blockers, Ask/Decisions Needed) shared weekly or milestone-by-milestone. Project artifacts—charters, release plans, risk registers, and retrospective notes—serve as single sources of truth stored in project repositories. After each sprint, release, or milestone, OctoAcme holds structured retrospectives (45��75 minutes) to capture what went well, what could improve, and prioritize 2–3 actionable items with clear owners and due dates. This focus on learning, measurement, and iterative improvement creates a culture where small, evidence-based changes compound over time, reducing single-person dependency and enabling consistent, repeatable project execution.

## Process Documentation

OctoAcme follows a structured project lifecycle. Navigate to any of the process guides below based on your current phase:

### 1. [Project Initiation](./octoacme-project-initiation.md)
Validate and authorize new work, align stakeholders, and create a lightweight plan.
- **When to use:** Whenever a new project idea or feature proposal is ready to be explored
- **Key deliverables:** Project One-pager, Stakeholder list, High-level timeline, Initial risk list

### 2. [Project Planning](./octoacme-project-planning.md)
Turn approved initiatives into actionable plans and backlogs for delivery.
- **Key activities:** Kickoff meeting, Prioritized backlog creation, Scope estimation, Dependency identification
- **Outputs:** Release plan, Milestone map, Definition of Done

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution and tracking progress toward milestones.
- **Team rhythm:** Daily standups (15 min), Weekly delivery sync, Demo/Review at sprint end
- **Quality practices:** Unit tests, Integration tests, Automated CI, Security scanning

### 4. [Risk Management & Communication](./octoacme-risks-and-communication.md)
Identify, manage, and communicate risks and dependencies effectively.
- **Risk lifecycle:** Identify → Assess → Mitigate → Monitor
- **Escalation paths:** Team-level → PM → Product Lead → Sponsor
- **Communication templates:** Weekly status, Incident communication

### 5. [Release & Deployment](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production to reduce risk and improve observability.
- **Release types:** Patch, Minor, Major
- **Pre-release requirements:** Acceptance criteria met, CI passing, Security scans complete
- **Post-deployment:** Verification, Announcement, Rollback procedures

### 6. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements.
- **Timing:** After each sprint, release, or important milestone
- **Structure:** What went well, What could improve, Action items with owners
- **Focus:** 2–3 prioritized action items to avoid overload

## Reference Materials

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions and responsibilities for Developers, Product Managers, and Project Managers
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme principles and practices

## Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Key Artifacts

Throughout a project lifecycle, OctoAcme creates and maintains:

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Contributing

To suggest updates or additions to these process docs, use the [Add Content to Project Management Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

**Last updated:** August 2026
