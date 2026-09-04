# OctoAcme Project Management Process Docs

## Overview
OctoAcme follows an iterative, customer-first project management approach that emphasizes clear ownership, data-informed decisions, and psychological safety. This folder contains detailed guidance for every phase of our project lifecycle and serves as the single entry point for project managers, product leads, engineers, QA, and stakeholders.

## Core Principles
- Customer-first: Prioritize customer value and usability
- Iterative delivery: Deliver small, testable increments
- Clear ownership: Each project has a named PM and Product Lead
- Data-informed: Measure impact and iterate based on evidence
- Psychological safety: Encourage feedback and learning

## Project Lifecycle
1. Initiation – Validate the business need, align stakeholders, and create a lightweight plan
2. Planning – Turn the approved initiative into an actionable plan and backlog
3. Execution – Manage day-to-day execution and track progress toward milestones
4. Release – Standardize how we deploy to production and manage risk
5. Close & Retrospective – Capture learnings and drive continuous improvement

## Process Documents
### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

### By Project Phase
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

### Cross-cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md)

## Quick Reference
### Communication Cadence
- Daily standups (15 min)
- Weekly PM + PdM sync
- Twice-weekly team standups
- Monthly stakeholder updates
- Sprint/milestone demos and retrospectives

### Key Artifacts at a Glance
- Project Charter / One-pager
- Prioritized backlog with acceptance criteria
- Release plan and milestone map
- Risk register
- Retrospective notes and action items

## How to Use These Docs
- Keep your Project Charter updated in your project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Adapt templates and checklists to your team's needs
- Use the escalation paths and communication templates during execution

## Summary of OctoAcme Project Management Processes
OctoAcme follows a structured lifecycle—initiation, planning, execution, release, and retrospective—designed to validate ideas early and deliver customer‑value iteratively. Initiation centers on a lightweight one‑pager that captures the problem, goals, and measurable success metrics and secures stakeholder alignment before work moves into planning. The planning phase breaks approved initiatives into shippable increments, defines acceptance criteria and a Definition of Done, and captures risks and dependencies in a Risk Register.

During execution, teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request workflow that emphasizes small, reviewable changes, CI gating (tests, linting, security scans), and clear PR descriptions that reference issues and acceptance criteria. Quality is enforced through unit and integration tests, end‑to‑end smoke checks for critical flows, security scanning in CI, and manual QA where necessary. Blocker escalation follows a tiered approach (team → PM → Product Lead → Sponsor) to surface issues efficiently.

Releases are classified as patch, minor, or major and require pre‑release checks including passing CI, drafted release notes, and a rollback plan. Deployments follow a checklist (staging verification, automated pipelines where possible, post‑deploy verification) and an incident playbook for rollbacks and triage. Post‑release retrospectives capture learnings and convert them into prioritized action items that are tracked in the backlog, ensuring continuous improvement.

Roles and communication cadence are explicit: PMs coordinate delivery and stakeholder communication, Product Managers own product outcomes and prioritization, Developers implement solutions, and QA validates acceptance. Regular touchpoints (daily standups, weekly syncs, demos, and monthly stakeholder updates) and templates for status and incident communication keep work transparent and aligned across teams.
