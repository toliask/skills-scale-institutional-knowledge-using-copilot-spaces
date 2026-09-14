# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions with Other Roles
- **Product Managers**: Receive acceptance criteria and feature specs
- **Project Managers**: Report progress and blockers in standups
- **QA Lead**: Collaborate on test coverage and acceptance validation
- **Design/UX Lead**: Review designs and implement UI specifications
- **Technical Lead/Architect**: Align on technical approach and design decisions
- **DevOps/Infrastructure Engineer**: Coordinate deployments and infrastructure needs

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- **Developers**: Define and refine acceptance criteria
- **Project Managers**: Align on priorities and dependencies
- **Design/UX Lead**: Collaborate on user experience and research findings
- **QA Lead**: Define quality standards and acceptance gates
- **Stakeholders/Sponsors**: Provide regular updates and seek alignment
- **Technical Lead/Architect**: Discuss feasibility and technical trade-offs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- **Product Managers**: Align on priorities and release planning
- **Developers**: Manage timeline, scope, and dependencies
- **QA Lead**: Coordinate testing schedule and quality gates
- **Design/UX Lead**: Track design work and review cycles
- **Technical Lead/Architect**: Identify technical dependencies and risks
- **DevOps/Infrastructure Engineer**: Coordinate deployment windows
- **Stakeholders/Sponsors**: Escalate blockers and risks

---

## Design/UX Lead

### Role Summary
Design/UX Leads define the user experience, maintain design systems, and ensure usability standards are met throughout the product lifecycle. They partner with Product Managers and Developers to translate user needs into intuitive, accessible interfaces.

### Responsibilities
- Define and maintain design systems and component libraries
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Review designs during code reviews for consistency and accessibility
- Advocate for user needs in trade-off discussions
- Document design decisions and rationale
- Collaborate on accessibility and inclusive design practices

### Goals
- Deliver intuitive, accessible user experiences
- Maintain design consistency across products
- Reduce post-launch usability issues
- Enable self-service for Developers using design systems
- Build user trust through cohesive, professional interfaces

### Typical Communication
- Design reviews and feedback loops with Developers
- Sprint planning and acceptance criteria definition
- User research findings with Product Managers
- Weekly design sync with engineering leads
- Design system documentation and component guides

### Interactions with Other Roles
- **Product Managers**: Share user research and validate feature concepts
- **Developers**: Provide design specifications and support implementation
- **QA Lead**: Review designs for usability and accessibility compliance
- **Project Managers**: Report design work progress and blockers
- **Technical Lead/Architect**: Discuss technical constraints and performance implications
- **Stakeholders/Sponsors**: Conduct design reviews and gather feedback

---

## QA Lead

### Role Summary
QA Leads define quality strategy, establish testing standards, and ensure acceptance criteria are met before releases. They work with the team to prevent defects and validate that solutions meet user and business needs.

### Responsibilities
- Define test strategy and quality gates for releases
- Create and maintain test plans and test cases
- Establish acceptance criteria and Definition of Done
- Perform manual and automated testing
- Identify and document defects with clear reproduction steps
- Advocate for quality in trade-off discussions
- Mentor team on testing best practices and tools

### Goals
- Prevent defects from reaching production
- Establish clear quality standards and metrics
- Enable rapid, confident releases
- Reduce post-release issues and support burden
- Build a quality-first culture across the team

### Typical Communication
- Sprint planning and acceptance criteria refinement
- Test status reports and defect logs
- QA reviews before release
- Post-release verification and incident reviews
- Testing methodology documentation

### Interactions with Other Roles
- **Product Managers**: Validate acceptance criteria and user stories
- **Developers**: Report defects and collaborate on root causes
- **Project Managers**: Provide quality metrics and release readiness assessments
- **Design/UX Lead**: Verify design compliance and usability in testing
- **Technical Lead/Architect**: Understand technical architecture for test planning
- **DevOps/Infrastructure Engineer**: Coordinate testing environments and deployments

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers ensure production readiness, manage deployment pipelines, monitor system health, and enable teams to deploy with confidence. They bridge development and production, ensuring reliability and observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure (cloud, on-prem, hybrid)
- Implement monitoring, logging, and alerting
- Plan and execute deployments with minimal risk
- Document rollback procedures and incident playbooks
- Advise on scalability and performance architecture
- Support incident response and post-mortems

### Goals
- Enable safe, frequent deployments
- Minimize production incidents and MTTR (Mean Time To Recovery)
- Ensure system reliability and observability
- Support rapid scaling and performance optimization
- Reduce deployment risk and manual effort

### Typical Communication
- Pre-release planning and deployment windows
- Incident response and post-mortems
- Infrastructure planning meetings with Technical Leads
- Monitoring dashboards and alerting thresholds reviewed with teams
- Deployment runbooks and operational documentation

### Interactions with Other Roles
- **Developers**: Support deployment of code and infrastructure setup
- **Project Managers**: Coordinate deployment schedules and windows
- **QA Lead**: Provide testing environments and deployment verification
- **Technical Lead/Architect**: Design scalable, resilient infrastructure
- **Stakeholders/Sponsors**: Report on system availability and incident impact

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects provide technical strategy, design guidance, and governance. They ensure the system is scalable, maintainable, and aligned with long-term technical goals while managing technical debt and risk.

### Responsibilities
- Define and maintain technical architecture and standards
- Conduct design reviews and provide technical guidance
- Identify and mitigate technical risks and technical debt
- Mentor team on best practices and new technologies
- Evaluate tools, frameworks, and architectural patterns
- Document technical decisions and rationale (ADRs)
- Advise on performance, security, and scalability trade-offs

### Goals
- Build scalable, maintainable, secure systems
- Reduce technical debt and system complexity
- Enable team velocity through good architecture
- Maintain system reliability and performance
- Foster a culture of continuous technical improvement

### Typical Communication
- Technical design reviews and architecture discussions
- Technical spike investigations and recommendations
- Architecture Decision Records (ADRs) and documentation
- Code review feedback on technical approach
- Technical mentoring and knowledge sharing sessions

### Interactions with Other Roles
- **Developers**: Guide technical approach and code quality standards
- **Product Managers**: Discuss feasibility and technical trade-offs
- **Project Managers**: Identify technical dependencies and risks
- **QA Lead**: Define testability requirements and quality standards
- **Design/UX Lead**: Address technical constraints and performance
- **DevOps/Infrastructure Engineer**: Design infrastructure and deployment architecture
- **Stakeholders/Sponsors**: Explain technical decisions and risk implications

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide executive oversight, business alignment, and decision authority for projects. They ensure projects deliver business value and manage organizational resources and priorities.

### Responsibilities
- Define business objectives and success metrics
- Approve project charter and resource allocation
- Make key decisions on scope, timeline, and budget trade-offs
- Escalate organizational blockers and dependencies
- Provide regular feedback and course corrections
- Champion project within the organization
- Ensure alignment with organizational strategy

### Goals
- Maximize return on investment (ROI)
- Ensure projects align with business strategy
- Remove organizational barriers to delivery
- Make timely, informed decisions
- Maintain stakeholder confidence in project execution

### Typical Communication
- Project kickoff and approval meetings
- Monthly or milestone-based status reviews
- Decision-gate reviews and go/no-go assessments
- Executive briefings and business updates
- Escalation meetings for blocked decisions

### Interactions with Other Roles
- **Project Managers**: Receive status updates and escalations
- **Product Managers**: Approve product vision and priorities
- **Developers**: Occasional technical reviews and design decisions
- **QA Lead**: Review quality metrics and release readiness
- **Technical Lead/Architect**: Discuss major technical decisions and risks
- **All roles**: Provide context on business needs and organizational priorities

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove impediments, and foster a culture of continuous improvement. They enable teams to work efficiently while maintaining Agile principles and practices (when applicable).

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove team impediments and blockers
- Coach team on Agile principles and practices
- Track and communicate team velocity and metrics
- Facilitate difficult conversations and conflict resolution
- Maintain sprint board and process artifacts
- Continuously improve team processes and rituals

### Goals
- Maximize team velocity and throughput
- Build a self-organizing, high-performing team
- Foster psychological safety and open communication
- Reduce process overhead and waste
- Adapt processes based on team feedback

### Typical Communication
- Sprint ceremonies (planning, standup, review, retrospective)
- One-on-one coaching with team members
- Metrics dashboards (velocity, burndown, cycle time)
- Retrospective action items and follow-ups
- Process improvement recommendations

### Interactions with Other Roles
- **All team members**: Facilitate ceremonies and coach on Agile practices
- **Project Managers**: Coordinate on timeline and capacity planning
- **Product Managers**: Collaborate on backlog refinement and prioritization
- **Stakeholders/Sponsors**: Report on team velocity and process health

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
