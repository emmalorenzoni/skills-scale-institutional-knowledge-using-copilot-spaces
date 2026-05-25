# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains comprehensive documentation of the processes, workflows, and best practices used across all OctoAcme projects.

## Quick Start

New team members should start with:
1. **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** — Understand our core principles and roles
2. **[OctoAcme Roles & Personas](octoacme-roles-and-personas.md)** — Learn about key responsibilities and personas
3. The relevant phase guide based on where your project is in the lifecycle

## Process Documentation

This knowledge base is organized by project phase:

- **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and define success criteria
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments with clear acceptance criteria and dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress, and maintain quality standards
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize releases to production with reduced risk and improved observability
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

## OctoAcme Project Management Overview

### Project Lifecycle & Core Principles

OctoAcme follows a structured five-phase project lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. The organization is guided by customer-first principles, iterative delivery, clear ownership, data-informed decision-making, and psychological safety. Projects begin with validation through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes measurable success metrics. Once approved at the decision gate—when success criteria are clear, stakeholders align, and team availability is confirmed—projects move into detailed planning where work is broken into shippable increments with defined acceptance criteria, dependencies, and risk mitigation strategies.

### Roles, Responsibilities & Communication Cadence

OctoAcme operates with clearly defined personas: **Project Managers** coordinate delivery, manage schedules and risks, and facilitate stakeholder communication; **Product Managers** define what to build, prioritize the backlog, and measure outcomes; **Developers** implement features, write tests, and identify technical risks; and **QA/Testing** validates quality against acceptance criteria. Communication is structured through a consistent cadence—daily standups (15 minutes), weekly delivery syncs between PM and PdM, monthly stakeholder updates, and ad-hoc escalations. The team uses a three-level escalation path (team-level → PM → Product Lead → Sponsor) for blockers, ensuring transparency and quick resolution of dependencies.

### Execution, Quality & Continuous Improvement

During execution, teams manage work through project boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and follow a small PR workflow (≤400 lines when possible) with required approvals before merging. Quality assurance is comprehensive, including unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance. Deployment follows a structured pre-release checklist with staging verification, automated pipelines where possible, and documented rollback plans. Finally, OctoAcme embeds continuous improvement through sprint or milestone retrospectives, which capture learnings (what went well, what to improve) and convert them into tracked action items with clear owners and timelines, fostering a culture of iterative refinement across all projects.

## Contributing

To update or add content to these process documents, please:

1. Create an issue using the **"Add Content to Project Management Process Docs"** template (see `.github/ISSUE_TEMPLATE/`)
2. Describe the update, rationale, and proposed content
3. Submit a pull request with your changes
4. Request review from the team

## Questions?

If you have questions about any of these processes, reach out to your Project Manager or Product Lead, or open a discussion in the repository.