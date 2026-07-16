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

## Executive Sponsor

### Role Summary
The Executive Sponsor owns the business case, secures organizational funding and support, and provides strategic direction for the project. They are the ultimate escalation point for decisions that exceed the project team's authority and hold accountability for the project's business outcomes.

### Responsibilities
- Own and champion the business case and project vision at the organizational level
- Secure funding, staffing authorization, and executive support
- Resolve escalated decisions that are beyond the project team's authority
- Set and communicate success expectations to senior stakeholders and leadership
- Remove organizational blockers that the Project Manager cannot resolve

### Decision Rights
- Final authority on go/no-go decisions with significant strategic or financial impact
- Approves major scope changes, budget overruns, or schedule extensions
- Determines outcomes for escalations that cross team or organizational boundaries

### Lifecycle Involvement
- **Initiation:** sponsors and approves the project charter; defines strategic success criteria
- **Planning:** reviews resource allocation and approves the baseline plan
- **Execution:** attends periodic governance check-ins; intervenes on critical escalations
- **Release:** approves go/no-go for high-visibility or high-risk releases
- **Retrospective:** reviews delivery outcomes against strategic and business goals

### Typical Communication
- Executive briefings and governance reviews (bi-weekly or milestone-driven)
- Receives condensed status summaries and escalation requests from the Project Manager
- Sponsors major stakeholder announcements and release communications

### Interaction with Existing Roles
- **Project Managers:** primary liaison for escalations and key approvals; receives regular condensed status updates
- **Product Managers:** aligns product direction with business strategy and investment goals
- **Engineering Manager:** reviews capacity and technical risk at a strategic level when escalated
- **Stakeholders:** sets organizational expectations and communicates executive priorities

---

## Product Owner / Business Representative

### Role Summary
The Product Owner or Business Representative is the voice of the customer and business within the delivery team. They define and prioritize requirements, clarify acceptance criteria, and approve completed work on behalf of the business. On smaller teams this role may be fulfilled by the Product Manager; on larger engagements a dedicated business stakeholder or product owner serves as the primary decision-maker for scope and value.

### Responsibilities
- Represent business and customer priorities within the delivery team
- Own and manage the product backlog, ensuring items are refined, prioritized, and ready for development
- Clarify and approve acceptance criteria for each feature or user story
- Approve or reject completed work during sprint reviews or demonstrations
- Authorize scope trade-offs and change requests within the agreed project budget

### Decision Rights
- Final say on backlog priority and scope trade-offs within delegated authority
- Approves acceptance of completed features before they proceed to release
- Escalates budget or scope changes that exceed delegated authority to the Executive Sponsor

### Lifecycle Involvement
- **Initiation:** contributes business requirements and success criteria to the project charter
- **Planning:** owns backlog refinement; defines sprint or milestone acceptance criteria
- **Execution:** answers developer and QA questions; approves completed features in sprint reviews
- **Release:** reviews release scope and approves readiness from a business perspective
- **Retrospective:** evaluates whether business outcomes and value delivery met expectations

### Typical Communication
- Sprint or iteration reviews and feature demonstrations
- Backlog grooming and prioritization sessions with the delivery team
- Change request decisions documented in the project decision log

### Interaction with Existing Roles
- **Product Managers:** collaborates on roadmap direction; may be the same person on smaller teams
- **Project Managers:** aligns on scope, schedule, and escalation paths for business decisions
- **QA/Test Engineers:** reviews and approves acceptance criteria and feature completeness
- **Developers:** answers functional questions and unblocks the team during development
- **UX/UI Designers:** co-defines user acceptance criteria and validates workflow designs

---

## Technical Lead / Solution Architect

### Role Summary
The Technical Lead or Solution Architect owns the technical direction and quality of the solution design. They ensure the system meets non-functional requirements — performance, scalability, security, and maintainability — and serve as the escalation point for complex technical trade-offs. This role is distinct from the Engineering Manager: where the Engineering Manager focuses on team health and organizational execution, the Technical Lead focuses on the quality and soundness of the technical solution.

### Responsibilities
- Define and maintain the solution architecture and key design decisions
- Establish and document technical standards, patterns, and guardrails for the project
- Lead technical spikes and proof-of-concept work for high-uncertainty features
- Estimate technical effort and surface architecture-related risks to the project team
- Review and approve significant architectural changes or high-risk implementations

### Decision Rights
- Final authority on architecture patterns, technology selection, and technical standards within the project
- Escalates decisions with cross-system or cross-team technical impact to the Engineering Manager
- Provides sign-off on architecturally significant changes before merging

### Lifecycle Involvement
- **Initiation:** defines technical approach and feasibility; identifies major technical risks for the charter
- **Planning:** produces architecture decisions and guides effort estimation
- **Execution:** reviews designs and implementations for architectural compliance; unblocks technical blockers
- **Release:** validates that non-functional requirements (performance, security, scalability) are satisfied
- **Retrospective:** captures architectural lessons learned and proposes updates to design standards

### Typical Communication
- Architecture decision records (ADRs) and technical design documents
- Code review comments on architecturally significant changes
- Technical risk entries in the project risk register

### Interaction with Existing Roles
- **Developers:** provides architectural guidance, reviews implementation decisions, and unblocks design questions
- **Engineering Manager:** aligns on technical standards, team capacity, and cross-team dependencies
- **Security/Compliance Representative:** incorporates security and compliance requirements into architecture decisions early
- **DevOps/Platform Engineers:** ensures architecture aligns with deployment, observability, and infrastructure constraints
- **Product Owner / Business Representative:** advises on technical feasibility and the implications of scope trade-offs

---

## Delivery / Engineering Lead

### Role Summary
The Delivery or Engineering Lead coordinates the day-to-day execution of technical work within a team or squad. They focus on unblocking the team, tracking progress, managing intra-team dependencies, and ensuring delivery quality and pace. On smaller teams this role may be held by a senior developer or Engineering Manager; on larger programs it is a dedicated coordination role.

### Responsibilities
- Coordinate daily execution tasks, sprint goals, and intra-team dependencies
- Identify and remove delivery blockers; escalate when resolution requires external involvement
- Track team velocity, capacity, and forecasted delivery against the plan
- Facilitate technical standups and working-level coordination sessions
- Ensure engineering practices (code review, testing, documentation) are followed consistently

### Decision Rights
- Resolves day-to-day execution trade-offs and task priorities within the sprint
- Escalates cross-team dependencies and blockers to the Project Manager or Engineering Manager

### Lifecycle Involvement
- **Planning:** participates in sprint planning; confirms team capacity and task breakdown
- **Execution:** primary contact for day-to-day progress; surfaces impediments daily
- **Release:** communicates final feature status and remaining delivery risks to the Project Manager
- **Retrospective:** captures execution-level process gaps and proposes actionable improvements

### Typical Communication
- Daily standups and team-level progress updates
- Dependency and blocker escalations to Project Managers
- Execution status reflected in the project board or tracking tool

### Interaction with Existing Roles
- **Project Managers:** primary delivery partner for tracking, forecasting, and escalating blockers
- **Technical Lead / Solution Architect:** coordinates on design questions and implementation approach
- **Developers:** facilitates daily coordination and removes execution impediments
- **QA/Test Engineers:** aligns on testing readiness and coordinates defect resolution to maintain pace

---

## Operations / Release Manager

### Role Summary
The Operations or Release Manager coordinates release readiness across teams and owns the operational aspects of the deployment process. They ensure environment readiness, deployment logistics, rollback planning, and the transition to ongoing operations are in place before any release proceeds. This role complements the DevOps/Platform Engineer's focus on pipeline and infrastructure by owning cross-team release coordination and the go/no-go process.

### Responsibilities
- Own the end-to-end release schedule, deployment windows, and stakeholder communications
- Coordinate release readiness reviews across engineering, QA, security, and operations
- Ensure operational runbooks, monitoring dashboards, and rollback procedures are ready before release
- Facilitate go/no-go meetings and document the decision with clear rationale
- Manage post-release verification and escalate production issues to the appropriate teams

### Decision Rights
- Calls or recommends go/no-go for each release in coordination with the Project Manager, QA/Test Engineer, and Security Representative
- Owns decisions on release window timing and deployment sequence
- Escalates critical release blockers to the Project Manager or Executive Sponsor

### Lifecycle Involvement
- **Planning:** establishes the release schedule and communication plan; identifies deployment dependencies
- **Execution:** monitors release blockers and readiness status throughout the sprint or milestone
- **Release:** owns deployment coordination, go/no-go facilitation, and post-deploy verification
- **Post-release:** coordinates incident response handoffs and confirms operational transition to support teams
- **Retrospective:** reviews release efficiency and captures improvements to the release process

### Typical Communication
- Release readiness reports and go/no-go decision records shared with all delivery teams
- Deployment window notifications to stakeholders
- Post-release status updates and incident handoff notes

### Interaction with Existing Roles
- **Project Managers:** joint ownership of the release schedule and escalation path; shares release readiness updates
- **DevOps/Platform Engineers:** relies on pipeline and infrastructure readiness; coordinates deployment execution
- **QA/Test Engineers:** confirms quality readiness and regression sign-off before calling go/no-go
- **Security/Compliance Representatives:** confirms compliance and security checkpoint completion before release
- **Stakeholders:** communicates release timing, scope, and any post-release issues

---

## Customer / User Representative

### Role Summary
The Customer or User Representative brings the direct perspective of end users into the delivery process. They validate that the product meets real-world user needs, participate in demonstrations and acceptance testing, and provide feedback that shapes feature refinement and prioritization. This role is distinct from the Product Owner/Business Representative: where the Product Owner holds business prioritization authority, the Customer/User Representative focuses on user experience, adoption, and real-world workflow validation.

### Responsibilities
- Provide user context, workflows, and real-world usage scenarios during planning and design
- Participate in sprint reviews, feature demonstrations, and user acceptance testing (UAT)
- Validate that features meet usability, accessibility, and workflow expectations
- Provide adoption and change-management feedback after release
- Communicate user-facing issues or gaps back to the product and project team

### Decision Rights
- Provides input and feedback on acceptance criteria and feature completeness; formal acceptance authority typically remains with the Product Owner / Business Representative
- Escalates user adoption or usability risks to the Product Owner or Project Manager

### Lifecycle Involvement
- **Initiation:** contributes user research insights and use-case context to the project charter
- **Planning:** reviews and validates user stories and acceptance criteria for real-world accuracy
- **Execution:** participates in feature demonstrations and provides early usability feedback
- **Release:** participates in UAT and provides readiness feedback from the user perspective
- **Retrospective:** shares adoption and satisfaction feedback; contributes to improvement priorities

### Typical Communication
- Sprint reviews and UAT sessions
- Feedback captured in issue trackers, surveys, or structured user research sessions
- Adoption reports shared with the Product Owner and Project Manager after release

### Interaction with Existing Roles
- **Product Owner / Business Representative:** primary partner; provides user validation to inform business prioritization decisions
- **UX/UI Designers:** participates in usability research and design validation sessions
- **QA/Test Engineers:** collaborates on UAT test scenarios and real-world acceptance criteria
- **Project Managers:** communicates adoption risks and UAT readiness during release planning

---

## Role Overlap and Flexible Assignment

On small teams or simpler projects, one person may hold multiple personas. The following combinations are common:

- **Product Manager + Product Owner/Business Representative:** the same person owns both product strategy and backlog/acceptance authority.
- **Engineering Manager + Technical Lead/Solution Architect:** the same person leads both team health and technical direction.
- **Engineering Manager + Delivery/Engineering Lead:** the same person handles both organizational concerns and day-to-day delivery coordination.
- **DevOps/Platform Engineer + Operations/Release Manager:** the same person owns both pipeline/infrastructure and release coordination.

Even when roles are consolidated, accountability and handoff expectations should remain explicit. Document which person owns each responsibility in the project charter or team agreement so that gaps and escalation paths are clear regardless of team size. See [`octoacme-role-handoff-checklist.md`](octoacme-role-handoff-checklist.md) for phase-by-phase ownership guidance.

---

## Expanded Roles Interaction Matrix

The matrix below shows which roles are **primary (P)** or **supporting (S)** across key project activities, including both the original and newly defined personas. For a phase-by-phase handoff checklist, see [`octoacme-role-handoff-checklist.md`](octoacme-role-handoff-checklist.md).

| Activity | Executive Sponsor | Product Owner / Biz Rep | Project Manager | Product Manager | Technical Lead / Architect | Delivery / Eng Lead | Engineering Manager | Developer | QA/Test Engineer | UX/UI Designer | DevOps / Platform Eng | Operations / Release Mgr | Security / Compliance Rep | Customer / User Rep |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project charter / initiation | P | S | P | S | S | — | S | — | — | — | — | — | S | S |
| Budget and resource approval | P | S | S | S | — | — | S | — | — | — | — | — | — | — |
| Backlog refinement and priority | — | P | S | P | S | S | — | S | S | S | — | — | S | S |
| Architecture and design decisions | — | — | — | — | P | S | S | S | — | — | S | — | S | — |
| Sprint / iteration planning | — | S | P | S | S | P | S | P | S | S | S | S | — | — |
| Security and threat review | — | — | S | S | S | — | S | S | — | — | S | — | P | — |
| UX review and design approval | — | S | — | S | — | — | — | S | S | P | — | — | — | S |
| QA and acceptance sign-off | — | P | S | S | — | S | — | S | P | S | — | — | — | S |
| Release go/no-go decision | S | S | P | S | S | S | S | — | P | — | S | P | S | — |
| Deployment execution | — | — | S | — | — | S | S | — | S | — | P | P | — | — |
| Post-release monitoring | — | — | S | — | — | — | S | S | S | — | P | P | — | — |
| Incident response | S | — | P | — | S | S | S | S | — | — | P | P | S | — |
| Retrospective facilitation | S | S | P | S | S | S | S | S | S | S | S | S | — | S |
| Escalation resolution | P | S | P | S | S | S | S | — | — | — | — | S | — | — |

**Legend:** P = Primary owner; S = Supporting contributor; — = Not typically involved

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For phase-by-phase handoff checklists and a condensed interaction matrix covering the original roles, see [`octoacme-role-handoff-checklist.md`](octoacme-role-handoff-checklist.md).

