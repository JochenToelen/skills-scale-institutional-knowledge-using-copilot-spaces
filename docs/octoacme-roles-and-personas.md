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

## UX / Design Lead

### Role Summary
Drives user research, interaction design, and usability validation to ensure features deliver a high-quality user experience aligned with customer needs.

### Responsibilities
- Conduct user research
- Create wireframes, prototypes, and UI specs
- Collaborate with PdM on usability acceptance criteria
- Participate in sprint reviews for UX validation
- Maintain design system/style guide

### Goals
- Deliver intuitive, accessible experiences
- Reduce rework by aligning design and engineering early
- Advocate for the end user

### Typical Communication
- Design reviews and usability sessions
- Collaboration with Developers during implementation
- Feedback loops with PdM and stakeholders

### Interaction with Existing Roles (PM, PdM, Developers, QA)
- PM: aligns UX activities and dependencies with delivery plans.
- PdM: co-defines usability goals, acceptance criteria, and feature outcomes.
- Developers: provides implementation-ready designs and clarifies interaction details.
- QA: aligns on UX acceptance checks for usability and accessibility expectations.

---

## Tech Lead / Engineering Lead

### Role Summary
Owns the technical direction of the project, ensures architectural soundness, and sets quality standards for the engineering team.

### Responsibilities
- Define and communicate technical architecture and design decisions
- Review and approve significant PRs and technical designs
- Identify and mitigate technical risks
- Mentor developers
- Coordinate with PM on technical dependencies and timelines

### Goals
- Deliver scalable, maintainable, and secure solutions
- Minimize technical debt
- Align technical execution with product and business goals

### Typical Communication
- Technical design discussions and architecture reviews
- Code review feedback
- Weekly delivery sync with PM and PdM

### Interaction with Existing Roles (PM, PdM, Developers, QA)
- PM: communicates technical constraints, risks, and sequencing impacts.
- PdM: aligns implementation trade-offs with product goals and timelines.
- Developers: provides technical direction, standards, and mentoring support.
- QA: aligns quality strategy, testability, and release readiness criteria.

---

## Scrum Master / Delivery Coach

### Role Summary
Facilitates agile ceremonies, shields the team from interruptions, removes impediments, and continuously improves team processes.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives
- Identify and remove blockers or escalate
- Track team health and flag process issues
- Coach the team on agile best practices
- Collaborate with PM on delivery rhythm

### Goals
- Enable a high-performing, self-organizing team
- Reduce cycle time and eliminate waste
- Foster continuous improvement culture

### Typical Communication
- Daily standups and retrospective facilitation
- Impediment logs and escalation updates
- Collaboration with PM on delivery cadence

### Interaction with Existing Roles (PM, PdM, Developers, QA)
- PM: aligns ceremonies and reporting cadence with project milestones.
- PdM: supports predictable refinement and planning flow for backlog readiness.
- Developers: removes day-to-day impediments and coaches team collaboration.
- QA: ensures QA work is planned in sprint flow and surfaced in blockers early.

---

## Security & Compliance Officer

### Role Summary
Ensures all project deliverables meet security requirements, compliance standards, and data protection obligations.

### Responsibilities
- Define and enforce security requirements and scanning gates in CI
- Review architecture and code for security vulnerabilities
- Ensure compliance with regulations and internal policies
- Own the security incident runbook
- Collaborate with Tech Lead on remediation

### Goals
- Prevent security incidents through proactive risk management
- Ensure compliance throughout the project lifecycle
- Enable fast, secure delivery

### Typical Communication
- Security review sessions during planning and pre-release
- CI/CD pipeline alerts and findings
- Incident notifications and post-incident retrospectives

### Interaction with Existing Roles (PM, PdM, Developers, QA)
- PM: escalates security risks, timelines, and incident response needs.
- PdM: aligns security/compliance requirements with product scope decisions.
- Developers: guides secure coding practices and remediation priorities.
- QA: integrates security validation into test strategy and release checks.

---

## Business Analyst (BA)

### Role Summary
Bridges business stakeholders and the technical team by translating high-level requirements into detailed, actionable specifications.

### Responsibilities
- Elicit and document functional and non-functional requirements
- Write detailed acceptance criteria and user stories
- Validate that delivered features meet business requirements
- Facilitate requirement workshops
- Maintain traceability between business goals and backlog items

### Goals
- Ensure the team builds the right thing the first time
- Reduce ambiguity and rework
- Improve stakeholder confidence in delivery outcomes

### Typical Communication
- Requirements workshops and discovery sessions
- Collaboration with PdM and Developers on backlog refinement
- Stakeholder feedback sessions and sign-off meetings

### Interaction with Existing Roles (PM, PdM, Developers, QA)
- PM: aligns requirement delivery with schedule, risk, and dependency tracking.
- PdM: translates strategic outcomes into detailed, testable backlog items.
- Developers: clarifies requirement details and edge cases during implementation.
- QA: collaborates on acceptance criteria and requirement traceability to tests.

---

## Sponsor / Executive Stakeholder

### Role Summary
Provides strategic direction, champions the project at the executive level, approves major decisions and investments, and resolves Level 3 escalations.

### Responsibilities
- Approve project charter and major scope or budget changes
- Remove organizational blockers beyond the PM's authority
- Receive and act on Level 3 escalations (as defined in Execution & Tracking)
- Communicate project status to senior leadership
- Ensure alignment with business strategy

### Goals
- Protect project investment and maximize business value
- Enable the team by clearing executive-level impediments
- Maintain visibility and confidence at the leadership level

### Typical Communication
- Monthly or milestone-based status updates
- Escalation notifications from PM
- Executive briefings and steering committee meetings

### Interaction with Existing Roles (PM, PdM, Developers, QA)
- PM: receives escalations and supports decisions beyond delivery authority.
- PdM: aligns strategic product decisions with business priorities and funding.
- Developers: provides executive unblock support for cross-org technical constraints.
- QA: supports risk-based release decisions when quality or compliance risk is high.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
