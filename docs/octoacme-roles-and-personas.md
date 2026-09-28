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
- Collaborate with **Technical Leads** on architecture and design decisions
- Coordinate with **QA/Testing Leads** on test automation and acceptance criteria validation
- Work with **Project Managers** on task estimation and scheduling
- Partner with **Product Managers** to understand acceptance criteria and priorities

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
- Work with **Project Managers** on timeline and planning alignment
- Collaborate with **QA/Testing Leads** to define test plans and acceptance criteria
- Coordinate with **Stakeholders/Sponsors** on priorities and business goals
- Engage with **Technical Leads** to understand technical feasibility and trade-offs

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
- Escalate blockers identified by **Scrum Masters** and team members
- Coordinate with **Product Managers** on scope and prioritization
- Work with **Stakeholders/Sponsors** on resource allocation and approvals
- Partner with **DevOps/Release Engineers** on deployment planning

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, define acceptance criteria validation, and ensure products meet quality standards before release.

### Responsibilities
- Create and maintain test plans aligned with project scope and risk profile
- Define QA approach (manual, automated, integration, E2E testing)
- Validate acceptance criteria and coordinate with Product Managers on definition
- Execute or coordinate testing activities and report quality metrics
- Identify quality risks and propose mitigation strategies
- Coordinate with Developers on test automation and CI/CD integration

### Goals
- Ensure product quality meets customer expectations
- Catch defects early and reduce production incidents
- Build confidence in releases through comprehensive testing

### Typical Communication
- Sprint planning and refinement sessions
- Daily standup participation for test progress
- Quality metrics in weekly status reports
- Pre-release sign-off meetings

### Interactions with Other Roles
- Partner with **Developers** on test automation and code quality
- Align with **Product Managers** on acceptance criteria and test coverage priorities
- Coordinate with **DevOps/Release Engineers** on smoke tests and post-deploy validation
- Work with **Project Managers** on test timeline and resource planning
- Support **Technical Leads** in validating architectural quality concerns

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide technical design, make architecture decisions, and own technical risk mitigation for projects.

### Responsibilities
- Define technical approach and architecture for project scope
- Review designs and code for technical feasibility and risk
- Identify technical risks and propose mitigation strategies
- Mentor Developers and provide technical guidance
- Participate in capacity planning and effort estimation
- Lead technical design reviews and document architectural decisions

### Goals
- Deliver scalable, maintainable, secure technical solutions
- Reduce technical debt and rework
- Build reusable components and patterns

### Typical Communication
- Technical design review meetings
- Capacity planning and estimation sessions
- Architecture decision documentation
- Code reviews and mentoring

### Interactions with Other Roles
- Guide **Developers** on technical approach and best practices
- Collaborate with **Product Managers** on feasibility and trade-offs
- Work with **Security/Compliance Officers** on security architecture
- Partner with **DevOps/Release Engineers** on deployment architecture
- Coordinate with **Project Managers** on capacity and schedule implications
- Support **QA/Testing Leads** on test strategy for complex technical areas

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach teams on agile practices and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and help remove impediments blocking the team
- Coach team on agile practices and iterative delivery
- Maintain sprint board and tracking cadence
- Escalate cross-team blockers to Project Manager
- Measure and report team velocity and burndown

### Goals
- Enable team flow and reduce cycle time
- Foster psychological safety and continuous improvement
- Maximize team velocity and predictability

### Typical Communication
- Daily standups (15 min)
- Sprint ceremonies
- One-on-ones with team members
- Backlog refinement sessions

### Interactions with Other Roles
- Escalate blockers to **Project Managers** for cross-team resolution
- Support **Developers** in identifying and removing impediments
- Coach team on collaboration with **Product Managers** and stakeholders
- Work with **Project Managers** on sprint planning and retrospectives

---

## Stakeholder/Sponsor

### Role Summary
Sponsors provide business context, make strategic decisions, allocate resources, and remove organizational blockers.

### Responsibilities
- Define business objectives and success metrics
- Provide strategic context and prioritization guidance
- Approve budget and resource allocation
- Remove organizational blockers
- Receive regular executive updates and escalations
- Make go/no-go decisions at key gates

### Goals
- Maximize business value delivery
- Ensure strategic alignment with organizational priorities
- Enable project success through resource and decision-making support

### Typical Communication
- Monthly or quarterly stakeholder updates
- Key decision gate meetings
- Escalation paths for business-impacting issues
- Executive summaries and risk reports

### Interactions with Other Roles
- Align with **Product Managers** on business priorities and success metrics
- Receive escalations from **Project Managers** on business-impacting risks
- Provide strategic direction to the **Scrum Master/Agile Coach**
- Make resource and approval decisions affecting **Developers**, **Technical Leads**, and other roles

---

## Security/Compliance Officer

### Role Summary
Security Officers ensure that projects meet security and regulatory requirements and build secure systems by design.

### Responsibilities
- Define security and compliance requirements for projects
- Review designs for security risks and vulnerabilities
- Approve security testing and scanning strategies
- Ensure data protection, encryption, and access controls
- Coordinate audits and compliance validations
- Provide security guidance and threat modeling support

### Goals
- Prevent security breaches and data loss
- Ensure regulatory compliance and audit readiness
- Build security awareness and best practices into delivery

### Typical Communication
- Security design review meetings
- Risk assessment and threat modeling sessions
- Compliance validation checkpoints
- Security incident response coordination

### Interactions with Other Roles
- Partner with **Technical Leads** on security architecture and design
- Review code and designs from **Developers** for security risks
- Coordinate with **QA/Testing Leads** on security testing and scanning
- Provide compliance requirements to **Project Managers** and **Product Managers**
- Work with **DevOps/Release Engineers** on secure deployment practices
- Advise **Stakeholders/Sponsors** on compliance and risk implications

---

## DevOps/Release Engineer

### Role Summary
DevOps Engineers own deployment processes, CI/CD infrastructure, and release coordination to enable fast, reliable deployments.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure, environments, and deployment tooling
- Plan and execute releases with minimal risk
- Coordinate rollback and incident response procedures
- Monitor deployed systems and observability
- Manage deployment documentation and runbooks

### Goals
- Enable frequent, reliable deployments to production
- Reduce deployment risk and time-to-recovery for incidents
- Maximize system reliability and observability

### Typical Communication
- Release planning and deployment window coordination
- Infrastructure and CI/CD maintenance updates
- Incident response and post-mortems
- Runbook and operations documentation review

### Interactions with Other Roles
- Partner with **Developers** on CI/CD pipeline configuration and automation
- Coordinate with **QA/Testing Leads** on smoke tests and post-deploy validation
- Work with **Technical Leads** on infrastructure architecture and scalability
- Align with **Project Managers** on release schedules and deployment windows
- Support **Security/Compliance Officers** on secure deployment practices
- Coordinate incident response with **Stakeholders/Sponsors** for critical issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction sections to understand how roles collaborate and communicate across project phases.
