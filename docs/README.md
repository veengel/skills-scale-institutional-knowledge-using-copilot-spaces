# OctoAcme Project Management Docs

Welcome to OctoAcme's project management process documentation. This README indexes all process guides and provides a concise overview of our approach to delivering projects with clear ownership, iterative delivery, and continuous improvement.

## Project Management Processes Overview

OctoAcme follows a structured five-phase project lifecycle designed to balance planning with agility, reduce risk, and maintain stakeholder alignment throughout delivery.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments and iterate based on metrics
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and adjust based on evidence
- **Psychological safety**: Encourage feedback and learning across the team

### Key Workflows

**Lifecycle Phases:**
1. **Initiation** — Validate business need, align stakeholders, and create a Project One-pager with success metrics and high-level timeline
2. **Planning** — Break work into prioritized backlog items with acceptance criteria, identify dependencies, and establish Definition of Done
3. **Execution** — Build, test, and iterate through a repeating cadence of daily standups, weekly syncs, and sprint demos; enforce quality via CI checks and PR reviews
4. **Release** — Deploy to production with pre-release checklists, smoke tests, and documented rollback plans
5. **Close & Retrospective** — Capture learnings, track action items, and measure improvements

**Execution Cadence:**
- Daily standups (15 min) — focus on progress, blockers, and dependencies
- Weekly delivery sync — review progress, flag risks, and resolve blockers
- Weekly PM sync — align on priorities and stakeholder updates
- Sprint/milestone demos — showcase work and gather feedback
- Post-sprint retrospectives — capture learnings and prioritize improvements

### Risk & Communication

- **Risk management** operates on three escalation levels: team-level triage, PM escalation to Product Lead, and sponsor-level escalation
- **Risk Register** tracks ID, description, impact, likelihood, owner, and mitigation status—reviewed at weekly syncs
- **Stakeholder communication** follows structured templates (weekly status, incident playbooks) to maintain transparency
- **Escalation paths** ensure critical issues reach decision-makers quickly

### Quality Assurance

- Unit, integration, and end-to-end smoke tests for critical flows
- Security scanning in CI before merge
- Small PR discipline (≤400 lines) with mandatory CI checks and peer review
- Manual QA for feature acceptance when needed
- Definition of Done ensures consistent quality standards

### Continuous Improvement

- Retrospectives held after each sprint, release, or milestone (45–75 min)
- Action items tracked with clear owners, due dates, and success criteria
- Improvements reviewed in weekly PM syncs and added to future sprints
- Iterative refinement of processes based on team feedback and metrics

---

## Documents

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level principles, core roles, key artifacts, and the five-phase lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Initial steps to validate and authorize work; includes One-pager template and decision gate |
| [Project Planning](octoacme-project-planning.md) | Turn approved initiatives into actionable plans; includes backlog template and risk capture |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm, PR workflow, quality standards, and reporting |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, risk lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, pre-release checklist, deployment process, rollback playbook, and release notes template |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and continuous improvement practices |
| [Roles & Personas](octoacme-roles-and-personas.md) | Role descriptions and responsibilities for Developers, Product Managers, and Project Managers |

---

## How to Use These Docs

- **Onboarding new team members**: Start with [Project Management Overview](octoacme-project-management-overview.md), then reference role-specific docs and [Roles & Personas](octoacme-roles-and-personas.md)
- **Starting a new project**: Follow the [Project Initiation Guide](octoacme-project-initiation.md) → [Project Planning](octoacme-project-planning.md) → [Execution & Tracking](octoacme-execution-and-tracking.md)
- **During execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for day-to-day guidance
- **Before release**: Use the [Release & Deployment Guide](octoacme-release-and-deployment.md) checklist
- **After project or sprint**: Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- **Linking to this README**: Reference this docs folder from project charters, onboarding materials, and the main repository README

---

## Contributing & Updates

To update or add new content to these process documents:
1. Open an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Propose changes for stakeholder review
3. Submit a pull request and link it to the issue
4. Ensure updates align with existing processes and close documented gaps

For questions or process improvements, reach out to your Project Manager or Product Lead.
