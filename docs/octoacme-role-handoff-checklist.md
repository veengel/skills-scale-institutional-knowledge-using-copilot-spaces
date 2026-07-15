# OctoAcme — Role Interaction & Handoff Checklist

## Purpose
Provide a practical reference for cross-role handoffs at each phase of the project lifecycle. Use this checklist to ensure the right people are engaged at the right time and that nothing falls through the cracks between teams.

---

## Phase 1 — Initiation

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Problem statement and business case documented | Product Manager | Stakeholders | [ ] |
| Project One-pager drafted and shared for review | Project Manager | Product Manager, Engineering Manager | [ ] |
| Security and compliance requirements identified | Security/Compliance Representative | Product Manager, Engineering Manager | [ ] |
| Initial UX research or discovery scoped | UX/UI Designer | Product Manager | [ ] |
| High-level timeline and capacity reviewed | Engineering Manager | Project Manager | [ ] |
| Stakeholder sign-off on initiation gate | Project Manager | Product Manager, Stakeholders | [ ] |

---

## Phase 2 — Planning

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Backlog items created with acceptance criteria | Product Manager | UX/UI Designer, QA/Test Engineer | [ ] |
| UX designs reviewed and approved for build-ready items | UX/UI Designer | Product Manager, Developers | [ ] |
| Test strategy defined for the sprint/milestone | QA/Test Engineer | Developers, Product Manager | [ ] |
| Security requirements added to relevant backlog items | Security/Compliance Representative | Product Manager, Engineering Manager | [ ] |
| Dependencies and risks documented in risk register | Project Manager | Engineering Manager, DevOps/Platform Engineer | [ ] |
| CI/CD environment and branching conventions confirmed | DevOps/Platform Engineer | Engineering Manager, Developers | [ ] |
| Definition of Done reviewed and agreed by team | Project Manager | All delivery roles | [ ] |

---

## Phase 3 — Execution

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| PR includes issue link, acceptance criteria, and test evidence | Developer | QA/Test Engineer | [ ] |
| Code review completed (at least one approval) | Developers (reviewer) | Engineering Manager (for high-risk changes) | [ ] |
| Security review completed for sensitive changes | Security/Compliance Representative | Engineering Manager, Developers | [ ] |
| UX implementation reviewed for design fidelity | UX/UI Designer | Developers | [ ] |
| QA sign-off on feature acceptance | QA/Test Engineer | Developer, Product Manager | [ ] |
| Blockers escalated per escalation path | Project Manager | Engineering Manager, Product Manager | [ ] |
| Risk register updated | Project Manager | Engineering Manager, DevOps/Platform Engineer | [ ] |

---

## Phase 4 — Release Readiness

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| All acceptance criteria met and PRs merged | Project Manager | QA/Test Engineer, Developers | [ ] |
| Regression suite passed | QA/Test Engineer | Developers | [ ] |
| Release notes drafted | Project Manager | Product Manager | [ ] |
| Rollback plan documented and verified | DevOps/Platform Engineer | Engineering Manager | [ ] |
| Deployment window scheduled and communicated | DevOps/Platform Engineer | Project Manager | [ ] |
| Security and compliance checkpoint completed | Security/Compliance Representative | Project Manager | [ ] |
| Go/no-go decision recorded | Project Manager | Product Manager, Engineering Manager, QA/Test Engineer | [ ] |

---

## Phase 5 — Post-Release & Incident Response

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Post-deploy smoke tests executed | QA/Test Engineer | DevOps/Platform Engineer | [ ] |
| Release announcement sent to stakeholders | Project Manager | Product Manager | [ ] |
| Production health monitored (errors, latency, alerts) | DevOps/Platform Engineer | Engineering Manager | [ ] |
| Incident triggered (if needed) and on-call notified | DevOps/Platform Engineer | Engineering Manager, Project Manager | [ ] |
| Incident communication sent to stakeholders | Project Manager | DevOps/Platform Engineer | [ ] |
| Rollback executed if needed | DevOps/Platform Engineer | Engineering Manager | [ ] |
| Post-incident review scheduled | Project Manager | DevOps/Platform Engineer, Engineering Manager | [ ] |

---

## Phase 6 — Retrospective & Close

| Handoff / Action | Responsible | Supporting Roles | Done? |
|---|---|---|---|
| Retrospective facilitated | Project Manager | All delivery roles | [ ] |
| Action items captured and owners assigned | Project Manager | All delivery roles | [ ] |
| Success metrics reviewed | Product Manager | Project Manager | [ ] |
| Process improvement items added to backlog | Project Manager | Product Manager, Engineering Manager | [ ] |
| Project artifacts archived | Project Manager | All delivery roles | [ ] |

---

## Role Interaction Summary Matrix

The matrix below shows which roles are **primary (P)** or **supporting (S)** for common cross-functional activities.

| Activity | Project Manager | Product Manager | Engineering Manager | Developer | QA/Test Engineer | UX/UI Designer | DevOps/Platform Engineer | Security/Compliance Representative |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project initiation / charter | P | S | S | — | — | — | — | S |
| Backlog prioritization | S | P | S | S | S | S | — | S |
| UX review / design approval | — | S | — | S | S | P | — | — |
| Sprint planning | P | S | S | P | S | S | S | — |
| Security/threat review | S | S | S | S | — | — | S | P |
| PR code review | — | — | S | P | S | — | — | S |
| QA / acceptance sign-off | S | S | — | S | P | S | — | — |
| Release go/no-go | P | S | S | — | P | — | S | S |
| Deployment execution | S | — | S | — | S | — | P | — |
| Incident response | P | — | S | S | — | — | P | S |
| Retrospective facilitation | P | S | S | S | S | S | S | — |

**Legend:** P = Primary owner; S = Supporting contributor; — = Not typically involved

---

## How to use this checklist
- Copy the relevant phase checklists into your project planning doc or sprint board at the start of each phase.
- Mark items done and note blockers in your weekly status update.
- Use the Role Interaction Matrix to identify who to involve when starting a new activity or resolving an ambiguous ownership situation.
- Review and adapt this checklist in each retrospective to reflect team-specific process improvements.
