# OctoAcme Project Management Docs — README

Welcome to the OctoAcme Project Management Docs! This README provides:
- A brief overview of the project management principles and procedures used by OctoAcme
- Convenient links to all core process documents in the `docs/` folder

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business needs and create a lightweight Project One-pager that defines the problem statement, success metrics, stakeholders, and initial timeline. This gates the decision to move forward only when stakeholder alignment is confirmed and measurable outcomes are clear. Once approved, the planning phase breaks work into prioritized backlog items with acceptance criteria, estimates, and dependencies. Teams use a Definition of Done to ensure quality standards and prepare release plans that map iterations to milestones.

Execution and tracking are managed through a disciplined rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based iteration planning. The team operates a project board (GitHub Projects) with standardized columns—Backlog, Ready, In Progress, In Review, QA, and Done—keeping work visible and dependencies transparent. Pull requests are kept small (≤400 lines), include issue links and acceptance criteria, and require at least one approval before merging. Quality assurance is embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance. Risk and dependency management are proactive, with escalation levels defined (team triage → PM to Product Lead → sponsor escalation) and a Risk Register maintained and reviewed at weekly syncs.

OctoAcme defines clear roles and responsibilities to avoid ambiguity: **Project Managers** coordinate delivery, manage schedules, and communication; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features, write tests, and identify technical risks; and **QA/Testing** validates quality against acceptance criteria. Communication cadences include twice-weekly standups, weekly PM/PdM syncs, and monthly stakeholder updates, with a focus on transparency and psychological safety. For releases, teams follow a structured pre-release checklist (acceptance criteria met, CI passing, security scans cleared, smoke tests prepared) and maintain rollback playbooks for incident response.

Finally, OctoAcme embeds continuous improvement through retrospectives held after each sprint or milestone, where teams capture what went well, areas for improvement, and actionable items with assigned owners and due dates. This closes the feedback loop and ensures learnings are systemized back into the process documentation and future iterations. The emphasis on versioned artifacts (Project Charter, Risk Register, release notes, retrospective summaries) stored in the repository—and optionally in Copilot Spaces—allows institutional knowledge to scale across the team and reduces single-person dependency risk.

## Core Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
