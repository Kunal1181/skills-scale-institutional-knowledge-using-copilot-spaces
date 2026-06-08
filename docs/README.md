# OctoAcme Project Management Docs

Welcome! This README provides a high-level overview of OctoAcme's project management processes and links to all program process documents in this repository.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, iterative project management approach grounded in five core principles: **customer-first prioritization**, **iterative delivery** of small testable increments, **clear ownership** with named Project Managers and Product Leads, **data-informed decision-making**, and a culture of **psychological safety**. The organization applies this methodology across all cross-functional projects that deliver product features, services, or integrations.

**Key Workflows:**
- **Customer-first, iterative delivery**: We focus on delivering customer value via incremental improvements, breaking work into shippable increments and measuring impact through defined success metrics.
- **Clear roles & artifacts**: Every project has a PM, Product Manager, documented charter, prioritized backlog, acceptance criteria, and risk register.
- **Structured lifecycle**: Projects follow a five-phase flow: **Initiation** → **Planning** → **Execution** → **Release** → **Retrospective**, with measurable metrics and regular syncs at each stage.
- **Transparent communication**: Regular updates, weekly status reports, and clearly defined escalation paths keep everyone aligned and unblock delivery quickly.

**Quality & Execution Discipline:**
- Small pull requests (≤400 lines) with at least one approval before merging
- Unit tests, integration tests, and end-to-end smoke tests before release
- Security scanning in CI and manual QA for feature acceptance
- Daily standups, weekly delivery syncs, and sprint-based iterations
- Risk registers tracked and reviewed at weekly synchronization meetings

## Core Roles

OctoAcme's project success depends on clear role definition and ownership:

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design, write tests, and help identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and business context

## Process Documents Index

Explore each process document for actionable guidance, checklists, and templates:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and authorize work
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, and create release plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, quality assurance, and blocker escalation
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk register, lifecycle, stakeholder communication, and escalation paths
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, and rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, capturing learnings, and tracking action items
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of typical roles and their responsibilities

## Quick Start for New Team Members

1. **Understand the big picture**: Start with [Project Management Overview](./octoacme-project-management-overview.md)
2. **Find your role**: Check [Roles and Personas](./octoacme-roles-and-personas.md) to see your responsibilities
3. **Learn the phase you're entering**: Use the process docs to understand what's happening now (Initiation? Planning? Execution?)
4. **Reference checklists and templates**: Each document includes actionable checklists and templates to guide your work

## How to Use These Docs

- **Keep the Project Charter updated** in your project repo
- **Add process-specific docs** to `.copilot/` or `.github/ISSUE_TEMPLATE/` if you want context-aware guidance from Copilot Spaces
- **Use issue templates** from `.github/ISSUE_TEMPLATE/` to standardize process documentation updates
- **Iterate and improve**: If you find gaps or improvements, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template

---

**Questions?** Reach out to your Product Lead or Project Manager. We're committed to continuous improvement and welcome feedback on these processes.
