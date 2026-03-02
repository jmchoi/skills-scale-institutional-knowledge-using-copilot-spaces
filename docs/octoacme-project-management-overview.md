# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Sponsor: provides strategic direction, secures resources, and approves major scope changes.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Project Manager (PM): coordinates delivery, schedules, risk, and communications.
- Developers: implement features, collaborate on design and testability.
- UX Designer: leads user research and interaction design; validates usability.
- QA Lead: owns quality strategy, test planning, and release certification.
- Scrum Master: facilitates agile ceremonies, removes blockers, and coaches the team.
- Technical Writer: creates and maintains user-facing and developer documentation.

See [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) for full role definitions.

## Role Interactions and Dependencies
Cross-functional collaboration is central to OctoAcme's delivery model. Key interaction patterns include:

- **Sponsor ↔ PM/PdM**: Periodic status updates and escalation for scope or budget decisions.
- **PdM ↔ UX Designer**: Joint definition of feature requirements and usability validation.
- **PM ↔ Scrum Master**: Coordination on sprint scheduling, cross-team dependencies, and blockers.
- **QA Lead ↔ Developers**: Shared ownership of test coverage, defect resolution, and release readiness.
- **Technical Writer ↔ Developers/PdM**: Documentation requirements included in acceptance criteria and reviewed before release.

For a full interaction matrix and RACI model, see [octoacme-roles-interaction-matrix.md](octoacme-roles-interaction-matrix.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
