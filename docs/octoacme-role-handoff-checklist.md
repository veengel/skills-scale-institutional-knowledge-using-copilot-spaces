# OctoAcme — Role Interaction & Handoff Checklist

## Purpose
Provide a practical reference for cross-role handoffs at each phase of the project lifecycle. Use this checklist to ensure the right people are engaged at the right time and that nothing falls through the cracks between teams.

---

## Phase 1 — Initiation

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Problem statement and business case documented | Product Manager | Executive Sponsor, Stakeholders | [ ] |
| Project One-pager drafted and shared for review | Project Manager | Product Manager, Engineering Manager, Technical Lead | [ ] |
| Executive Sponsor identified and project charter approved | Executive Sponsor | Project Manager, Product Manager | [ ] |
| Security and compliance requirements identified | Security/Compliance Representative | Product Manager, Engineering Manager | [ ] |
| Initial UX research or discovery scoped | UX/UI Designer | Product Manager | [ ] |
| High-level timeline and capacity reviewed | Engineering Manager | Project Manager, Delivery/Engineering Lead | [ ] |
| Technical approach and feasibility assessed | Technical Lead / Solution Architect | Engineering Manager, Product Manager | [ ] |
| Customer / user context and use-case requirements captured | Customer / User Representative | Product Manager, UX/UI Designer | [ ] |
| Stakeholder sign-off on initiation gate | Project Manager | Executive Sponsor, Product Manager, Stakeholders | [ ] |

---

## Phase 2 — Planning

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Backlog items created with acceptance criteria | Product Owner / Business Rep | Product Manager, UX/UI Designer, QA/Test Engineer | [ ] |
| UX designs reviewed and approved for build-ready items | UX/UI Designer | Product Manager, Developers, Customer / User Rep | [ ] |
| Test strategy defined for the sprint/milestone | QA/Test Engineer | Developers, Product Owner / Business Rep | [ ] |
| Security requirements added to relevant backlog items | Security/Compliance Representative | Product Manager, Engineering Manager, Technical Lead | [ ] |
| Architecture decisions and technical standards documented | Technical Lead / Solution Architect | Engineering Manager, Developers | [ ] |
| Dependencies and risks documented in risk register | Project Manager | Engineering Manager, Delivery/Engineering Lead, DevOps/Platform Engineer | [ ] |
| Release schedule and deployment plan established | Operations / Release Manager | Project Manager, DevOps/Platform Engineer | [ ] |
| CI/CD environment and branching conventions confirmed | DevOps/Platform Engineer | Engineering Manager, Developers | [ ] |
| Definition of Done reviewed and agreed by team | Project Manager | All delivery roles | [ ] |

---

## Phase 3 — Execution

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| PR includes issue link, acceptance criteria, and test evidence | Developer | QA/Test Engineer | [ ] |
| Code review completed (at least one approval) | Developers (reviewer) | Technical Lead (for architectural changes), Engineering Manager (for high-risk changes) | [ ] |
| Security review completed for sensitive changes | Security/Compliance Representative | Engineering Manager, Technical Lead, Developers | [ ] |
| UX implementation reviewed for design fidelity | UX/UI Designer | Developers | [ ] |
| QA sign-off on feature acceptance | QA/Test Engineer | Developer, Product Owner / Business Rep | [ ] |
| Delivery blockers identified and escalated | Delivery / Engineering Lead | Project Manager, Engineering Manager | [ ] |
| Blockers escalated per escalation path | Project Manager | Engineering Manager, Product Manager, Executive Sponsor (if required) | [ ] |
| Risk register updated | Project Manager | Engineering Manager, Delivery/Engineering Lead, DevOps/Platform Engineer | [ ] |

---

## Phase 4 — Release Readiness

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| All acceptance criteria met and PRs merged | Project Manager | QA/Test Engineer, Developers | [ ] |
| Regression suite passed | QA/Test Engineer | Developers | [ ] |
| User acceptance testing (UAT) completed | Customer / User Representative | Product Owner / Business Rep, QA/Test Engineer | [ ] |
| Release notes drafted | Project Manager | Product Manager, Product Owner / Business Rep | [ ] |
| Rollback plan documented and verified | DevOps/Platform Engineer | Operations / Release Manager, Engineering Manager | [ ] |
| Deployment window scheduled and communicated | Operations / Release Manager | DevOps/Platform Engineer, Project Manager | [ ] |
| Security and compliance checkpoint completed | Security/Compliance Representative | Operations / Release Manager, Project Manager | [ ] |
| Non-functional requirements validated (performance, scalability) | Technical Lead / Solution Architect | Developers, DevOps/Platform Engineer | [ ] |
| Go/no-go decision recorded | Operations / Release Manager | Project Manager, Product Owner / Business Rep, QA/Test Engineer, Security/Compliance Rep | [ ] |

---

## Phase 5 — Post-Release & Incident Response

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Post-deploy smoke tests executed | QA/Test Engineer | DevOps/Platform Engineer | [ ] |
| Release announcement sent to stakeholders | Project Manager | Product Manager, Operations / Release Manager | [ ] |
| Production health monitored (errors, latency, alerts) | DevOps/Platform Engineer | Operations / Release Manager, Engineering Manager | [ ] |
| Operational transition to support teams confirmed | Operations / Release Manager | DevOps/Platform Engineer, Project Manager | [ ] |
| Incident triggered (if needed) and on-call notified | DevOps/Platform Engineer | Engineering Manager, Project Manager, Operations / Release Manager | [ ] |
| Incident communication sent to stakeholders | Project Manager | DevOps/Platform Engineer, Operations / Release Manager | [ ] |
| Rollback executed if needed | DevOps/Platform Engineer | Operations / Release Manager, Engineering Manager | [ ] |
| Post-incident review scheduled | Project Manager | DevOps/Platform Engineer, Engineering Manager, Operations / Release Manager | [ ] |

---

## Phase 6 — Retrospective & Close

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Retrospective facilitated | Project Manager | All delivery roles | [ ] |
| Action items captured and owners assigned | Project Manager | All delivery roles | [ ] |
| Success metrics reviewed | Product Manager | Product Owner / Business Rep, Project Manager | [ ] |
| User adoption and satisfaction feedback reviewed | Customer / User Representative | Product Manager, Product Owner / Business Rep | [ ] |
| Process improvement items added to backlog | Project Manager | Product Manager, Engineering Manager, Operations / Release Manager | [ ] |
| Project artifacts archived | Project Manager | All delivery roles | [ ] |
| Executive Sponsor briefed on outcomes and lessons learned | Project Manager | Executive Sponsor, Product Manager | [ ] |

---

## Role Interaction Summary Matrix

The matrix below shows which roles are **primary (P)** or **supporting (S)** for common cross-functional activities. For full persona definitions, responsibilities, and decision rights of both original and new roles, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

| Activity | Exec Sponsor | Product Owner / Biz Rep | Project Manager | Product Manager | Technical Lead | Delivery / Eng Lead | Engineering Manager | Developer | QA/Test Engineer | UX/UI Designer | DevOps / Platform Eng | Operations / Release Mgr | Security / Compliance Rep | Customer / User Rep |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project initiation / charter | P | S | P | S | S | — | S | — | — | — | — | — | S | S |
| Backlog prioritization | — | P | S | P | S | S | — | S | S | S | — | — | S | S |
| Architecture / design decisions | — | — | — | — | P | S | S | S | — | — | S | — | S | — |
| UX review / design approval | — | S | — | S | — | — | — | S | S | P | — | — | — | S |
| Sprint planning | — | S | P | S | S | P | S | P | S | S | S | S | — | — |
| Security / threat review | — | — | S | S | P | — | S | S | — | — | S | — | P | — |
| PR code review | — | — | — | — | P | S | S | P | S | — | — | — | S | — |
| QA / acceptance sign-off | — | P | S | S | — | S | — | S | P | S | — | — | — | S |
| Release go/no-go | S | S | P | S | S | S | S | — | P | — | S | P | S | — |
| Deployment execution | — | — | S | — | — | S | S | — | S | — | P | P | — | — |
| Incident response | P | — | P | — | S | S | S | S | — | — | P | P | S | — |
| Retrospective facilitation | S | S | P | S | S | S | S | S | S | S | S | S | — | S |
| Escalation resolution | P | S | P | S | S | S | S | — | — | — | — | S | — | — |

**Legend:** P = Primary owner; S = Supporting contributor; — = Not typically involved

---

## How to use this checklist
- Copy the relevant phase checklists into your project planning doc or sprint board at the start of each phase.
- Mark items done and note blockers in your weekly status update.
- Use the Role Interaction Matrix to identify who to involve when starting a new activity or resolving an ambiguous ownership situation.
- On smaller teams, one person may hold multiple roles (e.g., Product Manager + Product Owner, Engineering Manager + Technical Lead). See [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for guidance on role overlap and flexible assignment.
- Review and adapt this checklist in each retrospective to reflect team-specific process improvements.
