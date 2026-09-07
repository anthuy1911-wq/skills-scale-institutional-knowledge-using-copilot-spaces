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

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure software quality through comprehensive testing strategies, test planning, and acceptance criteria validation. They work closely with developers and product managers to define testability requirements and validate that features meet quality standards before release.

### Responsibilities
- Create and maintain test plans and test cases
- Define acceptance criteria and Definition of Done for testing
- Perform manual and coordinate automated testing
- Validate features against acceptance criteria
- Report bugs and track quality metrics
- Advise on test coverage and risk mitigation

### Goals
- Ensure high-quality releases with minimal defects
- Reduce time between development and production readiness
- Maintain test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- Test case reviews and acceptance sign-off
- Bug reports and quality metrics reporting
- Design reviews for testability input

### Interaction with Other Roles
- **With Developers**: Collaborate on test design and coverage; provide feedback on test cases and quality issues
- **With Product Managers**: Validate feature acceptance criteria and ensure quality expectations align with business goals
- **With Project Managers**: Report quality metrics, manage testing timelines, escalate blockers affecting release readiness
- **With Technical Leads**: Work on architectural concerns impacting testability; advise on test infrastructure needs

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide the technical strategy, design decisions, and architectural patterns for projects. They ensure solutions are scalable, maintainable, and align with organizational standards.

### Responsibilities
- Design system architecture and technical approach
- Review designs and provide architectural guidance
- Identify technical risks and propose mitigations
- Mentor developers on technical best practices
- Evaluate technology choices and trade-offs
- Ensure code quality and standards adherence

### Goals
- Deliver technically sound, maintainable solutions
- Build scalable systems that support future growth
- Reduce technical debt and complexity

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and technical guidance
- Risk assessments and decision documentation

### Interaction with Other Roles
- **With Developers**: Mentor on best practices; guide design and implementation decisions; support technical problem-solving
- **With Project Managers**: Identify and communicate technical risks; advise on timeline and resource implications of technical decisions
- **With Product Managers**: Collaborate on feature feasibility; discuss technical trade-offs and long-term scalability implications
- **With DevOps/Infrastructure Engineers**: Align on deployment architecture and infrastructure requirements

---

## Stakeholder/Business Sponsor

### Role Summary
Stakeholders and Business Sponsors represent business interests, approve resources, and drive project priorities. They ensure projects align with organizational strategy and business value.

### Responsibilities
- Approve project scope, timeline, and resource allocation
- Define business objectives and success metrics
- Escalate blockers and risks to executive level
- Provide subject matter expertise and business context
- Participate in key decision gates (initiation, release, etc.)

### Goals
- Maximize business value and return on investment
- Ensure strategic alignment with organizational goals
- Mitigate business risks

### Typical Communication
- Milestone approvals and gate reviews
- Monthly stakeholder status updates
- Executive escalations for major risks or decisions

### Interaction with Other Roles
- **With Project Managers**: Approve schedules, scope changes, and resource allocation; review risk escalations
- **With Product Managers**: Align on business objectives, priorities, and success metrics
- **With Developers and Technical Leads**: Understand technical feasibility and constraints for business decisions

---

## Scrum Master/Delivery Coordinator

### Role Summary
Scrum Masters and Delivery Coordinators facilitate team ceremonies, remove blockers, and coach the team on agile practices. They enable smooth workflow and support the team in delivering value iteratively.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and remove impediments and blockers
- Coach team members on agile practices and continuous improvement
- Track and report team metrics (velocity, burndown, cycle time)
- Support effective communication and collaboration

### Goals
- Maximize team productivity and efficiency
- Foster a culture of continuous improvement
- Maintain healthy team dynamics and psychological safety

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching conversations
- Metrics and retrospective action item tracking

### Interaction with Other Roles
- **With Project Managers**: Collaborate on scheduling, escalate blockers, support risk management
- **With Developers**: Coach on agile practices; help remove impediments; facilitate pair programming and knowledge sharing
- **With All Roles**: Ensure transparent communication; facilitate conflict resolution; maintain psychological safety

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects adhere to security best practices, regulatory requirements, and organizational policies. They work proactively to identify and mitigate security and compliance risks.

### Responsibilities
- Review designs and implementations for security vulnerabilities
- Ensure compliance with regulatory and organizational standards
- Conduct security assessments and penetration testing coordination
- Advise on secure coding practices and security architecture
- Manage incident response and post-incident analysis

### Goals
- Prevent security breaches and compliance violations
- Build security awareness across the organization
- Maintain customer trust and organizational reputation

### Typical Communication
- Design reviews and threat modeling sessions
- Security assessment reports and recommendations
- Incident response and post-mortems
- Training and awareness communications

### Interaction with Other Roles
- **With Developers**: Advise on secure coding practices; review code for vulnerabilities; provide security training
- **With Technical Leads**: Collaborate on secure architecture design; review technical decisions for security implications
- **With Project Managers**: Escalate security risks; advise on compliance timelines and resource needs
- **With DevOps/Infrastructure Engineers**: Review infrastructure security; advise on secure deployment practices

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers manage deployment infrastructure, CI/CD pipelines, and production support. They enable teams to deploy reliably and maintain system health.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure, databases, and deployment environments
- Ensure system reliability, monitoring, and alerting
- Support production incidents and troubleshooting
- Automate manual processes and improve deployment velocity

### Goals
- Enable fast, reliable deployments
- Maintain system uptime and performance
- Reduce deployment risk and cycle time

### Typical Communication
- Pre-release deployment reviews and smoke test coordination
- Infrastructure capacity and architecture discussions
- Production incident response and post-mortems

### Interaction with Other Roles
- **With Developers**: Support local development environments; advise on deployment requirements; troubleshoot production issues
- **With Technical Leads**: Collaborate on infrastructure architecture; advise on scalability and performance concerns
- **With Project Managers**: Provide deployment timelines and resource estimates; coordinate release logistics
- **With Security/Compliance Officers**: Implement security best practices in infrastructure; maintain compliance controls

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When working on cross-functional projects, refer to the "Interaction with Other Roles" section to understand communication patterns and dependencies.
