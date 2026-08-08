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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## QA / Testing Lead

### Role Summary
QA/Testing Leads ensure product quality through comprehensive testing strategies, acceptance criteria validation, and defect management. They collaborate with developers and product managers to define quality standards and drive continuous improvement in testing practices.

### Responsibilities
- Design and execute test plans aligned with acceptance criteria
- Manage defect lifecycle and coordinate resolutions with developers
- Define QA approach and testing strategy during planning phase
- Validate release readiness through smoke tests and acceptance testing
- Mentor team members on testing best practices and automation
- Collaborate with Security on security testing requirements

### Goals
- Minimize defects reaching production
- Reduce time spent on rework and firefighting
- Build confidence in release quality through comprehensive testing
- Establish measurable quality metrics and trends

### Typical Communication
- Daily standups and sprint planning
- QA status updates in weekly delivery sync
- Test plan reviews with Product Manager
- Defect triage sessions with developers

### Key Interactions
- **Developers**: Reviews acceptance criteria, collaborates on test case design, coordinates defect investigations
- **Product Manager**: Validates that features meet success metrics and user expectations
- **Project Manager**: Provides QA status updates, escalates quality risks
- **Security Officer**: Coordinates security testing requirements

---

## Technical Architect

### Role Summary
Technical Architects lead system design and technical strategy. They ensure solutions are scalable, maintainable, and aligned with organizational technical standards. They advise on technology choices and risk mitigation.

### Responsibilities
- Define system architecture and technical approach for complex initiatives
- Review design proposals for scalability, performance, and maintainability
- Assess technical risks and propose mitigation strategies
- Ensure alignment with organizational standards and best practices
- Mentor developers on architectural patterns and design principles
- Advise on technology selections and trade-offs

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and rework
- Enable fast, confident decision-making on technical choices
- Support team capability growth

### Typical Communication
- Design review meetings during planning and execution
- Technical architecture documents and decision logs (ADRs)
- Consultation with developers on implementation questions
- Risk escalation to Project Manager when needed

### Key Interactions
- **Developers**: Provides technical guidance, reviews implementation for alignment with architecture
- **Project Manager**: Escalates architectural risks and complexity considerations
- **Product Manager**: Discusses technical feasibility of features and trade-offs
- **QA/Testing Lead**: Advises on testability and performance testing requirements

---

## Security / Compliance Officer

### Role Summary
Security/Compliance Officers embed security practices throughout the project lifecycle. They ensure solutions meet security requirements, compliance standards, and organizational policies. They lead incident response and security training.

### Responsibilities
- Define security requirements and acceptance criteria
- Review designs and code for security vulnerabilities
- Coordinate security scanning and penetration testing
- Manage security incident response and post-incident reviews
- Ensure compliance with regulatory and organizational policies
- Advise on secure coding practices and threat modeling

### Goals
- Prevent security breaches and compliance violations
- Shift security left (early in development cycle)
- Build security awareness across teams
- Minimize risk to customer data and organizational reputation

### Typical Communication
- Security requirements definition during planning
- Code and design reviews with developers
- Security testing status in weekly sync
- Incident response escalations

### Key Interactions
- **Developers**: Reviews code for security issues, provides secure coding guidance
- **QA/Testing Lead**: Coordinates security testing and penetration testing activities
- **Project Manager**: Escalates security risks and compliance concerns
- **Technical Architect**: Reviews architectural decisions for security implications

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters enable agile teams by removing blockers, facilitating ceremonies, and coaching the team toward continuous improvement. They foster psychological safety and iterative delivery practices.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and remove blockers to team progress
- Coach team on agile practices and frameworks
- Monitor team velocity and capacity
- Shield team from distracting interruptions
- Champion continuous improvement culture
- Escalate impediments the team cannot resolve

### Goals
- Enable high-performing, self-organizing teams
- Increase delivery predictability and velocity
- Build psychological safety and team cohesion
- Support continuous learning and improvement

### Typical Communication
- Facilitation of daily standups and ceremonies
- One-on-one coaching with team members
- Retrospective action item tracking
- Escalation summaries to Project Manager

### Key Interactions
- **Developers**: Removes blockers, facilitates collaboration
- **Project Manager**: Escalates unresolved impediments and risks
- **Product Manager**: Supports backlog refinement and acceptance criteria clarity
- **All Roles**: Fosters team psychological safety and continuous improvement

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, decision-making authority, and resource support. They represent customer, business, or organizational needs and have accountability for project success.

### Responsibilities
- Define business case and success criteria
- Provide decision-making authority on trade-offs and priorities
- Secure necessary budget and resources
- Receive regular status updates and provide guidance
- Approve release and go/no-go decisions
- Support escalation resolution at organizational level

### Goals
- Ensure project delivers intended business value
- Provide clear direction and remove organizational blockers
- Enable informed decision-making across stakeholders
- Support successful adoption and handoff

### Typical Communication
- Monthly stakeholder updates
- Milestone reviews and decision gates
- Escalation communications on risks and roadblocks
- Post-project retrospective and value realization review

### Key Interactions
- **Project Manager**: Receives status updates, approves decisions and resource requests
- **Product Manager**: Collaborates on success metrics and customer feedback
- **Developers**: May participate in key milestone reviews and design walkthroughs
- **All Roles**: Provides business context and decision authority when escalated

---

### Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
