# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-driven approach to project management built on five core principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**. The organization runs projects through five sequential phases—**Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**—each with defined artifacts, checklists, and decision gates. This phased approach ensures that every project begins with validated business need and measurable success criteria before significant resources are committed, minimizes scope creep through deliberate planning, and maintains quality and observability throughout delivery.

### Execution & Team Rhythm

The execution and tracking phase is operationalized through a clear team rhythm and collaborative workflows. Daily standups (15 minutes) focus the team on progress and blockers, while weekly delivery syncs provide visibility into flagged risks and demo/review cycles. Work flows through a GitHub Projects board using columns (Backlog, Ready, In Progress, In Review, QA, Done), with pull requests kept small (≤400 lines) and requiring at least one approval before merging. Quality assurance is embedded throughout with unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Velocity and burndown metrics are tracked continuously, and a three-level blocker escalation path ensures that team-level issues are triaged daily, with PM escalation to Product Lead for higher-impact blockers and sponsor-level involvement for business-impacting issues.

### Roles & Communication

Clear role definition and stakeholder communication are central to OctoAcme's success. Three primary roles anchor project delivery: **Project Managers** coordinate schedules, risks, and cross-team communication; **Product Managers** define vision, prioritize the backlog, and measure outcomes; and **Developers** implement features and collaborate on design and testability. A risk register maintained throughout the project lifecycle captures identification, assessment, mitigation, and monitoring of dependencies and blockers. Stakeholder communication follows standardized templates (weekly status updates, incident communications, and escalation paths) and is informed by a single source of truth maintained in the project repository.

### Continuous Improvement & Release

Continuous improvement is institutionalized through retrospectives held after each sprint, release, or milestone, where learnings are converted into actionable improvement items tracked in the project backlog with clear owners and due dates. Release and deployment processes are designed to reduce risk and improve observability. Before any release, all acceptance criteria must be met, CI and security scans must pass, and smoke tests must be prepared. Releases are classified by type (Patch, Minor, Major) and follow a structured deployment checklist that includes staging verification, post-deploy validation, and stakeholder announcement. A documented rollback and incident playbook ensures rapid response if deployment issues arise, with root cause captured and action items tracked through retrospectives.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle.
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate and authorize new work, align stakeholders, and create a lightweight initial plan.
- [Project Planning](./octoacme-project-planning.md) — Breaking approved initiatives into actionable plans and backlogs with clear dependencies and timelines.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution, team rhythm, quality standards, and blocker escalation.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies throughout the project lifecycle.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized processes for releasing features to production, including checklists and rollback procedures.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities.

## Getting Started

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach and core roles.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md), then move to [Project Planning](./octoacme-project-planning.md).
- **Managing a project in flight?** Use [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) as your primary references.
- **Preparing for release?** See [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- **Capturing lessons learned?** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).
