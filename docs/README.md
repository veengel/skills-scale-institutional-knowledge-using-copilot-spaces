# OctoAcme Project Management Docs

This README indexes OctoAcme's project management process documents and provides a concise summary of our approach: iterative delivery, clear ownership, data-informed decisions, and a repeatable cadence (daily standups, weekly syncs, sprint demos, and retrospectives). Use these docs as the canonical reference for initiation, planning, execution, release, risk management, and continuous improvement.

---

## Project Management Processes Overview

OctoAcme follows a structured **five-phase project lifecycle** designed to deliver customer value incrementally while maintaining quality and transparency.

### Five-Phase Lifecycle

| Phase | Goal |
|---|---|
| **1. Initiation** | Validate business need, align stakeholders, and create a lightweight Project One-pager with success metrics and key milestones. |
| **2. Planning** | Break work into a prioritized backlog with clear acceptance criteria, map dependencies, and establish a Definition of Done. |
| **3. Execution** | Build and deliver iteratively using daily standups, weekly delivery syncs, and GitHub Projects. Keep PRs small (≤ 400 lines) and require automated testing and peer review before merge. |
| **4. Release** | Run pre-release checklists covering acceptance criteria validation, CI/security scans, smoke tests, and documented rollback plans before deploying to production. |
| **5. Close & Retrospective** | Capture learnings, convert them into tracked action items with clear owners and timelines, and update process artifacts. |

### Core Principles

- **Customer-first** — prioritize customer value and usability in every decision.
- **Iterative delivery** — deliver small, testable increments and iterate based on feedback.
- **Clear ownership** — each project has a named Project Manager (PM) and Product Lead.
- **Data-informed decisions** — measure impact and adjust based on evidence.
- **Psychological safety** — encourage open feedback and blameless learning.

---

## Key Workflows

### Execution Cadence

| Cadence | Participants | Purpose |
|---|---|---|
| Daily standup | Delivery team | Surface blockers, align on daily priorities. |
| Weekly delivery sync | PM + delivery team | Review progress, update risk register, plan next sprint. |
| Weekly PM + Product Lead sync | PM, Product Lead | Align on scope, trade-offs, and stakeholder messaging. |
| Monthly stakeholder update | PM, Stakeholders | Communicate progress, risks, and decisions needed. |

### Risk & Communication

Risk management operates on three escalation levels:

- **Level 1** — Team-level triage during daily standups.
- **Level 2** — PM escalation to Product Lead and dependent teams.
- **Level 3** — Sponsor-level escalation for business-impacting issues.

A **Risk Register** tracks ID, description, impact, likelihood, owner, and mitigation status, reviewed at every weekly sync. Stakeholder communication follows a structured weekly status template: progress, next steps, risks/blockers, and decisions needed.

### Quality Assurance

Quality is embedded throughout execution:

- Unit tests, integration tests, and smoke tests for critical flows.
- Security scanning in CI on every pull request.
- Manual QA to validate feature acceptance criteria when needed.
- PR conventions: ≤ 400 lines, automated linting, peer review required before merge.

### Continuous Improvement

Structured retrospectives are held after every sprint, release, or milestone. These 45–75 minute timeboxed sessions produce:

- What went well and what could improve.
- 2–3 prioritized action items with clear owners and due dates.
- Improvements tracked in the project backlog or as GitHub issues.
- Outstanding actions reviewed at weekly PM syncs.

---

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level principles, core roles, key artifacts, and lifecycle summary. Start here for a quick orientation. |
| [Project Initiation Guide](octoacme-project-initiation.md) | One-pager template, stakeholder alignment steps, kickoff agenda, and decision gate for moving into Planning. |
| [Project Planning](octoacme-project-planning.md) | Backlog templates, sprint planning activities, Definition of Done, dependency mapping, and risk capture. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythm, GitHub Projects board conventions, PR workflows, quality standards, and reporting templates. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register format, escalation paths, stakeholder communication templates, and incident playbooks. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment runbook, rollback playbook, and release notes template. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, facilitation guide, action-item tracking, and improvement measurement. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Role descriptions, responsibilities, and decision-making authority for PM, PdM, Developers, QA, and Stakeholders. |

---

## How to Use These Docs

| Scenario | Recommended docs |
|---|---|
| **Onboarding a new team member** | Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md). |
| **Starting a new project** | Follow [Project Initiation Guide](octoacme-project-initiation.md), then [Project Planning](octoacme-project-planning.md). |
| **Day-to-day execution** | Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md). |
| **Preparing a release** | Use the [Release & Deployment Guide](octoacme-release-and-deployment.md) checklist and rollback playbook. |
| **Running a retrospective** | Follow the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide. |

---

## Contributing & Updates

To propose updates to any process document, open a GitHub issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template. Fill in:

1. **Which process document** you want to update (or select `<new document>` for a new file).
2. **Summary of new content** — a brief description of the change.
3. **Why it is needed** — gap, feedback, best practice alignment, etc.
4. **Suggested content** (optional) — paste the proposed text, checklist, or example.

Once the issue is reviewed and accepted, create a pull request on a new branch and reference the issue number in the PR description.
