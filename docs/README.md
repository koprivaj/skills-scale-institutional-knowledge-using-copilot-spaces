# OctoAcme Project Management Documentation

This README provides an overview of project management processes at OctoAcme and links to all detailed process documentation in this folder.

## Overview

OctoAcme's project management approach is designed to be lightweight, iterative, and easy to onboard to, with clear ownership and measurable outcomes. Projects follow a consistent lifecycle: **initiation**, **planning**, **execution**, **release**, and **close/retrospective**. During initiation, teams validate the business need and define success up front via a Project One-pager (problem statement, SMART objective, success metrics), identify stakeholders, outline a high-level timeline, and capture early risks and resource needs. The goal is a clear decision gate—only moving into planning when outcomes, priorities, and team availability are aligned.

Planning turns the approved initiative into an actionable backlog and release path. OctoAcme emphasizes breaking work into shippable increments, prioritizing backlog items with explicit acceptance criteria, estimating scope (T-shirt sizing or story points), and documenting a Definition of Done. Dependencies and risks are explicitly tracked via a risk register and surfaced through regular syncs. Planning also includes kickoff alignment with stakeholders, drafting an initial test/QA approach, and mapping milestones to releases so delivery can proceed predictably.

Execution and day-to-day tracking centers on a visible workflow and a steady team cadence. Work is managed on a project board (e.g., GitHub Projects) moving through stages: Backlog → Ready → In Progress → In Review → QA → Done. The pull request workflow is optimized for small, reviewable changes—PRs link to issues with acceptance criteria, CI checks must pass before review, and at least one approval is required before merge. The team rhythm includes daily standups for blockers, weekly delivery syncs for progress and flagged risks, and demos at sprint or milestone boundaries. Escalation is structured: team triage first, then PM escalation to product/dependent teams, and sponsor-level escalation for business-impacting issues.

Roles and communication expectations are explicit to maintain alignment across stakeholders. **Project Managers** coordinate delivery (plans, risks, communications, facilitation), **Product Managers** define outcomes and prioritize based on impact, and **Developers** and **QA/Testing** ensure implementation quality and acceptance. Stakeholder communication uses a single source of truth (project README or release doc) and recurring updates (weekly PM+PdM alignment, monthly stakeholder updates, plus ad-hoc escalation). Quality assurance is built into the workflow through unit and integration testing, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Releases require acceptance criteria completion, passing CI/scans, release notes, and rollback/mitigation planning. After sprints, releases, or incidents, retrospectives capture learnings and convert them into owned, trackable action items to drive continuous improvement.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning Guide](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
