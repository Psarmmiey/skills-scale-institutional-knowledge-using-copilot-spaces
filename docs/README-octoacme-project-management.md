# OctoAcme Project Management Documentation

## Overview

OctoAcme runs projects through a lightweight, lifecycle-driven process that moves work from initiation through planning, execution, release, and retrospective. Initiation focuses on validating the business need with a Project One-pager that captures the problem, measurable objectives, stakeholders, and an initial risk list. Planning turns approved initiatives into prioritized, estimable backlogs, defines the Definition of Done, and maps releases and milestones. Execution follows iterative delivery principles: small, shippable increments are planned into timeboxed sprints or milestones, with teams pulling work that meets readiness criteria and clear acceptance criteria.

Workflows are standardized to keep execution predictable and transparent. Teams use a project board (Backlog, Ready, In Progress, In Review, QA, Done) to visualize flow, and a Pull Request workflow that emphasizes small PRs, linking to issues and acceptance criteria, and requiring CI (tests and lint) and at least one approver before merging. Release activity is controlled by pre-release checklists (passing CI, release notes, rollback plans) and a deployment checklist that includes staging smoke tests, automated pipelines where possible, and post-deploy verification. Retrospectives and continuous improvement are baked into the cadence to convert learnings into tracked action items.

Roles and responsibilities are clearly defined to reduce ambiguity: Project Managers coordinate delivery, schedules, risks, and stakeholder communications; Product Managers own the problem definition, prioritization, and success metrics; Developers build and test; QA validates acceptance and quality; stakeholders provide inputs and approvals. This clarity ensures each artifact (one-pager, roadmap, backlog, risk register, retrospective notes) has an owner and a home in the repo so teams can maintain a single source of truth.

Communication and quality assurance are pillars of OctoAcme's process. Team rhythm includes daily standups for blockers and progress, weekly delivery syncs and PM–PdM alignment meetings, regular demos at sprint or milestone ends, and monthly stakeholder updates. Risk Management uses a simple risk register (ID, impact, likelihood, owner, mitigation) and defined escalation paths (team → PM → Product Lead → Sponsor). Quality practices require unit and integration tests, E2E smoke tests for critical flows, CI security scanning, and manual QA when needed; reporting tracks velocity, burndown, and success metrics to keep decisions data-informed.

## Key Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

These process documents serve as the single source of truth for OctoAcme's project management methodology. Each document covers a specific aspect of our project lifecycle, supporting repeatable, high-quality execution.

**Where to store artifacts:**
- **docs/**: General process documentation, templates, and guidelines accessible to all team members
- **.copilot/**: Project-specific knowledge that should be available to GitHub Copilot Spaces for context-aware assistance

**Maintaining this README:**
- Keep this README updated as the central index when new process documents are added
- Ensure all links are valid and point to the correct documents
- Review and update the overview section when significant process changes occur
- This README should always reflect the current state of OctoAcme's project management processes

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [x] Proposed content has been reviewed with stakeholders (if needed)
