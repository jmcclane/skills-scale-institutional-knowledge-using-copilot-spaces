# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management guide. This folder contains the complete suite of process documentation to help teams run projects effectively.

## About OctoAcme Project Management

OctoAcme operates on a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. Projects progress through five key stages: **Initiation** (validating business need and aligning stakeholders), **Planning** (breaking work into shippable increments and defining success metrics), **Execution** (managing day-to-day delivery and tracking progress), **Release** (deploying to production with standardized processes), and **Retrospectives** (capturing learnings and driving continuous improvement).

### Core Principles

OctoAcme projects are guided by:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Roles & Communication

Clear roles and responsibilities ensure accountability and smooth collaboration:
- **Project Manager (PM)**: Coordinates delivery activities, manages schedules, risks, and communications
- **Product Manager (PdM)**: Owns the product vision, prioritizes the backlog, and measures success metrics
- **Developers**: Implement features, write tests, participate in design reviews, and identify technical risks
- **QA/Testing**: Validates quality and ensures acceptance criteria are met
- **Stakeholders**: Provide inputs and approvals at key decision gates

OctoAcme maintains structured communication through daily standups (15 min focus on progress and blockers), weekly delivery syncs, and monthly stakeholder updates. Work is visualized on GitHub Projects boards, and risk registers are reviewed weekly. Blocker escalation follows a clear three-level path: team-level triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues.

### Quality Assurance & Risk Management

Quality is embedded throughout OctoAcme's processes. Development includes unit tests, integration tests, end-to-end smoke tests, automated CI with security scanning, and peer review requirements before merging. Releases require all acceptance criteria to be met, passing CI, drafted release notes, and documented rollback plans. Risk management happens continuously—risks are identified, assessed for impact and likelihood, actively mitigated, monitored at weekly syncs with clear ownership, and systematically converted into prioritized action items through retrospectives.

---

## Getting Started

New to OctoAcme? Start with our [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, core roles, and key artifacts.

## Process Documentation

### Project Lifecycle Stages

| Stage | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) | Validate business need, align stakeholders, create lightweight plan |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Turn initiative into actionable plan and backlog |
| **Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress |
| **Release** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize release process and reduce risk |
| **Closeout** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements |

### Cross-Cutting Concerns

- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Roles & Personas](./octoacme-roles-and-personas.md) — Define typical PM, Product Manager, Developer, and QA responsibilities

## Quick Reference

Need quick guidance? Use these shortcuts:

- **Starting a new project?** Begin with [Initiation](./octoacme-project-initiation.md)
- **Need to plan a sprint?** See [Planning](./octoacme-project-planning.md)
- **Managing blockers?** Check [Execution & Tracking](./octoacme-execution-and-tracking.md#blocker-escalation)
- **Preparing a release?** Follow [Release & Deployment](./octoacme-release-and-deployment.md)
- **Running a retrospective?** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Need role clarity?** Reference [Roles & Personas](./octoacme-roles-and-personas.md)
- **Managing project risks?** See [Risk Management & Communication](./octoacme-risks-and-communication.md)

## Contributing to Process Docs

Have feedback or want to update a process document? Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to request changes.

This approach ensures that process improvements are captured systematically and that all team members have a voice in how we continuously refine our project management practices.
