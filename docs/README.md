# OctoAcme Project Management Docs

This README provides an overview of how project management is approached at OctoAcme, with quick access to all program process documents.

## Overview

OctoAcme's project management process is organized around a lightweight, end-to-end lifecycle with clear ownership and a small set of repeatable artifacts. Projects begin with **initiation**, where teams validate the business need, define SMART goals and success metrics, identify stakeholders and champions, and establish a high-level timeline before a go/no-go decision gate. If approved, the work moves into **planning**, where the initiative is decomposed into shippable increments with a prioritized backlog, estimates (e.g., T‑shirt sizing or story points), dependencies, milestones, and an explicit Definition of Done—all intended to support iterative delivery and data-informed decisions.

Roles and personas are explicitly defined to keep accountability crisp. The **Project Manager (PM)** coordinates delivery logistics—plans, timelines, risks, dependencies, and status reporting—and facilitates key ceremonies such as kickoff, planning, and retrospectives. The **Product Manager (PdM)** owns the "what" and "why" by shaping problem statements, outcomes, and prioritization, and by validating impact through user research and metrics. **Developers** are responsible for designing, building, testing, documenting, and participating in reviews. **QA/Testing** validates acceptance criteria and overall quality, while **Stakeholders/Sponsors** provide inputs and approvals at key decision points.

Communication is handled through a consistent cadence and a "single source of truth" approach. OctoAcme uses recurring touchpoints such as PM + PdM weekly alignment, regular team standups and syncs, demos at the end of sprints and milestones, and periodic stakeholder updates—backed by templates for weekly status reporting covering progress, next steps, risks/blockers, and decisions needed. Risks and dependencies are managed via a simple risk register (impact, likelihood, owner, mitigation, status) that is reviewed routinely, with a defined escalation path from team triage to PM/Product Lead and, if needed, sponsor-level escalation. Incident communications include a summary, actions, expected timelines, and a blameless retrospective.

Quality assurance is embedded throughout execution and release. Day-to-day delivery is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and reinforced with PR practices such as keeping changes small, linking issues and acceptance criteria in PR descriptions, running CI (tests/lint) before review, and requiring approvals before merge. Testing expectations include unit tests, integration tests where applicable, and end-to-end smoke tests for critical flows, plus security scanning in CI and manual QA for acceptance when needed. Releases follow standardized pre-release requirements (acceptance criteria met, CI/scans passing, release notes, rollback plan, smoke tests), staged deployments when appropriate, post-deploy verification, stakeholder and support announcements, and retrospectives that turn learnings into owned, time-bound backlog action items for continuous improvement.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

These documents are maintained collaboratively. Improvements are encouraged via issue template submissions, and changes are versioned within this repo.
