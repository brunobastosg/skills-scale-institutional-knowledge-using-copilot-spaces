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
QA/Testing Leads own quality assurance strategy, test planning, and validation activities. They collaborate with developers and product teams to ensure features meet acceptance criteria and quality standards.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Define testing strategy (unit, integration, end-to-end, manual QA)
- Execute or coordinate test execution and report results
- Identify and track quality risks and regressions
- Participate in sprint planning and estimation
- Validate acceptance criteria before marking work as done

### Goals
- Ensure features are production-ready and meet quality standards
- Reduce production defects and customer-impacting issues
- Maintain test coverage and automation to support rapid iteration

### Typical Communication
- Sprint planning and estimation sessions
- Daily standups and status updates
- Test reports and quality metrics dashboards
- Acceptance criteria reviews and clarification discussions

### Interaction with Existing Roles
- **Developers:** Work closely during implementation to define test requirements and review test results
- **Product Managers:** Align on acceptance criteria and quality expectations for features
- **Project Managers:** Report on quality metrics and risks that may impact timeline

---

## Product Lead

### Role Summary
Product Leads provide strategic oversight of product initiatives, approve project charters, and serve as decision-makers for prioritization conflicts and cross-functional trade-offs.

### Responsibilities
- Review and approve Project One-pagers during initiation phase
- Make prioritization decisions and resolve backlog conflicts
- Serve as escalation point for product-level risks and dependencies
- Align projects with overall product strategy and roadmap
- Provide executive visibility into project status and outcomes

### Goals
- Ensure projects deliver strategic value
- Maintain alignment across multiple concurrent initiatives
- Maximize product impact and customer satisfaction

### Typical Communication
- Milestone reviews and decision gates
- Weekly PM + PdM sync (as approver/stakeholder)
- Status updates and strategic alignment discussions
- Escalation meetings for high-impact decisions

### Interaction with Existing Roles
- **Product Managers:** Approve product direction and resolve prioritization conflicts
- **Project Managers:** Participate in go/no-go decision gates and escalation discussions
- **Developers:** Communicate strategic direction and constraints for technical decisions

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors provide business case validation, organizational support, and resource allocation for significant initiatives. They are the executive champion and decision authority for go/no-go gates.

### Responsibilities
- Validate business case and ROI assumptions
- Allocate resources (budget, team capacity, tools)
- Support risk escalation and removal of organizational blockers
- Receive and approve major milestone and release announcements
- Participate in decision gates and high-impact trade-off discussions

### Goals
- Ensure projects align with business strategy
- Remove organizational barriers to project success
- Maximize return on investment and business impact

### Typical Communication
- Initiation and planning phase gate meetings
- Monthly executive updates on strategic initiatives
- Escalation for resource or priority conflicts
- Post-release announcements and retrospective summaries

### Interaction with Existing Roles
- **Product Leads:** Collaborate on strategic alignment and investment decisions
- **Project Managers:** Escalation point for critical blockers and resource constraints
- **All team members:** Provide organizational support and executive visibility

---

## Security Lead

### Role Summary
Security Leads integrate security requirements, scanning, and incident response into the project lifecycle. They ensure compliance and risk mitigation across design, development, and deployment.

### Responsibilities
- Define security requirements and acceptance criteria
- Review design and architecture for security implications
- Ensure security scanning is enabled in CI/CD pipeline
- Coordinate security reviews and vulnerability assessments
- Lead or participate in security incident response
- Track and report security metrics and compliance status

### Goals
- Minimize security vulnerabilities and compliance gaps
- Enable rapid, secure feature delivery
- Support blameless incident response and learning

### Typical Communication
- Design reviews and security assessments
- CI/CD configuration and security scanning setup
- Incident communication and post-mortems
- Security metrics dashboards and compliance reports

### Interaction with Existing Roles
- **Developers:** Review code and architecture for security risks; provide secure coding guidance
- **QA/Testing Lead:** Coordinate on security testing and vulnerability assessment strategies
- **Project Managers:** Report on security risks and blockers; participate in release planning
- **Incident Responder:** Collaborate on incident response and post-incident reviews

---

## Incident Responder / On-Call Engineer

### Role Summary
On-Call Engineers are responsible for triaging, responding to, and escalating production incidents. They follow incident runbooks and coordinate with other functions to minimize downtime and customer impact.

### Responsibilities
- Triage incoming alerts and incidents
- Follow incident response runbooks and escalation procedures
- Communicate incident status to stakeholders
- Coordinate with development and security teams for resolution
- Participate in blameless post-incident reviews
- Contribute to runbook refinement based on lessons learned

### Goals
- Minimize time-to-detection and time-to-resolution for production issues
- Maintain system reliability and customer trust
- Capture and implement lessons learned from incidents

### Typical Communication
- Incident severity notifications and escalation alerts
- Real-time incident status updates (Slack, war room, etc.)
- Post-incident blameless retrospectives
- Runbook and playbook updates

### Interaction with Existing Roles
- **Developers:** Coordinate on hotfixes and root cause analysis
- **Security Lead:** Collaborate on security-related incidents and vulnerabilities
- **Project Managers:** Provide incident impact assessment and escalation support
- **QA/Testing Lead:** Verify fixes and test incident resolutions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
