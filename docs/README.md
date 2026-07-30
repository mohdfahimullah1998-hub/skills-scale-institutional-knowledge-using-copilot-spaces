# OctoAcme Project Management Docs

This folder contains OctoAcme's program and process documents for project initiation, planning, execution, releases, retrospectives, risk management, and roles/personas. Use this README as the single source of truth to discover and navigate the full set of process docs used by the team.

## Summary
OctoAcme follows an iterative, customer-first approach that starts with a lightweight initiation and moves through planning, execution, release, and retrospective stages. Work is validated with a Project One-pager (problem, objective, success metrics) and a Decision Gate before moving into planning. Approved initiatives are broken into prioritized backlog items with clear acceptance criteria and a Definition of Done.

Execution emphasizes small, reviewable increments and visible tracking. The project board is structured (Backlog → Ready → In Progress → In Review → QA → Done) and pull requests are expected to be small, linked to an issue with acceptance criteria, and gated by CI and linting. Releases are classified (patch/minor/major) and require passing tests, security scans, release notes, smoke tests, and a rollback plan before production deployment.

Roles and communication are explicit: Product Managers (PdM) define outcomes and success metrics, Project Managers (PM) coordinate delivery and risk, Developers implement and test, and QA validates acceptance. Team cadence includes daily standups, weekly delivery syncs, sprint/milestone demos, and regular stakeholder updates. Risk management uses a simple risk register, weekly reviews, and a clear escalation path from team → PM → Product Lead → Sponsor.

Quality and continuous improvement are embedded across the lifecycle: unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA where needed. Retrospectives after sprints, releases, or incidents capture action items that are tracked back into the backlog and reviewed in PM syncs.

## Process Documents
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

## How to use this folder
- Reference these docs during project initiation, planning, execution, and retrospectives.
- Keep the One-pager, risk register, and release notes updated in this repository.
- Use the process update issue template in .github/ISSUE_TEMPLATE/ to request changes to these documents.
