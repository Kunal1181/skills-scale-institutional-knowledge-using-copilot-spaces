# OctoAcme Project Management Docs

Welcome! This README provides a high-level overview of OctoAcme's project management processes and links to all program process documents in this repository.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, iterative project management approach grounded in five core principles: **customer-first prioritization**, **iterative delivery of small testable increments**, **clear ownership** with named Project Managers and Product Leads, **data-informed decision-making**, and a culture of **psychological safety**. The organization applies this methodology across all cross-functional projects that deliver product features, services, or integrations. The lifecycle progresses through five distinct phases—Initiation, Planning, Execution, Release, and Close & Retrospective—ensuring that work is validated upfront, planned thoroughly, executed with quality discipline, and continuously improved through structured retrospectives.

### Key Roles and Workflows

OctoAcme's project success depends on three primary roles: **Project Managers** (who coordinate schedules, risks, and communications), **Product Managers** (who define outcomes, prioritize the backlog, and measure success), and **Developers** (who implement features and collaborate on design and testability). The project initiation phase validates business need through a lightweight One-pager template that captures the problem statement, objectives, success metrics, stakeholder alignment, and resource needs before moving forward. Once approved, the planning phase breaks work into a prioritized backlog with acceptance criteria, estimates scope using T-shirt sizing or story points, and creates a detailed release plan with clearly defined dependencies and a Definition of Done.

### Execution, Quality, and Communication

During execution, OctoAcme maintains a disciplined rhythm with daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations. The team uses GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforces small pull requests (≤400 lines when possible) with at least one approval before merging. Quality is embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Risks are actively managed through a Risk Register (tracked by ID, impact, likelihood, owner, and mitigation plan) with escalation paths from team-level triage through PM to Product Lead to sponsor-level decision-making. Weekly status updates, incident communication templates, and stakeholder briefings ensure transparency, while retrospectives after each sprint or release capture learnings and convert them into prioritized action items that feed back into continuous improvement.

## Process Documents Index

Navigate to the detailed process guides below for actionable steps, checklists, and templates:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle.
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Define initial steps to validate business need, align stakeholders, and create a lightweight plan.
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, align timelines and responsibilities.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress, maintain quality, and escalate blockers.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies; maintain transparency with stakeholders.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production to reduce risk and improve observability.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed role definitions and responsibilities for Project Managers, Product Managers, and Developers.

## Quick Links

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.
- **Starting a new project?** Use the [Project Initiation Guide](./octoacme-project-initiation.md) to validate and authorize work.
- **In execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for workflows and quality standards.
- **Managing risks?** Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths and templates.
- **Preparing a release?** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release and deployment checklists.
- **Post-project reflection?** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements.

## Issue Templates

Process improvement requests and documentation updates are tracked using GitHub issue templates in [`.github/ISSUE_TEMPLATE/`](../.github/ISSUE_TEMPLATE/):

- **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** — Use this template to propose updates or additions to existing process documents or to create new ones.

## Questions or Feedback?

If you have questions about these processes, encounter gaps, or want to suggest improvements, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
