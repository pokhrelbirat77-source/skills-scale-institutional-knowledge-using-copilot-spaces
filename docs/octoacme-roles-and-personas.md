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
- **QA/Testing Professional:** Collaborate on test planning, accept defect reports, and participate in test result reviews
- **Technical Lead/Architect:** Follow architectural guidance, implement design recommendations, and escalate technical risks
- **Project Managers:** Provide estimates and progress updates, surface blockers early
- **Product Managers:** Clarify requirements and acceptance criteria

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
- **Product Lead:** Escalate major prioritization decisions and strategic trade-offs; receive mentorship on product strategy
- **Sponsor/Executive Stakeholder:** Present business case and success metrics; seek approval for major initiatives
- **Developers:** Refine acceptance criteria, clarify requirements, validate feasibility
- **QA/Testing Professional:** Define acceptance criteria and success metrics for testing

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
- **Sponsor/Executive Stakeholder:** Provide status updates, escalate business-impacting blockers, seek resource decisions
- **Product Lead:** Align on strategic priorities and timeline adjustments
- **Scrum Master/Agile Coach:** Coordinate on ceremony facilitation and team impediment removal
- **All team members:** Facilitate collaboration, manage dependencies, track progress

---

## QA/Testing Professional

### Role Summary
QA/Testing Professionals ensure product quality, validate acceptance criteria, and maintain high standards for user experience and reliability. They collaborate with developers and product teams to define testability requirements and drive quality improvements.

### Responsibilities
- Define test strategy and test plans for features and releases
- Create and maintain test cases and test automation
- Execute manual and automated testing across all environments
- Validate acceptance criteria before features move to done
- Identify and triage defects with clear reproduction steps
- Participate in test planning during sprint planning
- Recommend quality improvements and process optimizations

### Goals
- Catch defects early and prevent production incidents
- Enable faster, more confident releases through comprehensive testing
- Maintain high test coverage and automation rates

### Typical Communication
- Sprint planning and backlog refinement sessions
- Daily standups (quality status and blockers)
- Bug reports and defect triage meetings
- Release coordination and smoke test execution

### Interaction with Other Roles
- **Developers:** Collaborate on test automation, review code for testability, communicate defects and quality metrics
- **Product Managers:** Clarify acceptance criteria and validate quality requirements
- **Project Managers:** Report quality metrics and risks, coordinate testing schedules
- **Technical Lead/Architect:** Understand technical architecture to design effective test strategies

---

## Product Lead

### Role Summary
Product Leads provide senior product strategy and oversight, ensuring alignment between product initiatives, business goals, and customer needs. They mentor Product Managers and act as escalation point for major product decisions.

### Responsibilities
- Set product vision and strategic direction
- Approve roadmap priorities and major feature decisions
- Mentor and guide Product Managers on prioritization trade-offs
- Stakeholder engagement and executive communication
- Review and validate success metrics and product outcomes
- Act as escalation point for cross-product dependencies

### Goals
- Maximize customer value and business impact
- Ensure product strategy aligns with company goals
- Develop and mentor product management capability

### Typical Communication
- Weekly alignment with PM and PdM teams
- Monthly stakeholder executive briefings
- Product roadmap reviews and strategic planning sessions
- Ad-hoc escalations on priority conflicts

### Interaction with Other Roles
- **Product Managers:** Mentor on strategy, approve major decisions, guide prioritization trade-offs
- **Sponsor/Executive Stakeholder:** Present product strategy and outcomes, seek budget and resource approvals
- **Project Managers:** Align on strategic timeline and release planning
- **Developers:** Communicate product vision and strategy context for technical decisions

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors are senior business stakeholders who own project success from a business perspective. They provide strategic direction, allocate resources, and make high-level decisions that impact project scope and priority.

### Responsibilities
- Approve project charter and major scope changes
- Allocate budget and resources
- Make trade-off decisions on scope, schedule, and resources
- Provide business context and success criteria
- Escalation point for business-impacting issues
- Remove organizational blockers

### Goals
- Ensure project delivers business value on time
- Align project with strategic business initiatives
- Remove barriers to successful delivery

### Typical Communication
- Monthly stakeholder updates
- Project charter and decision gate reviews
- Escalation communications and incident notifications
- Post-project retrospectives and outcome reviews

### Interaction with Other Roles
- **Project Managers:** Receive status updates, make resource and scope decisions, escalate blockers
- **Product Leads:** Review product strategy and outcomes, approve major initiatives
- **Product Managers:** Review business case and success metrics for major features
- **Security Officer:** Approve security requirements and incident response decisions

---

## Security Officer

### Role Summary
Security Officers ensure that projects meet security requirements, maintain compliance standards, and respond to security incidents. They provide guidance on secure development practices and work with teams to identify and mitigate security risks.

### Responsibilities
- Define security requirements and compliance standards for projects
- Conduct security reviews and assessments
- Recommend secure coding practices and architectural patterns
- Coordinate security scanning and vulnerability management
- Lead incident response and post-incident reviews
- Provide security training and awareness guidance
- Act as escalation point for security-related decisions

### Goals
- Prevent security incidents and data breaches
- Ensure compliance with regulatory and organizational standards
- Build a security-conscious culture across teams

### Typical Communication
- Security requirement reviews with Product and Project Managers
- Code and architecture security reviews with Developers
- Security scanning and vulnerability reports
- Incident response and escalation communications
- Regular security updates and training sessions

### Interaction with Other Roles
- **Developers:** Provide secure coding guidance, review code for vulnerabilities, collaborate on security fixes
- **Project Managers:** Define security requirements and timeline, escalate security issues
- **Technical Lead/Architect:** Review architecture for security risks, recommend secure design patterns
- **Sponsor/Executive Stakeholder:** Report security posture and compliance status, escalate business-impacting incidents
- **QA/Testing Professional:** Coordinate on security testing and vulnerability validation

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects provide technical direction, design guidance, and oversight to ensure solutions are scalable, maintainable, and aligned with technical standards. They mentor developers and make high-level technical decisions.

### Responsibilities
- Define technical architecture and design patterns
- Provide technical direction on complex problems
- Mentor developers on technical best practices
- Review technical designs and code for quality and maintainability
- Identify and mitigate technical risks
- Make trade-off decisions on technology choices
- Ensure compliance with security and performance standards

### Goals
- Deliver scalable, maintainable, and secure solutions
- Reduce technical debt and complexity
- Enable faster development through clear architectural guidance

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and mentoring sessions
- Technical risk identification and mitigation planning
- Cross-team technical coordination and standards alignment

### Interaction with Other Roles
- **Developers:** Provide architectural guidance, review designs and code, mentor on technical practices
- **QA/Testing Professional:** Define testability requirements, review test strategies
- **Product Managers:** Consult on technical feasibility and trade-offs
- **Project Managers:** Identify technical risks and dependencies
- **Security Officer:** Collaborate on security architecture and design reviews

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove team impediments, and help teams adopt and improve agile practices. They serve as process facilitators and coaches to enable team productivity and continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove team impediments and blockers
- Coach team members on agile principles and practices
- Track sprint metrics and team velocity
- Support process improvements and retrospective action items
- Escalate organizational impediments to Project Managers
- Help teams adapt to changing requirements and priorities

### Goals
- Maximize team productivity and velocity
- Promote psychological safety and continuous improvement
- Enable teams to self-organize and make decisions

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching conversations
- Sprint metrics and retrospective discussions
- Process improvement recommendations

### Interaction with Other Roles
- **Project Managers:** Coordinate on sprint planning and timeline, escalate organizational impediments
- **Developers:** Coach on agile practices, facilitate collaboration, remove technical blockers
- **Product Managers:** Facilitate backlog refinement, help clarify requirements
- **All team members:** Facilitate ceremonies, coach on agile principles, support continuous improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction points between roles to understand collaboration patterns and communication flows.
