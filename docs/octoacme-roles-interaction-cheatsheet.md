# OctoAcme — Roles Interaction Cheatsheet

Quick reference for **who to involve** when making key decisions or carrying out recurring activities.

> Full role descriptions: [Roles & Personas](./octoacme-roles-and-personas.md)  
> RACI ownership table: see the [RACI / Ownership Summary](./octoacme-roles-and-personas.md#raci--ownership-summary) section in Roles & Personas.

---

## Key Decision Points

| Decision / Activity | Who is Accountable | Who Must Be Consulted | Who Should Be Informed |
|---|---|---|---|
| Approve scope change | Product Manager | Project Manager, Business Analyst | Developers, Sponsor |
| Prioritize backlog | Product Manager | Business Analyst, UX Designer | Developers, Scrum Master |
| Define acceptance criteria | Business Analyst | Product Manager, UX Designer | Developers, QA |
| Approve release to production | Project Manager | Developers, Support Engineer | Stakeholders, Sponsor |
| Declare and manage an incident | Support Engineer | Developers, Project Manager | Product Manager, Stakeholders |
| Decide rollback during deployment | Developers (on-call) | Project Manager, Support Engineer | Product Manager, Stakeholders |
| Approve design solution | Product Manager | UX Designer, Business Analyst | Developers, Stakeholders |
| Escalate a blocker (Level 2+) | Project Manager | Product Manager, Scrum Master | Sponsor, Developers |
| Close a retrospective action item | Scrum Master | Project Manager, Developers | Product Manager |
| Sign off on requirements | Business Analyst | Product Manager, Stakeholders | Project Manager, Developers |

---

## Common Ceremonies — Who Should Attend

| Ceremony | Required | Optional |
|---|---|---|
| Project Kickoff | Project Manager, Product Manager, Developer lead, Sponsor | UX Designer, Business Analyst, Support Engineer |
| Sprint Planning | Scrum Master, Developers, Product Manager | Business Analyst, Project Manager |
| Backlog Grooming / Refinement | Product Manager, Business Analyst, Scrum Master | UX Designer, Developers |
| Sprint Review / Demo | Product Manager, Developers, Scrum Master | Stakeholders, Support Engineer, UX Designer |
| Retrospective | Scrum Master, Developers, Project Manager | Product Manager, Business Analyst |
| Risk Review | Project Manager | Product Manager, Business Analyst, Developers |
| Release Planning | Project Manager, Developers | Support Engineer, Product Manager, UX Designer |
| Incident Triage | Support Engineer, Developers (on-call) | Project Manager, Product Manager |

---

## Escalation Path at a Glance

```
Blocker identified
       ↓
Level 1: Team triage (Scrum Master + Developers, in standup)
       ↓ (unresolved same day)
Level 2: Project Manager escalates to Product Manager and dependent teams
       ↓ (business impact or cross-org dependency)
Level 3: Sponsor-level escalation (Project Manager + Product Manager → Sponsor)
```

---

## Quick-Reference: Role → Go-To For

| If you need… | Contact |
|---|---|
| Scope or priority decision | Product Manager |
| Schedule, timeline, or capacity | Project Manager |
| Requirement clarification | Business Analyst |
| Design or UX guidance | UX Designer |
| Agile process or ceremony help | Scrum Master / Delivery Facilitator |
| Production issue or user complaint | Support Engineer |
| Technical feasibility | Developer lead |
