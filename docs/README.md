# OctoAcme Project Management Docs

A guide to OctoAcme's project management processes, roles, artifacts, and delivery practices.

## Process overview

OctoAcme uses a lightweight, outcome-oriented lifecycle: initiatives begin with validated business needs and stakeholder alignment, move through planning and prioritized backlogs, and proceed through iterative execution with testing, reviews, and progress tracking. Risks, dependencies, and stakeholder communications are managed throughout delivery. Releases require acceptance criteria, passing quality and security checks, release notes, smoke tests, and rollback planning. Each sprint, release, or major milestone ends with a retrospective so the team can capture learnings and continuously improve.

## Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, key artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — Business need, stakeholders, success criteria, risks, resources, and the initiation decision gate.
- [Project Planning](octoacme-project-planning.md) — Kickoff, backlog creation, estimation, Definition of Done, dependencies, risks, and release planning.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, project-board workflow, pull requests, quality practices, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, risk lifecycle, stakeholder updates, incident communication, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment, verification, rollback, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, action-item tracking, and continuous improvement practices.
- [Roles & Personas](octoacme-roles-and-personas.md) — Responsibilities, goals, and communication patterns for developers, Product Managers, and Project Managers.

## How to use these documents

Start with the [Project Management Overview](octoacme-project-management-overview.md), then use the lifecycle-specific guides as the project progresses. Keep project-specific charters, plans, risk registers, status updates, and retrospective actions current in the project repository.

## Roles and responsibilities

Product Managers define outcomes, prioritize the backlog, and measure success. Project Managers coordinate delivery, schedules, risks, dependencies, and stakeholder communication. Developers implement features, tests, and documentation, while QA and stakeholders help validate acceptance criteria and release readiness. Clear ownership and cross-functional collaboration support predictable delivery.

## Communication and risk management

OctoAcme uses daily standups or delivery-team check-ins, weekly PM and Product Manager alignment, delivery syncs, milestone demos, and regular stakeholder updates. Teams maintain a single source of truth for status and decisions, track risks in a register with owners and mitigation plans, and escalate blockers from the team to the PM, Product Lead, and sponsor when business impact requires it.

## Quality and continuous improvement

Quality is built into delivery through acceptance criteria, unit and integration tests, end-to-end smoke tests for critical flows, CI linting, security scanning, and pull request review. Releases require passing checks, release notes, deployment verification, and rollback or mitigation plans. After each sprint, release, or major milestone, retrospectives capture what went well, what should improve, and action items that are tracked in the backlog or issues.
