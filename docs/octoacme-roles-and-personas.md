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

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master facilitates agile ceremonies, removes team impediments, and promotes continuous improvement. They protect the team's focus and help maintain a healthy delivery cadence.

### Responsibilities
- Organize and facilitate ceremonies: standups, sprint planning, reviews, and retrospectives
- Identify and remove blockers that prevent the team from progressing
- Coach the team on agile practices and the Definition of Done
- Track team velocity and flag capacity issues early
- Shield the team from unplanned interruptions during a sprint

### Goals
- Maximize team throughput and morale
- Reduce cycle time by resolving impediments quickly
- Foster a culture of continuous improvement

### Typical Communication
- Daily standups and retrospective facilitation
- Blocker escalation notes to Project Manager or Product Manager
- Sprint health summaries shared with stakeholders

### Interactions with Existing Roles
| Role | How they interact |
|---|---|
| Project Manager | Shares capacity and velocity data; co-owns escalations |
| Product Manager | Coordinates backlog readiness before sprint planning |
| Developers | Facilitates ceremonies; removes technical blockers |
| Business Analyst | Confirms stories are refined and ready for sprint |
| Stakeholders | Facilitates sprint reviews and demos |

---

## UX Designer

### Role Summary
The UX Designer focuses on user research, interaction design, and usability to ensure the product is intuitive and valuable to end-users.

### Responsibilities
- Conduct user research, interviews, and usability tests
- Create wireframes, mockups, and interactive prototypes
- Define and maintain the design system and accessibility standards
- Validate designs with stakeholders and real users before development begins
- Collaborate with developers on feasibility and implementation fidelity

### Goals
- Reduce rework caused by late-stage usability issues
- Ensure every feature solves a real user problem
- Maintain a consistent, accessible user experience

### Typical Communication
- Design reviews and prototype walkthroughs
- Research summaries shared with Product Manager and stakeholders
- Annotated design handoffs to Developers

### Interactions with Existing Roles
| Role | How they interact |
|---|---|
| Product Manager | Co-defines user stories and acceptance criteria; validates designs against product goals |
| Project Manager | Flags design dependencies and timeline needs during planning |
| Developers | Partners on implementation feasibility; reviews built UI against designs |
| Business Analyst | Aligns design requirements with documented business rules |
| Stakeholders | Presents prototypes for feedback before build begins |

---

## Business Analyst

### Role Summary
The Business Analyst bridges business needs and technical solutions by gathering requirements, documenting processes, and ensuring the team builds the right thing.

### Responsibilities
- Elicit and document requirements from business stakeholders and end-users
- Write clear acceptance criteria and user stories for backlog items
- Model business processes and identify gaps or inefficiencies
- Support sprint reviews by confirming delivered features meet requirements
- Maintain traceability between business objectives and delivered features

### Goals
- Eliminate ambiguity in requirements before work begins
- Reduce defects caused by misunderstood or missing acceptance criteria
- Ensure delivered features align with business outcomes

### Typical Communication
- Requirements workshops and stakeholder interviews
- Acceptance criteria documented in backlog items
- Process diagrams and decision tables shared with the team

### Interactions with Existing Roles
| Role | How they interact |
|---|---|
| Product Manager | Translates product vision into detailed, actionable requirements |
| Project Manager | Flags scope changes and requirement risks early |
| Developers | Clarifies requirements during refinement and answers questions in-sprint |
| UX Designer | Provides business rules and user context to inform designs |
| Stakeholders | Facilitates requirements gathering and validates sign-off |

---

## Support Engineer

### Role Summary
The Support Engineer provides post-release technical support, triages incoming issues, and acts as a feedback loop between end-users and the development team.

### Responsibilities
- Monitor and respond to incoming support requests and incidents
- Triage issues and reproduce bugs before escalating to Development
- Document recurring problems and surface trends to the Product team
- Coordinate communication with affected users during incidents
- Contribute to runbooks and knowledge base articles

### Goals
- Minimize user-impacting downtime and time-to-resolution
- Reduce repeat incidents through root-cause documentation
- Improve product quality by feeding user pain points back to the backlog

### Typical Communication
- Incident tickets and triage notes
- Escalation messages to on-call developers or Project Manager
- User-facing status updates and post-incident summaries

### Interactions with Existing Roles
| Role | How they interact |
|---|---|
| Developers | Escalates reproducible bugs; collaborates on hotfix verification |
| Project Manager | Reports incident status; flags patterns that may affect planning |
| Product Manager | Surfaces recurring user pain points for backlog consideration |
| Business Analyst | Provides field feedback to refine requirements and acceptance criteria |
| Stakeholders / Sponsors | Communicates incident status and resolution timelines |

---

## RACI / Ownership Summary

Quick reference for common recurring activities. **R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed.

| Activity | Project Manager | Product Manager | Developer | Scrum Master | UX Designer | Business Analyst | Support Engineer |
|---|---|---|---|---|---|---|---|
| Project kickoff | A/R | C | I | R | I | C | I |
| Backlog grooming | C | A | C | R | C | R | I |
| Acceptance criteria | I | A | C | I | C | R | I |
| Risk register maintenance | A/R | C | C | I | I | C | I |
| Release planning | A | C | R | C | I | I | C |
| Incident comms | C | I | R | I | I | I | A/R |
| Retrospectives | C | C | R | A/R | C | C | I |
| Design review | I | A | C | I | R | C | I |
| Requirements sign-off | C | A | I | I | C | R | I |

> See also: [Roles Interaction Cheatsheet](./octoacme-roles-interaction-cheatsheet.md) for a decision-focused quick reference.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

