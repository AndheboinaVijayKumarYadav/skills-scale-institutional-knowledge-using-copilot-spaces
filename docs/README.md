# OctoAcme Project Management Docs

## Overview

OctoAcme uses an iterative, customer-focused project management methodology. All projects follow a standardized lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Continuous Improvement/Retrospective**. Core principles include:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed decisions**: Measure impact and evidence
- **Psychological safety**: Encourage feedback and learning

This documentation provides guidance, checklists, and templates to help teams execute projects consistently and transparently.

## How OctoAcme Executes Projects

### Project Lifecycle & Workflows

OctoAcme operates a structured, lifecycle-driven project management approach that emphasizes customer value, iterative delivery, and clear ownership. The process is organized into five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During initiation, teams validate business needs by creating a lightweight one-pager that captures the problem statement, success metrics, stakeholder alignment, and resource requirements. Once approved by the Product Lead and sponsors, projects move into planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a Definition of Done is established. This foundation ensures every team member understands scope, quality expectations, and shared responsibility for delivery.

### Execution, Roles & Communication

Execution and delivery are coordinated through a rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations. Work flows through a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done, keeping transparency high and blockers visible. The core delivery team includes **Developers** (who implement features and maintain tests), **Product Managers** (who prioritize the backlog and measure outcomes), **Project Managers** (who coordinate schedules, risks, and communications), and **QA/Testing** resources (who validate quality and acceptance criteria). Pull requests are kept small (≤400 lines when possible), require automated testing and linting in CI, and need at least one approval before merging—maintaining code quality while unblocking progress.

### Quality, Risk Management & Continuous Improvement

Quality assurance and risk management are woven throughout the entire lifecycle. Teams practice unit testing, integration testing, and end-to-end smoke tests for critical flows, with security scanning embedded in CI pipelines. A Risk Register is maintained and reviewed at weekly syncs, capturing impact, likelihood, and mitigation strategies. Escalation follows a three-level model: team-level triage during standups, PM escalation to Product Leads for medium-priority issues, and sponsor involvement for business-impacting blockers. Finally, every project culminates in a retrospective where teams reflect on what went well, what could improve, and identify 2–3 actionable improvements for the next cycle. These learnings are tracked, owned, and reviewed in subsequent syncs to build a culture of continuous improvement.

---

## Process Docs Index

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence

### Project Lifecycle

1. **[Project Initiation Guide](octoacme-project-initiation.md)** — Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and decision gate criteria.

2. **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery. Covers backlog prioritization, estimation, Definition of Done, and risk/dependency mapping.

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward project milestones. Includes team rhythm, PR workflow, quality standards, and blocker escalation.

4. **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklist, and rollback playbooks.

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements. Structure, templates, and tracking for action items.

### Supporting Guides

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout the project lifecycle. Includes Risk Register template, stakeholder communication strategies, and escalation paths.

- **[Project Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Developers, Product Managers, Project Managers) used in OctoAcme projects and their responsibilities, goals, and communication patterns.

---

## How to Use This Documentation

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the sequence: Initiation → Planning → Execution → Release → Retrospective
- **Looking for a template or checklist?** Check the relevant lifecycle phase document
- **Managing risks or communicating status?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Need role clarity?** See [Project Roles & Personas](octoacme-roles-and-personas.md)

## Keeping Docs Current

These docs represent our living project management practices. As processes evolve or new guidance is needed:

1. Use the [Add Content to Project Management Process Docs issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates
2. Include rationale and suggested content in your issue
3. Update links and index in this README as new docs are created

---

*Last updated: 2026-05-29*
