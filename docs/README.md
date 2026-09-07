# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, data-informed decisions, and psychological safety. These practices are captured across the process docs in this folder to help teams plan, execute, and improve consistently.

## Core Principles
- Customer-first: prioritize customer value and usability  
- Iterative delivery: deliver small, testable increments  
- Clear ownership: each project has named roles with defined responsibilities  
- Data-informed: measure impact and iterate based on evidence  
- Psychological safety: encourage feedback and continuous learning

## Project Management Processes — Brief Summary
OctoAcme runs work through a lightweight lifecycle from initiation to close. Initiation validates the business need and aligns stakeholders using a Project One-pager and decision gate. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, and a release plan so teams can deliver predictable increments.

During execution teams follow a standard board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request process: small PRs when possible, linked issues and acceptance criteria, CI (tests, lint, security scans) before review, and required approvals prior to merge. Regular team rhythm — daily standups, weekly delivery syncs, and PM+PdM alignment — keeps progress visible and blockers surfaced.

Releases follow a checklist-driven approach with pre-release verification, rollback plans, and post-deploy checks. Quality is enforced through unit and integration tests, end-to-end smoke tests for critical flows, automated security scanning, and manual QA when needed. After each sprint or release teams run retrospectives, convert learnings into tracked action items, and measure improvement over time.

## Process Documentation (pick based on your current phase)
- [Project Management Overview](octoacme-project-management-overview.md) — Start here for a concise introduction to OctoAcme's approach, roles, and artifacts  
- [Project Initiation](octoacme-project-initiation.md) — Validate idea, build one-pager, decide go/no-go  
- [Project Planning](octoacme-project-planning.md) — Break work into shippable increments, define DoD, plan releases  
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery practices, PR workflow, team rhythm  
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, escalation, stakeholder updates  
- [Release & Deployment](octoacme-release-and-deployment.md) — Deployment checklist, rollback playbook, release notes  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospectives and tracking action items  
- [Roles & Personas](octoacme-roles-and-personas.md) — Role definitions and responsibilities

## Quick Reference
| Need | Document |
|------|----------|
| Understand OctoAcme PM approach | [Project Management Overview](octoacme-project-management-overview.md) |
| Starting a new initiative | [Project Initiation](octoacme-project-initiation.md) |
| Breaking down work and planning delivery | [Project Planning](octoacme-project-planning.md) |
| Daily execution, standups, and tracking | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| Managing and communicating risks | [Risk Management & Communication](octoacme-risks-and-communication.md) |
| Preparing and executing a release | [Release & Deployment](octoacme-release-and-deployment.md) |
| Learning and improving processes | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Role definitions and responsibilities | [Roles & Personas](octoacme-roles-and-personas.md) |

## How to Contribute
To propose changes to these process docs, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/ and reference the file(s) you want to update. For quick edits, submit a pull request with the proposed change and link any relevant issues or decisions.

## Acceptance Criteria
- README provides a clear entry point and navigation for docs/  
- Content aligns with existing process documents and improves discoverability  
- Readers can identify which document to consult for common scenarios
