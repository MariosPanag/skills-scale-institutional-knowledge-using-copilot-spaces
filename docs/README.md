# OctoAcme Project Management Documentation

Welcome to OctoAcme's Project Management Process Documentation. This directory contains comprehensive guides for running projects using the OctoAcme methodology.

## Quick Start

New to OctoAcme? Start here:
1. Read the [Project Management Overview](octoacme-project-management-overview.md)
2. Review the [Roles and Personas](octoacme-roles-and-personas.md) to understand your role
3. Follow the guides based on your project stage

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. The approach is grounded in five core principles: customer-first prioritization, iterative delivery of small testable increments, clear ownership (with dedicated Project Managers and Product Leads), data-informed decision-making, and psychological safety for team feedback. 

Projects begin with lightweight validation through a Project One-pager that captures the problem statement, measurable success metrics, stakeholder alignment, and initial risk assessment. Once approved at the decision gate, the team moves into planning to break work into shippable increments, define acceptance criteria, estimate scope, and create a release roadmap.

Day-to-day execution is governed by a disciplined workflow: daily standups (15 min) focus on progress and blockers, weekly delivery syncs review flagged risks, and sprint-based planning ensures team capacity is respected. Quality is embedded throughout via unit and integration tests, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance. A three-level blocker escalation path (team triage → PM escalation → sponsor escalation) ensures issues surface promptly.

OctoAcme maintains a weekly cadence between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates. Risks are actively managed through a Risk Register and formal retrospectives occur after each sprint or milestone, capturing learnings and prioritized action items. This emphasis on transparent communication, continuous learning, and data-driven metrics creates accountability while reducing single-person dependency risk through institutionalized processes.

## OctoAcme Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Documents

### Foundation
- [Project Management Overview](octoacme-project-management-overview.md) - High-level introduction to OctoAcme approach, roles, and artifacts
- [Roles and Personas](octoacme-roles-and-personas.md) - Role definitions and responsibilities for Developers, Product Managers, and Project Managers

### Project Lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) - Validate business need, align stakeholders, and authorize work
- [Project Planning](octoacme-project-planning.md) - Create actionable plans, prioritized backlogs, and release roadmaps
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day execution, team rhythm, quality assurance, and blocker escalation
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Standardize releases to production and manage rollbacks

### Cross-Cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identify, assess, and mitigate risks; manage stakeholder communication
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and convert them into actionable improvements

## Key Artifacts

- **Project Charter / One-pager** - Problem statement, objectives, success metrics, stakeholders, timeline, risks, and team roles
- **Risk Register** - Centralized tracking of identified risks with impact, likelihood, owner, and mitigation plans
- **Sprint/Iteration Backlog** - Prioritized list of work items with acceptance criteria and estimates
- **Release Plan** - Milestone map and deployment roadmap
- **Retrospective Notes** - Action items with owners and due dates for continuous improvement

## Communication Cadence

- **Weekly sync** between PM + Product Manager
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates** on progress and key decisions
- **Ad-hoc escalations** as needed for blockers and risks

## Definition of Done

Before marking work as complete, ensure:
- All acceptance criteria are met
- Code review and approval completed
- Tests pass (unit, integration, and smoke tests)
- Security scanning completed
- Documentation updated
- Ready for deployment

## Getting Started with a New Project

1. **Initiation**: Complete the Project One-pager and secure stakeholder alignment
2. **Planning**: Conduct kickoff, create prioritized backlog, define release timeline
3. **Execution**: Follow team rhythm, manage risks weekly, maintain quality standards
4. **Release**: Deploy to staging, run smoke tests, deploy to production, announce
5. **Retrospective**: Capture learnings and drive improvements for next iteration

## Questions?

- **New to the team?** Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md)
- **Starting a project?** Follow [Project Initiation Guide](octoacme-project-initiation.md)
- **Tracking execution?** See [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Managing risks?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Deploying to production?** Check [Release & Deployment Guide](octoacme-release-and-deployment.md)
