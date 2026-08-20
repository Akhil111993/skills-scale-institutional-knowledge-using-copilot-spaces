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

## QA/Quality Assurance Lead

### Role Summary
QA Leads define quality standards, test strategy, and acceptance criteria. They collaborate with developers and product managers to ensure features meet quality thresholds and user expectations.

### Responsibilities
- Define test strategy and acceptance criteria with product managers
- Establish quality standards and Definition of Done criteria
- Design and execute manual and automated test plans
- Triage and document defects with clear reproduction steps
- Partner with developers on test coverage and edge cases
- Validate acceptance criteria before marking work complete
- Track and report on quality metrics and test coverage

### Goals
- Prevent defects from reaching production
- Deliver high-confidence, maintainable test coverage
- Improve quality metrics and reduce post-release issues

### How they interact with other roles
- **Developers**: Partner on test coverage strategies, participate in code reviews to validate quality standards
- **Product Managers**: Align on acceptance criteria and quality expectations during backlog refinement
- **Project Managers**: Report on quality metrics and test progress as part of delivery tracking
- **Technical Leads**: Collaborate on test automation infrastructure and quality best practices

### Typical Communication
- Acceptance criteria refinement sessions
- QA sign-off gates in PR reviews
- Daily standup updates on test progress and blockers
- Quality dashboards and metrics reporting

---

## Technical Lead/Architect

### Role Summary
Technical Leads make critical design decisions, own system architecture, and guide the team on technical direction. They balance short-term delivery with long-term maintainability.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Identify technical risks and propose mitigations
- Guide code quality standards and best practices
- Mentor developers and conduct technical code reviews
- Manage technical debt and prioritize refactoring work
- Evaluate build/test/deployment tooling and infrastructure needs
- Serve as escalation point for complex technical trade-offs

### Goals
- Ensure technical decisions support both current and future project needs
- Minimize technical debt and maintain code quality
- Build scalable, maintainable systems

### How they interact with other roles
- **Developers**: Mentor through code review feedback and technical design guidance
- **QA Leads**: Collaborate on test automation infrastructure and quality standards
- **Project Managers**: Advise on technical risks and dependencies that impact timeline
- **Product Managers**: Provide technical perspective on feasibility and trade-offs during planning

### Typical Communication
- Technical design reviews and RFCs (Request for Comments)
- Architecture decision records in documentation
- Code review feedback and mentoring
- Technical risk assessments in project planning

---

## Release Manager

### Role Summary
Release Managers coordinate all activities needed to move features from development to production. They own the deployment checklist, timing, and post-release verification.

### Responsibilities
- Plan and schedule release windows
- Coordinate pre-release testing and smoke test execution
- Create and communicate release notes
- Manage deployment scripts and automation
- Execute or oversee production deployments
- Run post-deployment verification and health checks
- Coordinate rollback procedures if needed
- Document deployment metrics and incidents

### Goals
- Deliver releases safely with minimal downtime
- Reduce deployment risk through preparation and automation
- Enable fast, predictable release cadence

### How they interact with other roles
- **Developers**: Coordinate on code freeze and deployment readiness
- **QA Leads**: Align on smoke test requirements and pre-release testing timelines
- **Project Managers**: Communicate release status and dependencies across stakeholders
- **Technical Leads**: Collaborate on deployment architecture and rollback strategies

### Typical Communication
- Release coordination meetings and checklists
- Release notes and deployment runbooks
- Status updates during deployment windows
- Post-release incident communication

---

## Stakeholder/Sponsor

### Role Summary
Sponsors provide business context, strategic priorities, and decision authority. They align projects with organizational goals and secure resources and approvals.

### Responsibilities
- Define business objectives and success criteria
- Prioritize work against competing initiatives
- Approve scope, timeline, and resource decisions
- Escalate blockers at executive level if needed
- Communicate project value to leadership and customers
- Attend milestone reviews and provide feedback
- Make trade-off decisions (scope, timeline, quality)

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment with organizational priorities
- Enable rapid decision-making and risk mitigation

### How they interact with other roles
- **Product Managers**: Align on priorities and provide business context for product decisions
- **Project Managers**: Escalate blockers and approve timeline/scope changes
- **Developers and Technical Leads**: Provide business rationale for architectural decisions and trade-offs
- **QA Leads and Release Managers**: Approve quality gates and release decisions

### Typical Communication
- Milestone reviews and steering committee meetings
- Monthly executive status updates
- Ad-hoc escalation and approval requests
- Risk and dependency reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
