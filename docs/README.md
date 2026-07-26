# OctoAcme Project Management Docs

This README serves as the central entry point for OctoAcme's project management documentation. The documents in this folder cover the full project lifecycle—from initiation through retrospective improvement—and are intended to help teams, project managers, product managers, and stakeholders understand OctoAcme's standard processes, workflows, and expectations.

## Overview

OctoAcme's project management process follows a clear, end-to-end lifecycle: **initiation, planning, execution, release, and retrospective improvement**. Work begins with a lightweight initiation phase that confirms business need, success metrics, stakeholders, timeline, initial risks, and team roles through a one-pager. Once approved, planning translates the initiative into a prioritized backlog with acceptance criteria, estimates, milestones, dependencies, and a documented Definition of Done. This creates a consistent bridge between strategic intent and delivery execution.

Execution is run through a structured team rhythm and visible workflow management. Teams use project boards (spanning backlog through done states), daily standups, weekly delivery syncs, and sprint or milestone demos to maintain flow and surface blockers quickly. Pull request practices emphasize small and reviewable changes, links to issues, explicit acceptance criteria, CI validation, and approval before merge. Risks are continuously tracked and escalated through defined levels—from team triage to PM/Product Lead involvement, and finally sponsor-level escalation for business-critical issues.

Roles are intentionally differentiated but collaborative. **Project Managers** coordinate planning, delivery cadence, risk and dependency management, and stakeholder communication. **Product Managers** define outcomes, prioritize roadmap and backlog decisions, and validate value through metrics. **Developers** implement and test features, contribute to estimation and design review, and help identify technical risks. **QA contributors** validate acceptance criteria and release readiness, while stakeholders provide direction, decisions, and approvals at key gates. Communication and quality assurance are treated as core operating mechanisms: OctoAcme uses recurring status updates, single sources of truth for project status, explicit templates for weekly updates and release notes, layered testing (unit, integration, and end-to-end smoke tests), CI linting and security scanning, and post-deploy verification. Retrospectives after sprints, releases, or incidents convert lessons into owned action items with due dates and success criteria, reinforcing a continuous improvement loop across projects.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, principles, and key artifacts. Then review [Roles and Personas](octoacme-roles-and-personas.md) to understand your responsibilities on the team.

**Starting a new project?** Follow the docs in lifecycle order: initiation → planning → execution → release → retrospective.

**Day-to-day reference?** Go directly to the doc most relevant to your current phase. Each document is self-contained and cross-references related docs where applicable.

**Contributing updates?** Keep content aligned with the style and structure of existing docs. Open a pull request with a brief summary of what changed and why.
