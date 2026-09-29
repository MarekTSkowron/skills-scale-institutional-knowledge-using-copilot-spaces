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

## Design/UX Lead or Researcher

### Role Summary
Design/UX Leads and Researchers own user research, interaction design, usability validation, and design acceptance criteria. They ensure that products are discoverable, usable, and delightful for end users.

### Responsibilities
- Conduct user research and gather customer feedback
- Design workflows, wireframes, and interaction patterns
- Define usability acceptance criteria and design specifications
- Validate design solutions through user testing and iteration
- Collaborate on accessibility and inclusive design considerations
- Review and approve UI/UX implementations against design specs

### Goals
- Deliver user-centric, accessible, and intuitive experiences
- Reduce support burden through better design
- Increase user adoption and satisfaction

### Typical Communication
- Design workshops and critiques with the team
- User research findings and insights shared with Product Managers
- Usability acceptance criteria provided to Developers
- Collaborative validation with QA/Testing on critical user flows

### Interactions with Existing Roles
- **Product Managers**: Partner on customer value, outcomes, and prioritization; align on customer insights and product direction
- **Developers**: Collaborate on feasibility of design solutions, provide implementation guidance, and review code for design accuracy
- **QA/Testing**: Work together on usability testing, critical-flow validation, and design acceptance criteria verification

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects guide technical direction, architecture decisions, non-functional requirements, and technical risk management. They ensure the solution is technically sound, scalable, and maintainable.

### Responsibilities
- Define technical architecture and design patterns
- Make decisions on technology choices and trade-offs
- Establish non-functional requirements (performance, scalability, security, reliability)
- Identify and mitigate technical risks and dependencies
- Provide technical guidance to the development team
- Review technical implementations and design documents

### Goals
- Deliver technically sound, scalable, and maintainable solutions
- Reduce technical debt and future rework
- Minimize integration and deployment risks

### Typical Communication
- Technical design reviews and architecture decisions
- Technical risk registers and mitigation plans
- Estimates and dependency impact assessments
- Code reviews and technical mentoring

### Interactions with Existing Roles
- **Developers**: Guide implementation, review code, mentor on technical best practices
- **Project Managers**: Advise on estimates, dependencies, and technical risks; inform timeline and resource planning
- **Product Managers**: Translate product outcomes into feasible technical increments; collaborate on performance and scalability requirements

---

## Release/DevOps Engineer

### Role Summary
Release/DevOps Engineers own deployment automation, environments, observability, release readiness, and rollback execution. They ensure smooth, reliable transitions from development to production.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage development, staging, and production environments
- Implement monitoring, logging, and alertability for production systems
- Validate release readiness and execute deployments
- Plan and execute rollbacks when necessary
- Document deployment procedures and runbooks

### Goals
- Enable fast, reliable, repeatable deployments
- Minimize deployment risks and production incidents
- Maintain high observability and incident response capability

### Typical Communication
- Release planning and deployment windows
- CI/CD status and pipeline improvements
- Post-deploy verification and smoke test results
- Incident response and rollback coordination

### Interactions with Existing Roles
- **Developers**: Coordinate on CI configuration, deployment automation, and smoke test implementation
- **QA/Testing**: Collaborate on pre-deployment verification, smoke tests, and environment readiness
- **Project Managers**: Support release planning, communicate deployment timelines, and escalate deployment blockers
- **Stakeholders**: Provide production verification updates and coordinate go-live announcements

---

## Security or Privacy Partner

### Role Summary
Security and Privacy Partners review security, privacy, threat, and compliance considerations. They define required controls, approvals, and ensure that products meet regulatory and organizational security standards.

### Responsibilities
- Conduct security threat modeling and risk assessments
- Define security requirements and controls
- Review designs, code, and data flows for security vulnerabilities
- Ensure compliance with relevant regulations (e.g., GDPR, HIPAA)
- Advise on incident response and breach notification procedures
- Provide security training and guidance to the team

### Goals
- Deliver secure, privacy-preserving solutions
- Reduce security and compliance risks
- Build customer trust through strong security posture

### Typical Communication
- Security requirement definitions and acceptance criteria
- Threat models and security review findings
- Compliance and regulatory alignment updates
- Incident response and post-incident reviews

### Interactions with Existing Roles
- **Product Managers**: Engage early on security and privacy requirements; advise on customer and regulatory implications
- **Technical Leads**: Collaborate on security architecture and threat mitigation strategies
- **Developers**: Provide security requirements, review code implementations, and advise on secure coding practices
- **QA/Testing**: Define security test cases and validation procedures
- **Project Managers**: Advise on security risks and escalate security-blocking issues

---

## Data/Analytics Partner

### Role Summary
Data/Analytics Partners help define instrumentation, baselines, dashboards, and success-measurement plans. They enable data-driven decision-making and outcome validation.

### Responsibilities
- Define success metrics and measurement strategies
- Design event instrumentation and data collection
- Create dashboards and reporting for key metrics
- Provide data analysis and insights to inform decisions
- Validate outcome achievement post-release
- Advise on data privacy and compliance

### Goals
- Enable data-driven product and business decisions
- Measure and demonstrate project impact and ROI
- Support continuous improvement through metrics

### Typical Communication
- Metric definitions and dashboard reviews
- Data-driven insights and trend analysis
- Post-release performance reporting
- Success criteria validation

### Interactions with Existing Roles
- **Product Managers**: Collaborate on success metrics definition and outcome measurement
- **Developers**: Guide event implementation and data collection design
- **Project Managers**: Support tracking and reporting of key metrics; communicate results to stakeholders
- **Stakeholders**: Provide performance reports and impact analysis

---

## Operations/Support or Service Owner

### Role Summary
Operations/Support or Service Owners represent operational readiness, support processes, incident response, and service-level expectations. They ensure solutions are operationally sound and customer-ready.

### Responsibilities
- Define service-level expectations and SLAs
- Design operational runbooks and incident response procedures
- Coordinate with support teams on enablement and training
- Identify operational risks and mitigation strategies
- Participate in release validation and go-live activities
- Monitor operational health and escalate issues

### Goals
- Deliver operationally ready solutions
- Minimize unplanned incidents and customer impact
- Enable smooth customer onboarding and adoption

### Typical Communication
- Operational requirements and SLA definitions
- Runbooks and incident response procedures
- Support training and enablement plans
- Post-release operational monitoring and feedback

### Interactions with Existing Roles
- **Release/DevOps Engineers**: Partner on runbooks, monitoring setup, and incident response procedures
- **QA/Testing**: Collaborate on operational acceptance readiness and failure scenario testing
- **Project Managers**: Advise on operational risks and customer readiness; coordinate go-live activities
- **Developers**: Provide operational context on failure modes and observability needs

---

## Customer Support or Customer Success Representative

### Role Summary
Customer Support or Customer Success Representatives bring customer feedback, adoption concerns, enablement needs, and known support impacts into planning and release activities. They ensure solutions meet real customer needs.

### Responsibilities
- Gather and communicate customer feedback and pain points
- Identify adoption barriers and support enablement gaps
- Collaborate on help content and customer documentation
- Participate in beta testing and early customer validation
- Plan customer communication and launch strategy
- Monitor early adoption and support escalations post-release

### Goals
- Ensure solutions address real customer needs
- Maximize customer adoption and satisfaction
- Reduce post-release support burden

### Typical Communication
- Customer feedback and feature requests
- Adoption and enablement concerns
- Support training and help content review
- Customer launch communications and announcements

### Interactions with Existing Roles
- **Product Managers**: Share customer feedback and adoption insights; inform prioritization and product direction
- **Project Managers**: Coordinate customer communications and go-live activities
- **Operations/Support**: Partner on customer readiness, support training, and post-release monitoring
- **Developers**: Provide customer context on usability and support impact of design decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning a project, identify which personas need to be engaged and at what lifecycle stages (initiation, planning, execution, release, retrospective).
- Use the interaction guidance to clarify communication patterns, handoff points, and escalation paths.
- Note that role assignments may vary by project size and organizational context—some roles may be combined or modified based on team structure.
