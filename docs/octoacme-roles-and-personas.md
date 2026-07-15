# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Engineering Manager

### Role Summary
Engineering Managers provide technical leadership and team health oversight. They partner with Project Managers on capacity planning, dependencies, and risk identification, while supporting Developers through mentoring and architectural guidance.

### Responsibilities
- Set technical direction and enforce architecture guardrails
- Manage capacity, staffing, and skill-gap planning
- Identify and resolve technical dependencies and cross-team blockers
- Mentor Developers and uphold engineering quality standards
- Represent engineering in planning and trade-off discussions

### Goals
- Deliver technically sound, maintainable solutions
- Ensure the team has the capacity and clarity to execute
- Bridge engineering and product strategy

### Typical Communication
- Weekly syncs with Project Managers and Product Managers on scope, timeline, and technical risks
- Architecture decision records (ADRs) and technical design docs
- 1:1s and team retrospectives with Developers

### Interaction with Existing Roles
- **Project Managers:** aligns on timelines, surfacing capacity constraints and dependency risks early
- **Product Managers:** negotiates scope trade-offs and technical feasibility
- **Developers:** provides guidance on implementation approach, code quality, and career growth

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered designs, interaction flows, and prototypes. They validate usability and accessibility to ensure features meet user needs and meet the product's quality bar before and during development.

### Responsibilities
- Develop user flows, wireframes, and high-fidelity prototypes
- Conduct usability research and synthesize findings
- Define and uphold accessibility standards (WCAG compliance)
- Partner with engineering on implementation feasibility
- Validate UX acceptance criteria with QA/Test Engineers

### Goals
- Deliver intuitive, accessible experiences
- Reduce rework by resolving UX ambiguity before development starts
- Bridge user research insights and engineering execution

### Typical Communication
- Design reviews and prototype walkthroughs with Product Managers and Developers
- Accessibility and UX acceptance notes shared with QA/Test Engineers
- Figma/design system links included in feature specs and PRs

### Interaction with Existing Roles
- **Product Managers:** co-defines problem framing, user outcomes, and acceptance criteria
- **Developers:** reviews implementation for design fidelity and flags deviations early
- **QA/Test Engineers:** provides UX acceptance criteria and participates in usability sign-off

---

## QA/Test Engineer

### Role Summary
QA/Test Engineers own the test strategy and quality gate for each feature and release. They validate that acceptance criteria are met, maintain regression coverage, and surface quality risks before production.

### Responsibilities
- Define and maintain test strategies (unit, integration, end-to-end, accessibility)
- Validate feature acceptance criteria with Product Managers
- Manage regression suites and track test coverage
- Report quality risks and defect trends to Project Managers
- Coordinate go/no-go quality readiness for each release

### Goals
- Prevent regressions and quality escapes to production
- Ensure acceptance criteria are clear and verifiable before development starts
- Reduce manual test burden through automation

### Typical Communication
- QA status updates in weekly delivery syncs
- Defect triage sessions with Developers and Engineering Managers
- Quality readiness sign-off shared with Project Managers and Release owners

### Interaction with Existing Roles
- **Developers:** collaborates on testability requirements and defect triage
- **Product Managers:** aligns on acceptance criteria and feature completeness
- **Project Managers:** provides quality readiness reports and flags release-blocking risks
- **UX/UI Designers:** validates UX acceptance and accessibility requirements

---

## DevOps / Platform Engineer

### Role Summary
DevOps/Platform Engineers maintain CI/CD pipelines, deployment automation, and production environment health. They ensure reliable, repeatable deployments and prepare rollback plans to minimize production risk.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment tooling
- Monitor environment health, observability, and alerting
- Establish and document deployment runbooks and rollback procedures
- Coordinate release windows and deployment logistics with Project Managers
- Ensure infrastructure meets security and compliance requirements

### Goals
- Achieve reliable, low-friction deployments
- Reduce mean time to recovery (MTTR) for production incidents
- Improve observability and on-call readiness across the team

### Typical Communication
- Release readiness updates and deployment window coordination with Project Managers
- Runbooks and incident playbooks shared with on-call teams
- Post-incident reviews and infrastructure change notes

### Interaction with Existing Roles
- **Developers:** defines operability requirements (logging, metrics, health checks) and reviews infra-as-code changes
- **Project Managers:** aligns on release windows and communicates deployment risks
- **QA/Test Engineers:** coordinates staging environment availability and smoke test execution
- **Stakeholders:** provides production health updates and incident status during incidents

---

## Security/Compliance Representative

### Role Summary
Security/Compliance Representatives ensure that features, architectures, and processes meet the organization's security standards and regulatory obligations. They are embedded in the delivery process to catch risks early, not just at release gates.

### Responsibilities
- Conduct threat modeling and security reviews for new features and integrations
- Define security requirements and acceptance criteria for sensitive work
- Maintain the compliance checklist and risk register entries related to security
- Guide escalation paths for security incidents
- Review and approve changes with significant security or compliance impact

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure the team understands and meets compliance obligations
- Shift security review left to reduce late-stage rework

### Typical Communication
- Security review outcomes and requirements added to feature specs and the risk register
- Compliance checkpoints documented in the Project One-pager and release checklist
- Escalation guidance shared with Project Managers and Engineering Managers

### Interaction with Existing Roles
- **Developers and Engineering Managers:** provides secure implementation guidance and reviews high-risk code or architecture changes
- **Project Managers:** contributes security items to the risk register and escalation paths
- **Product Managers:** advises on security-related scope decisions and compliance constraints
- **DevOps/Platform Engineers:** reviews infrastructure and pipeline configurations for security posture

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

