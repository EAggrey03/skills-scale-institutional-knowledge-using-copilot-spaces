# OctoAcme Project Management Docs

This README aggregates the OctoAcme project management process documents and provides a short summary of the processes.

## Summary
OctoAcme runs projects using a lightweight, iterative lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation centers on a Project One-pager that captures the problem, measurable outcomes, stakeholders, timeline, and initial risks; that one-pager is the gate to planning. Planning breaks approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, and a release plan. Execution uses a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and emphasizes small, testable increments and frequent demos, while release guidance defines pre-release checks, deployment steps, rollback plans, and release-note templates.

Workflows enforce disciplined PR and CI practices: small pull requests (target <= 400 lines), PRs must include issue links and acceptance criteria, automated tests and linting run in CI before reviews, and at least one approval is required to merge. Backlog items follow a template (title, description, acceptance criteria, owner, estimate) so work is reviewable and shippable. Risk and dependency management is explicit—teams maintain a Risk Register (ID, impact, likelihood, owner, mitigation) and mark cross-team dependencies on the board, escalating them during weekly syncs as needed.

Roles and team rhythm are clearly defined: Product Managers set outcomes and prioritize the backlog, Project Managers coordinate schedules/risks/communications, Developers implement and test, QA validates quality, and stakeholders provide inputs and approvals. The cadence includes 15-minute daily standups focused on progress and blockers, weekly delivery syncs for progress and risk review, and demos/reviews at the end of each sprint or milestone. Retrospectives follow a timeboxed structure to capture what went well, what to improve, and 2–3 action items that are tracked back into the backlog.

Quality assurance and communication practices are embedded throughout: unit, integration, and end-to-end smoke tests are expected, security scanning runs in CI, and manual QA is used for feature acceptance when needed. Pre-release smoke tests and a deployment checklist (staging verification, backups if needed, post-deploy checks) reduce production risk. Communication is standardized with weekly status templates (progress, next steps, risks/blockers, asks) and defined escalation paths (team → PM → Product Lead → Sponsor), plus incident communication and a blameless post-incident retrospective process.

## Process documents
- docs/octoacme-project-management-overview.md — Project management overview, roles, and key artifacts
- docs/octoacme-project-initiation.md — Project initiation guide and one-pager template
- docs/octoacme-project-planning.md — Planning activities, backlog templates, and risk management
- docs/octoacme-execution-and-tracking.md — Team rhythm, workflows, testing, and execution checklist
- docs/octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and action tracking
- docs/octoacme-risks-and-communication.md — Risk register and stakeholder communication templates
- docs/octoacme-roles-and-personas.md — Role summaries and responsibilities

## How to use
- Link this README from the project root and official onboarding materials
- Add new process docs to the docs/ folder and update this README with links

