# OctoAcme Project Management Docs

## Overview

OctoAcme operates on a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization follows five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, projects begin with a lightweight one-pager that captures the business need, success metrics, stakeholders, and initial timeline—moving forward only when stakeholders align and measurable outcomes are defined. This decision-gate approach ensures that only well-validated work enters the planning phase, where teams break projects into shippable increments, build prioritized backlogs with clear acceptance criteria, estimate scope, and map dependencies and milestones.

Execution and delivery are coordinated through a consistent team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and sprint-based planning. Teams use GitHub Projects to visualize workflow across columns like Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept lean (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval before merging. Quality assurance is embedded throughout—unit tests, integration tests, and smoke tests are expected before release, along with security scanning in CI and manual QA when needed. Progress is tracked through velocity and burndown metrics, with key success indicators tied back to the original project goals.

OctoAcme defines clear roles to avoid ambiguity: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build and measure outcomes; **Developers** design, build, and test features; and **QA/Testing** validates quality and acceptance criteria. Communication flows through multiple cadences—weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, and monthly stakeholder updates—with escalation paths for blockers: team-level triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues.

Releases are standardized by type (patch, minor, major) and follow a pre-release checklist ensuring all acceptance criteria are met, CI/security checks pass, and rollback plans are documented. Post-release, the organization captures learnings through retrospectives after each sprint or milestone, converting action items into traceable improvements tracked in the project backlog. This emphasis on continuous feedback, blameless retrospectives, and iterative refinement—along with maintaining a single source of truth in project repositories—enables consistent, repeatable execution while reducing single-person dependency risk and accelerating team onboarding.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Quick Navigation by Phase

| Phase | Document | Purpose |
|-------|----------|---------|
| **Getting Started** | [Project Management Overview](octoacme-project-management-overview.md) | Understand OctoAcme's framework, roles, and key artifacts |
| **Initiation** | [Project Initiation Guide](octoacme-project-initiation.md) | Validate business need, align stakeholders, create lightweight plan |
| **Planning** | [Project Planning](octoacme-project-planning.md) | Break work into shippable increments, manage dependencies |
| **Execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress |
| **Risk Management** | [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| **Release** | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize release and deployment processes |
| **Learning** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements |
| **Team Reference** | [OctoAcme Personas](octoacme-roles-and-personas.md) | Understand key roles and responsibilities |

## All Documentation

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](octoacme-project-initiation.md)
- [octoacme-project-planning.md](octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
3. **In the middle of execution?** Reference the [Execution & Tracking](octoacme-execution-and-tracking.md) guide
4. **Need to understand a specific role?** Check [OctoAcme Personas](octoacme-roles-and-personas.md)
5. **Managing risks or communicating updates?** Use [Risk Management & Communication](octoacme-risks-and-communication.md)
6. **Preparing for release?** Consult [Release & Deployment Guide](octoacme-release-and-deployment.md)
7. **After a milestone or sprint?** Run through [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Key Artifacts Across Project Lifecycle

- **Project Charter / One-pager**: Captured during Initiation
- **Roadmap and Release Plan**: Defined during Planning
- **Sprint/Iteration Backlog**: Managed during Execution
- **Acceptance Criteria & Definition of Done**: Established during Planning
- **Risk Register**: Maintained throughout Execution
- **Retrospective notes and action items**: Captured during Close & Retrospective

## Communication Cadence

- Weekly sync between PM + Product Manager
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

---

*These documents are living artifacts. To suggest updates or improvements, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.*
