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

### Interaction with Other Roles
- Partner with **QA/Testing Leads** on test strategies and acceptance criteria validation
- Collaborate with **Technical Leads/Architects** on design reviews and technical decisions
- Work with **Product Managers** to clarify requirements and acceptance criteria
- Receive deployment support from **Release/DevOps Engineers** during releases
- Incorporate **Design/UX Lead** specifications into implementations

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

### Interaction with Other Roles
- Receive strategic input from **Sponsors/Executive Stakeholders** on organizational priorities
- Partner with **Developers** and **Technical Leads/Architects** on feasibility and scope
- Align with **Design/UX Leads** on user experience and feature design
- Collaborate with **QA/Testing Leads** on acceptance criteria and quality standards
- Support **Project Managers** with prioritized backlog and roadmap clarity

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

### Interaction with Other Roles
- Escalate risks and decisions to **Sponsors/Executive Stakeholders**
- Track delivery progress with **Developers** and **Technical Leads/Architects**
- Coordinate quality gates with **QA/Testing Leads**
- Manage release coordination with **Release/DevOps Engineers**
- Ensure stakeholder alignment through **Product Managers**

---

## QA/Testing Lead

### Role Summary
QA and Testing Leads define and execute testing strategies to ensure software quality, validate acceptance criteria, and identify risks before release.

### Responsibilities
- Design comprehensive test plans aligned with acceptance criteria
- Define testing strategy (unit, integration, e2e, performance, security)
- Coordinate manual and automated test execution
- Triage and track quality issues through resolution
- Validate fixes and manage test coverage metrics
- Partner with engineering to identify testability gaps

### Goals
- Achieve quality targets and reduce production defects
- Shift testing left to catch issues early
- Reduce time spent on regression and ad-hoc testing

### Typical Communication
- Planning meetings to define acceptance criteria and test approach
- Daily standups to report blocker issues
- QA sign-off before release
- Quality metrics review in weekly syncs

### Interaction with Other Roles
- Collaborate with **Developers** on test design, testability, and defect resolution
- Align with **Product Managers** on acceptance criteria and quality standards
- Support **Technical Leads/Architects** with test coverage and quality metrics
- Coordinate release readiness with **Release/DevOps Engineers** and **Project Managers**
- Validate UX requirements from **Design/UX Leads** through user acceptance testing

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors provide strategic direction, secure resources, and ensure projects align with organizational goals and business outcomes.

### Responsibilities
- Approve project charter and business case
- Provide budget and resource allocation
- Escalate and resolve cross-org dependencies
- Review and approve major decisions and trade-offs
- Receive monthly/quarterly status updates

### Goals
- Ensure projects deliver measurable business value
- Minimize resource conflicts and delays
- Maintain alignment with organizational strategy

### Typical Communication
- Initiation and approval meetings
- Monthly executive status updates
- Escalation and issue resolution
- Post-release retrospectives and impact reviews

### Interaction with Other Roles
- Partner with **Project Managers** for escalations and strategic alignment
- Review project outcomes with **Product Managers** against business metrics
- Approve resource allocation and trade-offs involving **Developers** and other technical roles
- Receive quality and release readiness reports from **QA/Testing Leads** and **Release/DevOps Engineers**

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects guide system design, technical strategy, and implementation quality. They enable teams to build scalable, maintainable solutions.

### Responsibilities
- Define technical approach and architecture
- Review designs for scalability, security, and maintainability
- Identify technical risks and propose mitigations
- Mentor developers and support technical decision-making
- Ensure alignment with tech strategy and standards
- Support estimation and technical feasibility assessments

### Goals
- Build systems that scale and last
- Reduce technical debt and improve code quality
- Accelerate team velocity through good design and guidance

### Typical Communication
- Design review sessions and architecture discussions
- Planning and estimation participation
- Code review and mentoring
- Risk identification and mitigation planning

### Interaction with Other Roles
- Mentor and guide **Developers** on technical implementation and best practices
- Advise **Project Managers** on technical feasibility and risk assessment
- Collaborate with **Product Managers** on architectural trade-offs and feasibility
- Partner with **QA/Testing Leads** on test coverage and quality assurance strategy
- Support **Release/DevOps Engineers** with infrastructure and deployment considerations

---

## Design / UX Lead

### Role Summary
Design and UX Leads shape product usability and user experience. They partner with product and engineering to ensure solutions are intuitive and customer-focused.

### Responsibilities
- Conduct user research and usability testing
- Create design specifications and interaction models
- Review designs for consistency and usability
- Collaborate with product and engineering on feasibility
- Participate in acceptance criteria definition
- Support design-driven quality assurance

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Ensure design consistency across products

### Typical Communication
- Planning and kickoff to define design scope
- Design critique and feedback sessions
- Acceptance criteria reviews
- Post-release user feedback and iteration planning

### Interaction with Other Roles
- Partner with **Product Managers** on feature definition and user requirements
- Collaborate with **Developers** on implementation feasibility and design patterns
- Support **Technical Leads/Architects** with UX considerations in system design
- Work with **QA/Testing Leads** on usability testing and acceptance criteria validation
- Coordinate with **Project Managers** on design-related timelines and dependencies

---

## Release / DevOps Engineer

### Role Summary
Release and DevOps Engineers manage deployment pipelines, infrastructure, and release coordination. They enable safe, repeatable, and observable releases.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and deployment environments
- Coordinate release planning and execution
- Implement rollback and disaster recovery procedures
- Monitor deployments and support incident response
- Optimize deployment safety and speed

### Goals
- Enable frequent, low-risk deployments
- Minimize deployment-related incidents
- Maintain high observability and incident response capability

### Typical Communication
- Release planning and pre-deployment reviews
- Deployment day coordination
- Post-deployment verification and incident response
- Infrastructure and pipeline improvement discussions

### Interaction with Other Roles
- Coordinate release timelines and dependencies with **Project Managers**
- Execute deployment pipelines built and tested by **Developers**
- Validate deployment readiness with **QA/Testing Leads**
- Support **Technical Leads/Architects** with infrastructure decisions and optimizations
- Provide deployment status and incident updates to **Sponsors/Executive Stakeholders** through **Project Managers**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interaction with Other Roles" section to understand cross-functional dependencies and collaboration patterns.
