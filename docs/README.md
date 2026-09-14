# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. Our framework is built on core principles including customer-first prioritization, data-informed decision-making, psychological safety, and continuous improvement. The organization operates across five key phases—**Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**—each with defined deliverables, checklists, and communication cadences. This documentation suite serves as the central source of truth for how OctoAcme teams organize, execute, and learn from their work.

## Project Lifecycle

OctoAcme projects follow a structured lifecycle:

1. **Initiation** - Validate business need, align stakeholders, and secure sponsor approval
2. **Planning** - Break work into actionable backlog, define dependencies, and establish milestones
3. **Execution & Tracking** - Day-to-day delivery, progress monitoring, and blocker management
4. **Release & Deployment** - Ship to production safely with comprehensive testing and rollback plans
5. **Retrospective** - Capture learnings, convert insights into action items, and drive continuous improvement

## Key Roles & Responsibilities

OctoAcme projects operate with clearly defined roles to eliminate ambiguity and ensure accountability:

- **Project Managers** coordinate schedules, manage risks and dependencies, facilitate meetings, and maintain project documentation and status reporting
- **Product Managers** define what to build, prioritize the backlog, validate solutions through research and metrics, and own success metrics
- **Developers** implement features with quality in mind, write and maintain tests, participate in design and code reviews, and identify technical risks
- **Stakeholders & Sponsors** provide inputs, approvals, and business context for decisions

For detailed persona descriptions, see [Roles and Personas](octoacme-roles-and-personas.md).

## Documentation Index

### Core Guides

- **[Project Management Overview](octoacme-project-management-overview.md)** - Introduction to OctoAcme's principles, roles, key artifacts, and communication cadence
- **[Roles and Personas](octoacme-roles-and-personas.md)** - Detailed descriptions of Developer, Product Manager, and Project Manager roles and responsibilities

### Process Guides by Phase

- **[Project Initiation](octoacme-project-initiation.md)** - Getting started with a new project, including stakeholder alignment and go/no-go decision gates
- **[Project Planning](octoacme-project-planning.md)** - Creating your project plan and backlog, defining Definition of Done, and identifying dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Managing daily work and progress through standups, syncs, PR workflows, and blocker escalation
- **[Release & Deployment](octoacme-release-and-deployment.md)** - Shipping to production safely with pre-release checklists, deployment windows, and rollback plans
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Learning and iterating through structured retrospectives and action item tracking

### Cross-Cutting Guides

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Managing risks throughout the project lifecycle, communicating with stakeholders, and executing escalation paths

## Quick Start Guide

### For New Project Managers
1. Start with [Project Management Overview](octoacme-project-management-overview.md) to understand roles and artifacts
2. Use [Project Initiation](octoacme-project-initiation.md) to kick off a new project and create a One-pager
3. Follow [Project Planning](octoacme-project-planning.md) to build the backlog and establish milestones
4. Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day rhythm and blocker management
5. Consult [Risk Management & Communication](octoacme-risks-and-communication.md) for ongoing stakeholder updates and risk tracking

### For Developers
1. Review [Project Management Overview](octoacme-project-management-overview.md) to understand the process
2. Check [Roles and Personas](octoacme-roles-and-personas.md) to see Developer responsibilities
3. Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for PR workflows, testing expectations, and Definition of Done
4. Review acceptance criteria in your project's backlog (typically in GitHub Projects or issues)

### For Product Managers
1. Read [Project Management Overview](octoacme-project-management-overview.md) to understand the full lifecycle
2. Use [Project Initiation](octoacme-project-initiation.md) to define problem statements and success metrics
3. Leverage [Project Planning](octoacme-project-planning.md) to prioritize the backlog and define acceptance criteria
4. Monitor [Risk Management & Communication](octoacme-risks-and-communication.md) to track dependencies and stakeholder concerns
5. Participate in [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to measure impact and iterate

## Communication Cadence

OctoAcme maintains a structured communication rhythm to ensure alignment and transparency:

- **Daily Standups** (15 min) - Team-level focus on progress, blockers, and dependencies
- **Weekly PM + Product Manager Sync** - Alignment on prioritization, risks, and decisions
- **Twice-Weekly Team Standups** - As agreed by delivery team
- **Weekly Delivery Sync** - Show progress, updates, and flagged risks to stakeholders
- **Monthly Stakeholder Updates** - Status summary for sponsors and leadership
- **Sprint/Milestone Demos** - Demonstrate completed work and gather feedback

## Quality & Testing Standards

Quality is embedded throughout OctoAcme's execution process:

- **Unit tests** for all new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI pipeline
- **Manual QA** for feature acceptance when needed
- **Small, reviewable PRs** (≤400 lines when possible)
- **At least one approval** required before merge

## How to Use These Docs

- **Keep your Project Charter updated** in your project repository
- **Reference the appropriate phase guide** as you progress through your project lifecycle
- **Use checklists** as acceptance criteria for completing each phase
- **Add process-specific customizations** to your project's `.copilot/` folder if you want project-specific guidance
- **Contribute improvements** via the [Process Doc Update issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

## Contributing to These Docs

Found a gap, improvement, or best practice to add? Use the **[Process Doc Update issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** to propose changes. All updates are reviewed for alignment with OctoAcme's principles and incorporated back into the living documentation.
