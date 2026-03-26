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

## QA/Testing Specialists

### Role Summary
QA/Testing Specialists ensure product quality through test planning, validation, and release readiness checks. They partner with product and engineering to make quality criteria explicit and measurable.

### Responsibilities
- Define test strategy and scope for each delivery increment
- Validate acceptance criteria before work is marked done
- Perform exploratory and regression testing for critical flows
- Triage defects and coordinate resolution priorities with the team
- Support pre-release smoke testing and post-release verification

### Goals
- Reduce escaped defects and production incidents
- Increase confidence in release quality
- Provide early quality feedback to reduce rework

### Typical Communication
- Daily bug triage and test status updates
- QA sign-off notes in sprint/release checkpoints
- Defect reports with reproducible steps and severity

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide solution design, technical decision making, and engineering standards. They ensure implementations are scalable, maintainable, and aligned with long-term architecture goals.

### Responsibilities
- Review architecture and technical design proposals
- Identify and mitigate technical risks and dependencies
- Define engineering standards and quality guardrails
- Mentor developers and support technical decision trade-offs
- Track and prioritize technical debt with product and project leads

### Goals
- Maintain system reliability and technical quality
- Improve developer effectiveness and delivery speed
- Balance short-term delivery with long-term sustainability

### Typical Communication
- Design review sessions and architecture notes
- Risk and dependency inputs for planning sessions
- PR guidance on complex implementation decisions

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors represent business outcomes, strategic constraints, and funding priorities. They help ensure delivery remains aligned to customer and organizational goals.

### Responsibilities
- Define business outcomes and success criteria
- Approve key scope, schedule, and funding decisions
- Participate in major go/no-go and escalation decisions
- Remove cross-functional blockers that affect delivery
- Review status and outcome reports from PM and PdM

### Goals
- Ensure initiatives deliver measurable business value
- Keep work aligned with strategy and priorities
- Reduce organizational friction for delivery teams

### Typical Communication
- Weekly or monthly stakeholder status reviews
- Decision logs and approval checkpoints
- Escalation responses for high-impact risks

---

## Release / DevOps Engineers

### Role Summary
Release and DevOps Engineers own deployment reliability, environment consistency, and operational readiness. They help teams ship quickly and safely through automation and operational discipline.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage staging and production environment readiness
- Support release windows, rollback planning, and post-release checks
- Monitor production health and alerting signals
- Maintain runbooks and incident response procedures

### Goals
- Increase deployment frequency with low failure rates
- Minimize downtime and release risk
- Improve recovery speed for production issues

### Typical Communication
- Release readiness updates and deployment run logs
- Incident response channels and post-incident summaries
- Coordination with QA and developers on release blockers

---

## Security / Compliance Officers

### Role Summary
Security and Compliance Officers ensure delivery aligns with security standards, regulatory obligations, and governance requirements. They embed risk-aware practices in planning, delivery, and release workflows.

### Responsibilities
- Define security and compliance requirements for initiatives
- Review architecture, code, and pipeline controls for risks
- Drive remediation tracking for vulnerabilities and findings
- Support audit readiness and evidence collection
- Provide guidance on secure development and data handling

### Goals
- Reduce security and compliance exposure
- Ensure auditability and policy adherence
- Build secure-by-default delivery practices

### Typical Communication
- Security review outcomes and remediation plans
- Compliance checkpoints in release planning
- Risk escalations with PM and sponsor stakeholders

---

## Cross-Role Collaboration Model

To improve clarity and accountability, teams should define role handoffs at each project phase:

- Initiation: Sponsor + Product Manager define outcomes; Project Manager defines governance cadence.
- Planning: Product Manager + Technical Lead shape scope and feasibility; QA defines test approach.
- Execution: Developers implement; QA validates; Project Manager tracks delivery and escalations.
- Release: DevOps leads deployment readiness; QA and Security provide final readiness signals.
- Retrospective: Project Manager facilitates; all roles contribute actions tied to owners and due dates.

Use the role accountability checklist in `docs/octoacme-role-accountability-checklist.md` during planning and release readiness reviews.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

