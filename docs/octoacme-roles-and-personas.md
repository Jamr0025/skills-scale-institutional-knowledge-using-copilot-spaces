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

## UX/Design Lead

### Role Summary
The UX/Design Lead owns user research, interaction design, accessibility considerations, and usability validation. They ensure that features are intuitive, accessible, and meet user needs throughout the project lifecycle.

### Responsibilities
- Conduct user research and synthesize findings into design direction
- Create wireframes, prototypes, and design specifications
- Ensure accessibility standards (WCAG) are met
- Validate usability through user testing and feedback
- Participate in acceptance criteria definition to ensure user-centered success
- Partner with developers on feasibility and implementation of designs

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Validate that solutions solve real user problems
- Ensure consistent design language across products

### Interactions with Other Roles
- **Product Manager**: Collaborate on user needs, prioritization, and success metrics
- **Developers**: Partner on design feasibility, technical constraints, and implementation details
- **QA/Test Lead**: Work together on usability acceptance criteria and validation approach
- **Project Manager**: Communicate design milestones, dependencies, and risks

### Typical Communication
- Design reviews and feedback sessions
- User research reports and insights
- Accessibility and usability checklists
- Design system documentation and updates

---

## QA/Test Lead

### Role Summary
The QA/Test Lead defines the test strategy, coordinates validation against acceptance criteria and the Definition of Done, and ensures release readiness. They champion quality throughout the project lifecycle.

### Responsibilities
- Define test strategy and test plans for features and releases
- Create and maintain automated test suites
- Coordinate manual testing and validation activities
- Ensure all acceptance criteria are validated before release
- Identify quality risks and propose mitigations
- Support release readiness verification and post-deployment smoke testing
- Track and communicate quality metrics and test coverage

### Goals
- Deliver reliable, high-quality software
- Reduce defects in production
- Ensure projects meet acceptance criteria and Definition of Done
- Minimize rework and support costs through early issue detection

### Interactions with Other Roles
- **Developers**: Partner on testability, test automation, and defect resolution
- **Project Manager**: Communicate quality risks, blockers, and release readiness status
- **Product Manager**: Align on acceptance criteria, user scenarios, and acceptance decisions
- **UX/Design Lead**: Collaborate on usability acceptance and user-facing quality validation

### Typical Communication
- Test plans and test case specifications
- Quality reports and metrics dashboards
- Defect and issue tracking
- Release readiness checklists

---

## Security/Privacy Partner

### Role Summary
The Security/Privacy Partner identifies security, privacy, and compliance requirements, reviews architectural and implementation risks, and ensures that projects meet organizational and regulatory standards.

### Responsibilities
- Define security and privacy requirements for projects
- Conduct threat modeling and security design reviews
- Review code and architecture for security vulnerabilities
- Identify compliance requirements and audit obligations
- Propose and validate security mitigations
- Participate in incident response planning and post-incident analysis
- Ensure secure configuration and data handling practices

### Goals
- Protect customer data and organizational assets
- Reduce security and compliance risks
- Ensure regulatory alignment and audit readiness
- Build security into the development process from the start

### Interactions with Other Roles
- **Developers**: Partner on secure implementation, code review, and vulnerability remediation
- **Project Manager**: Escalate security risks, track mitigations, and ensure security checkpoints in the plan
- **Product Manager**: Advise on risk-based trade-offs and security-related prioritization
- **QA/Test Lead**: Coordinate security testing and validation activities

### Typical Communication
- Security and privacy requirements documentation
- Threat models and risk assessments
- Security review findings and remediation tracking
- Compliance checklists and audit reports

---

## Site Reliability/Operations Lead

### Role Summary
The Site Reliability/Operations Lead owns operational readiness, observability, deployment coordination, and rollback planning. They ensure that features are operationally sound and can be reliably deployed and monitored in production.

### Responsibilities
- Design observability, monitoring, and alerting strategies
- Plan and coordinate deployment activities
- Define and document rollback procedures
- Ensure infrastructure readiness and capacity planning
- Establish operational runbooks and incident playbooks
- Support incident response and post-incident analysis
- Validate operational metrics and service-level agreements

### Goals
- Ensure systems are reliable, observable, and maintainable
- Minimize downtime and incident impact
- Reduce mean time to resolution (MTTR) for incidents
- Enable confident, low-risk deployments

### Interactions with Other Roles
- **Developers**: Partner on reliability, observability instrumentation, and operational best practices
- **Project Manager**: Coordinate release planning, incident response, and operational handoffs
- **Product Manager**: Advise on service-impact decisions and customer-facing reliability trade-offs
- **QA/Test Lead**: Collaborate on load testing, chaos engineering, and operational readiness validation

### Typical Communication
- Deployment plans and runbooks
- Operational readiness checklists
- Monitoring and alerting configuration
- Incident reports and post-mortems

---

## Customer/Support Representative

### Role Summary
The Customer/Support Representative brings customer needs, support trends, and real-world feedback into planning and validation. They ensure that projects address customer pain points and maintain support readiness.

### Responsibilities
- Identify customer needs and pain points from support interactions
- Synthesize support trends and escalation patterns
- Participate in acceptance criteria definition to ensure customer usability
- Validate that solutions address customer feedback
- Prepare support documentation and customer communication
- Provide customer context during planning and prioritization discussions
- Support post-launch monitoring of customer sentiment and issues

### Goals
- Reduce customer support burden and escalations
- Increase customer satisfaction and product adoption
- Ensure customer feedback is represented in product decisions
- Enable support team readiness and customer self-service

### Interactions with Other Roles
- **Product Manager**: Collaborate on prioritization, customer research, and customer-facing messaging
- **Project Manager**: Provide customer context in stakeholder updates and communication planning
- **Developers and QA/Test Lead**: Partner on reproduction of customer issues, edge cases, and acceptance validation
- **UX/Design Lead**: Share customer feedback on usability and design improvements

### Typical Communication
- Customer feedback summaries and trends
- Support documentation and FAQ updates
- Customer communication drafts and release notes
- Post-launch customer sentiment and issue monitoring

---

## Responsibility and Interaction Matrix

| Persona | Initiation | Planning | Execution | Release | Incident Response | Retrospective |
|---------|-----------|----------|-----------|---------|-------------------|---------------|
| Developers | Consult | Primary | Primary | Primary | Primary | Participant |
| Product Manager | Primary | Primary | Consult | Consult | Consult | Participant |
| Project Manager | Primary | Primary | Primary | Primary | Primary | Facilitator |
| UX/Design Lead | Consult | Primary | Primary | Consult | — | Participant |
| QA/Test Lead | Consult | Primary | Primary | Primary | Consult | Participant |
| Security/Privacy Partner | Consult | Primary | Consult | Primary | Primary | Participant |
| Site Reliability/Operations Lead | Consult | Consult | Consult | Primary | Primary | Participant |
| Customer/Support Representative | Consult | Consult | Consult | Consult | Consult | Participant |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Responsibility and Interaction Matrix to determine who should participate in each phase of a project.
