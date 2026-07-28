# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains all process guides that define how OctoAcme plans, executes, and continuously improves its projects.

## Summary of Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project delivery, moving work through five distinct phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager capturing the problem statement, SMART goals, success metrics, and stakeholder alignment. A formal decision gate ensures that work only advances into planning once success criteria are clear, stakeholders are aligned, and team capacity is confirmed. From there, planning activities focus on breaking scope into shippable increments with explicit acceptance criteria, a Definition of Done, and a risk register that tracks impact, likelihood, owner, and mitigation for each identified risk.

Day-to-day execution is anchored in a consistent team rhythm: 15-minute daily standups to surface blockers and dependencies, weekly delivery syncs for progress and risk updates, and sprint-end demos for stakeholder visibility. Work moves through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with pull requests kept small (≤ 400 lines where possible), linked to issues, and gated behind automated CI checks and at least one peer approval. Quality is enforced at multiple layers — unit tests, integration tests, end-to-end smoke tests, and security scanning in CI — with manual QA reserved for critical feature acceptance.

OctoAcme defines three core personas with distinct responsibilities: the *Project Manager* coordinates timelines, risks, and cross-team communications; the *Product Manager* owns the product vision, backlog prioritization, and outcome measurement; and *Developers* implement features, maintain test coverage, and contribute to technical risk identification. These roles collaborate through a clear communication cadence — weekly PM/PdM syncs, twice-weekly standups, monthly stakeholder updates, and a three-level blocker escalation path (team → PM/Product Lead → Sponsor) for issues that cannot be resolved at the team level.

Releases are governed by a standardized checklist covering staging smoke tests, rollback planning, and post-deploy verification before any production deployment. After each sprint, release, or incident, the team runs a timeboxed retrospective (45–75 minutes) structured around what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates. Those action items feed back into the project backlog, closing the loop on continuous improvement and ensuring that learnings are tracked, measured, and celebrated — reinforcing a culture of iterative, evidence-based delivery.

## Process Overview by Phase

- **Initiation**: Validate and authorize work, align stakeholders, and define success metrics and a high-level timeline before committing to planning.
- **Planning**: Break approved initiatives into shippable increments, identify dependencies and risks, and align on release milestones and Definition of Done.
- **Execution & Tracking**: Manage day-to-day delivery through standups, sprint reviews, a structured PR workflow, CI quality gates, and blocker escalation paths.
- **Risk Management & Communication**: Maintain a risk register, assess and mitigate risks continuously, and keep stakeholders informed through regular status updates and clear escalation paths.
- **Release & Deployment**: Standardize releases with pre-release checklists, automated pipelines, smoke tests, rollback plans, and stakeholder announcements.
- **Retrospective & Continuous Improvement**: Capture learnings after each sprint or milestone, convert them into actionable backlog items, and track impact over time.
- **Roles & Personas**: Clearly defined responsibilities for Developers, Product Managers, and Project Managers to ensure accountability and efficient collaboration.

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's PM approach, roles, artifacts, and lifecycle. |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work, including the Project One-pager template. |
| [Project Planning](octoacme-project-planning.md) | Guidance on building an actionable plan, backlog, and release timeline. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery practices, PR workflow, quality standards, and blocker escalation. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication templates. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook, and release notes template. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and continuous improvement culture. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for Developers, Product Managers, and Project Managers. |
