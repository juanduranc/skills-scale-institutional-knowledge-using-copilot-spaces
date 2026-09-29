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

---

## QA/Test Leads

### Role Summary
QA/Test Leads define the test strategy and coordinate validation of acceptance criteria, quality risks, and release readiness.

### Responsibilities
- Define the test approach for features, integrations, and critical user flows
- Coordinate manual, automated, integration, and end-to-end testing
- Track quality risks and provide a release-quality recommendation
- Confirm that acceptance criteria and the Definition of Done are testable and met

### Interaction with Existing Roles
- Work with Developers on testability, automation, defect resolution, and test evidence
- Work with Product Managers to clarify acceptance criteria and feature behavior
- Work with Project Managers to plan quality milestones, report readiness, and escalate quality risks

---

## UX/Design Leads

### Role Summary
UX/Design Leads own user research, interaction design, accessibility considerations, and design validation for project outcomes.

### Responsibilities
- Translate user needs and research findings into usable design proposals
- Define interaction patterns and accessibility expectations
- Validate designs with users and stakeholders before and during implementation
- Provide design artifacts and decisions needed for backlog and delivery planning

### Interaction with Existing Roles
- Partner with Product Managers to connect customer needs, product outcomes, and acceptance criteria
- Collaborate with Developers to clarify design intent, implementation trade-offs, and testable usability requirements
- Work with Project Managers to sequence design dependencies and communicate design risks or decisions

---

## Security/Privacy Leads

### Role Summary
Security/Privacy Leads identify security and privacy requirements and coordinate the reviews and controls needed to protect users, systems, and data.

### Responsibilities
- Identify security, privacy, and compliance requirements during initiation and planning
- Coordinate threat modeling, risk assessments, and required security reviews
- Verify that required controls, security testing, and remediation plans are complete
- Advise on risk acceptance and escalate unresolved security or privacy issues

### Interaction with Existing Roles
- Work with Developers on secure implementation, threat mitigations, and remediation
- Coordinate with QA/Test Leads on security testing and evidence
- Work with Product Managers to balance user, business, and compliance outcomes
- Work with Project Managers to track security risks, dependencies, approvals, and escalations

---

## Technical Leads/Architects

### Role Summary
Technical Leads/Architects guide technical direction, architecture decisions, integration design, and management of technical debt.

### Responsibilities
- Define and document technical approaches, interfaces, and significant design decisions
- Identify integration points, technical dependencies, and architecture risks
- Support estimation and sequencing of technically complex work
- Guide technical debt management and maintainability decisions

### Interaction with Existing Roles
- Collaborate with Developers on implementation, code quality, and technical reviews
- Work with Product Managers on feasibility, customer impact, and technical trade-offs
- Work with Project Managers on dependencies, estimates, milestones, and delivery risks
- Consult Security/Privacy Leads and Operations/SRE or Release Managers when architecture affects security or operability

---

## Operations/SRE or Release Managers

### Role Summary
Operations/SRE or Release Managers coordinate operational readiness and reliable delivery of changes into production.

### Responsibilities
- Define deployment readiness, observability, and operational acceptance requirements
- Maintain runbooks, rollback plans, and release or incident procedures
- Coordinate staging verification, production deployment, and post-deployment checks
- Monitor production impact and ensure follow-up actions are captured after incidents or releases

### Interaction with Existing Roles
- Coordinate with Developers and QA/Test Leads on release gates, smoke tests, monitoring, and defect response
- Work with Technical Leads/Architects on reliability, capacity, and integration concerns
- Work with Project Managers on release schedules, incidents, risks, and stakeholder communications
- Support Product Managers and stakeholders with production impact, known issues, and release outcomes

---

## Business Sponsors/Executive Stakeholders

### Role Summary
Business Sponsors or Executive Stakeholders provide strategic sponsorship, confirm priority, and make or authorize high-impact business decisions.

### Responsibilities
- Confirm strategic alignment, business priority, and sponsorship during initiation
- Approve major scope, funding, timeline, or risk decisions within their authority
- Resolve escalations that exceed team or Product Manager decision rights
- Review outcomes, success metrics, and material changes in project direction

### Interaction with Existing Roles
- Partner with Product Managers on business outcomes, product priorities, and trade-offs
- Work with Project Managers through status reports, decision logs, risk escalations, and governance updates
- Provide timely decisions and support when dependencies or business-impacting blockers require executive action

---

## Cross-Role Collaboration Across the Project Lifecycle

- **Initiation:** Product Managers define the problem and outcomes; Project Managers identify stakeholders and initial risks; Business Sponsors confirm priority; UX/Design, Technical, Security/Privacy, and Operations representatives contribute early feasibility and risk input as needed.
- **Planning:** Product Managers prioritize the backlog; Project Managers establish milestones and dependencies; Technical Leads/Architects, UX/Design Leads, Security/Privacy Leads, QA/Test Leads, and Operations/SRE or Release Managers define their respective acceptance, design, technical, security, quality, and operational needs.
- **Execution:** Developers implement the work while collaborating with Technical Leads, UX/Design, Security/Privacy, and QA/Test Leads. Project Managers coordinate delivery and escalation, while Product Managers clarify scope and priorities.
- **Release:** QA/Test Leads confirm validation, Security/Privacy Leads confirm required controls, and Operations/SRE or Release Managers coordinate deployment and verification. Project Managers coordinate timing and communications, and Product Managers and sponsors review expected outcomes and impact.
- **Retrospectives and improvement:** All participating roles contribute evidence and lessons learned. Project Managers facilitate action tracking, while role leads own improvements within their areas and Product Managers and sponsors evaluate impact against project or business outcomes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
