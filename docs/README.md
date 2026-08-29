# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs! This directory contains comprehensive guidance for managing projects from initiation through close-out.

## Quick Start

- **New to OctoAcme projects?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Read [Project Initiation Guide](octoacme-project-initiation.md)
- **Planning a project?** See [Project Planning](octoacme-project-planning.md)
- **Currently executing?** Check [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Managing risks?** Review [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Ready to release?** Follow [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Project complete?** Run [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## OctoAcme Project Management Approach

OctoAcme follows a structured five-phase project lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. During initiation, teams validate business need and create a lightweight Project One-pager that captures the problem statement, goals, success metrics, stakeholders, and initial risks. Once approved, the planning phase breaks work into shippable increments using a prioritized backlog with clear acceptance criteria and estimates. Execution leverages GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), small pull requests (≤400 lines), and automated CI/CD for testing and linting. The release phase includes pre-deployment verification, smoke testing, and rollback plans, while closure involves retrospectives to capture learnings and drive continuous improvement.

OctoAcme defines clear roles with specific responsibilities: **Product Managers** define what to build, prioritize the backlog, and measure outcomes; **Project Managers** coordinate schedules, manage risks, and facilitate communication; and **Developers** implement features, write tests, and collaborate on design. Supporting roles include QA/Testing teams and stakeholders. Communication follows a consistent cadence: daily standups (15 min) focus on progress and blockers, weekly syncs align PM and Product Lead, twice-weekly delivery team standups track iteration progress, and monthly stakeholder updates maintain transparency. Ad-hoc escalation follows a clear path: team-level triage → PM escalation → Product Lead → Sponsor for business-impacting issues.

Quality is embedded throughout execution via unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI before merging. A clear **Definition of Done** ensures consistency across the team. Risk management is proactive: the Risk Register tracks risks by ID, description, impact, probability, owner, and mitigation plan, reviewed weekly during syncs. OctoAcme emphasizes learning through blameless retrospectives held after each sprint, release, or milestone, capturing learnings and 2–3 prioritized action items. This structured yet flexible approach balances accountability with psychological safety, enabling data-informed decisions and iterative refinement of processes.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates** for transparency and alignment
- **Ad-hoc escalations** as needed for blockers and risks

## Documentation Index

1. [octoacme-project-management-overview.md](octoacme-project-management-overview.md) — High-level introduction, lifecycle, and core framework
2. [octoacme-project-initiation.md](octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders
3. [octoacme-project-planning.md](octoacme-project-planning.md) — Turning initiatives into actionable plans and backlogs
4. [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, quality, and metrics
5. [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) — Risk and dependency management, stakeholder communication
6. [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — Release types, pre-release requirements, and deployment checklists
7. [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and continuous improvement cycles
8. [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Detailed role definitions, responsibilities, and communication patterns

## Using These Docs

- **Keep the Project Charter updated** in your project repo
- **Add process-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Reference relevant sections** during planning, execution, and retrospectives
- **Update and evolve** these docs based on team feedback and continuous improvement action items
