# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management Documentation Hub. This directory contains the core processes and guidance for running projects consistently across OctoAcme.

## Overview

OctoAcme follows a **customer-first, iterative delivery approach** with clear ownership, data-informed decisions, and a culture of psychological safety. These documents guide teams through each phase of the project lifecycle and define the roles, workflows, and quality standards that ensure consistent, repeatable project execution.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects move through five distinct phases:

1. **Initiation** - Validate business need, align stakeholders, define success metrics, and confirm resource availability
2. **Planning** - Break work into shippable increments, estimate scope, identify dependencies, and create a prioritized backlog
3. **Execution** - Build, test, review, and iterate with a disciplined team rhythm (daily standups, weekly syncs)
4. **Release** - Deploy to production with quality assurance, stakeholder communication, and rollback plans
5. **Close & Retrospective** - Capture learnings and translate them into continuous improvements

## Process Documents

### Getting Started
- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** - Start here to understand roles, artifacts, and the high-level project lifecycle. Covers core roles (PM, PdM, Developers, QA) and communication cadence.
- **[Roles & Personas](./octoacme-roles-and-personas.md)** - Detailed definitions of Project Managers, Product Managers, Developers, and QA/Testing roles with responsibilities, goals, and typical communication patterns.

### Running Projects
- **[Project Initiation Guide](./octoacme-project-initiation.md)** - Steps to validate an idea, identify stakeholders, create a Project One-pager, and make the go/no-go decision to move into planning.
- **[Project Planning](./octoacme-project-planning.md)** - Breaking work into backlog items, estimating scope, defining Definition of Done (DoD), mapping release timelines, and identifying dependencies.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Daily standups, PR workflows, quality standards (unit tests, integration tests, security scanning), progress tracking, and blocker escalation.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Pre-release requirements, deployment checklist, smoke tests, rollback procedures, and release notes templates.

### Supporting Functions
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Identifying and managing risks via a Risk Register, stakeholder communication templates, escalation paths, and incident playbooks.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Running retrospectives, capturing action items, and tracking impact of improvements over time.

## Quick Reference: When to Use Each Process

| Scenario | Primary Document | Secondary Resources |
|----------|------------------|---------------------|
| New project idea or proposal | [Project Initiation](./octoacme-project-initiation.md) | [Project Management Overview](./octoacme-project-management-overview.md) |
| Ready to start delivery planning | [Project Planning](./octoacme-project-planning.md) | [Execution & Tracking](./octoacme-execution-and-tracking.md) |
| Daily work in progress | [Execution & Tracking](./octoacme-execution-and-tracking.md) | [Project Planning](./octoacme-project-planning.md) (for DoD reference) |
| Blocked or at risk | [Risk Management & Communication](./octoacme-risks-and-communication.md) | [Project Planning](./octoacme-project-planning.md) (for dependencies) |
| Preparing for release | [Release & Deployment](./octoacme-release-and-deployment.md) | [Execution & Tracking](./octoacme-execution-and-tracking.md) |
| Sprint or project ends | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | All docs for historical context |

## Key Workflows

### Weekly Team Rhythm
- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery sync** — Show progress, flag risks, discuss cross-team dependencies
- **Weekly PM sync** — Align between Project Manager and Product Manager on priorities and risks
- **Demo/Review at sprint/milestone end** — Showcase completed work and gather feedback

### Pull Request Workflow
- Keep PRs small (≤400 lines when possible)
- Include issue link and acceptance criteria in PR description
- Run automated tests, linting, and security scanning in CI
- Require at least one approval before merging
- Link to related documentation or design specs as needed

### Quality & Testing Standards
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk & Blocker Escalation
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

## Core Roles at a Glance

| Role | Primary Responsibility |
|------|------------------------|
| **Project Manager** | Coordinates delivery, manages schedules, risks, and communications |
| **Product Manager** | Defines outcomes, prioritizes backlog, measures success |
| **Developers** | Implement features, collaborate on design and testability |
| **QA/Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs, approvals, and strategic guidance |

For detailed role definitions, see [Roles & Personas](./octoacme-roles-and-personas.md).

## Communication & Reporting

### Status Updates
Teams provide regular status updates using a standard template:
- **Progress this week** — What was delivered or completed
- **Next steps** — What's planned for the coming period
- **Risks & blockers** — Any issues impeding progress
- **Ask / decisions needed** — Input or approvals required

### Metrics & Dashboards
- Track velocity and burndown to monitor delivery pace
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)
- Review progress at weekly syncs and monthly stakeholder updates

## Getting Help

If you're unsure which process to follow:
1. Start with the [Quick Reference table](#quick-reference-when-to-use-each-process) above
2. Refer to the [Project Lifecycle](#project-lifecycle) diagram
3. Review the [Getting Started](#getting-started) section for foundational documents
4. Consult your Project Manager or Product Lead for clarification

---

*Last updated: 2026*
*For questions or updates to this documentation, create an issue using the "[Process Doc Update]" template.*
