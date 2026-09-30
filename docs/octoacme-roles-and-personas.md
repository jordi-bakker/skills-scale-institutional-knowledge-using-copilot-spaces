# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core vs. Context-Dependent Roles

Not every project needs every role at the same level of involvement. Use the following distinction to keep accountability clear without creating unnecessary overhead:

### Core roles
These roles are usually required for a project to move from initiation to delivery and release:
- Developers
- Product Managers
- Project Managers
- QA / Testing
- Stakeholders
- Business Sponsor / Executive Sponsor

### Context-dependent roles
These roles are added when the initiative requires specialist expertise, cross-team coordination, user experience work, compliance review, operational readiness, or dependency management:
- UX / Product Designer
- Technical Lead / Architect
- Delivery Lead / Scrum Master
- Operations / SRE / Release Manager
- Security / Privacy Representative
- Data / Analytics Representative
- Customer Success / Support Representative
- Subject-Matter Expert / Dependency Owner

### Role assignment guidance
- Assign multiple roles to one person when the project is small or the team is lean, but keep the accountability model explicit.
- For larger or higher-risk work, separate decision-making, delivery ownership, and review functions to reduce bottlenecks.
- Document who is accountable for each decision, handoff, and escalation path in the project README, backlog, or risk register.

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

## Business Sponsor / Executive Sponsor

### Role Summary
Business Sponsors provide strategic sponsorship, authorize priority trade-offs, and help resolve escalations that affect business outcomes, resource allocation, or critical commitments.

### Responsibilities
- Confirm project value and business case
- Support funding, staffing, or prioritization decisions
- Resolve cross-functional conflicts when business impact is material
- Sponsor key milestones, decision gates, and changes in scope or timeline
- Review progress against strategic outcomes and major risks

### Goals
- Ensure the initiative delivers meaningful business value
- Protect the team from avoidable interruptions or unclear mandates
- Maintain alignment between project execution and strategic goals

### Typical Communication
- Executive briefings, milestone reviews, and escalation updates
- Decisions on priority, funding, and major risks
- Sponsor check-ins during planning and release approval gates

### Interaction with existing roles
- Works with the Product Manager on outcome prioritization and business case validation
- Works with the Project Manager on escalations, resourcing, and timeline trade-offs
- Supports the Technical Lead, Developers, and Operations team by providing clear strategic direction and escalation authority
- Helps Stakeholders understand business impact and sponsor decisions when necessary

---

## UX / Product Designer

### Role Summary
UX or Product Designers ensure the experience is usable, coherent, and aligned to customer needs. They translate user needs into flows, interaction design, and acceptance criteria that support delivery quality.

### Responsibilities
- Conduct discovery, user research, and usability input when needed
- Define or refine user flows, interaction patterns, and interface requirements
- Collaborate on acceptance criteria, edge cases, and accessibility needs
- Review designs with Product, Engineering, and QA before implementation
- Help identify experience risks and propose iterative improvements

### Goals
- Improve usability, clarity, and customer satisfaction
- Reduce rework caused by ambiguous or weak user experience requirements
- Ensure design decisions align with customer and business goals

### Typical Communication
- Design reviews, user research summaries, and feedback loops
- Collaboration in planning, refinement, and QA validation
- Updates to product and engineering stakeholders on usability trade-offs

### Interaction with existing roles
- Partners closely with the Product Manager to connect customer needs to the roadmap
- Works with Developers to validate implementation against UX intent
- Provides input to QA/Testing for usability acceptance and regression checks
- Coordinates with Stakeholders when experience decisions affect customer expectations or business goals

---

## Technical Lead / Architect

### Role Summary
Technical Leads or Architects guide technical direction, design decisions, and non-functional requirements. They reduce architectural drift and ensure solutions are maintainable, secure, and scalable.

### Responsibilities
- Define technical architecture, standards, and design patterns
- Guide trade-offs between speed, cost, reliability, and maintainability
- Review technical risks, dependencies, and integration points
- Support design and code review quality for critical decisions
- Align engineering work with security, operations, and performance expectations

### Goals
- Keep the solution technically sound and sustainable
- Minimize avoidable technical debt and integration failures
- Enable the delivery team to make good decisions without excessive redesign

### Typical Communication
- Architecture reviews, design discussions, and technical dependency updates
- Coordination with Project Managers and Product Managers on trade-offs and milestones
- Cross-team technical planning and escalation for high-risk decisions

### Interaction with existing roles
- Works with Developers to shape implementation approach and review technical quality
- Collaborates with the Product Manager on feasibility, sequencing, and trade-offs
- Coordinates with Security and Operations on compliance, reliability, and incident-readiness
- Helps the Project Manager identify technical dependencies and delivery risk early

---

## Delivery Lead / Scrum Master

### Role Summary
Delivery Leads or Scrum Masters improve team flow and delivery practices. They facilitate alignment and remove impediments without replacing accountability for product or project outcomes.

### Responsibilities
- Facilitate ceremonies such as sprint planning, standups, reviews, and retrospectives
- Remove or escalate blockers that slow delivery
- Help the team improve flow, focus, and predictability
- Support a healthy working agreement and decision-making process
- Track delivery health, patterns, and improvement opportunities

### Goals
- Improve team rhythm and throughput without creating process overhead
- Identify and resolve friction early
- Support a sustainable, collaborative delivery environment

### Typical Communication
- Team rituals, backlog refinement sessions, and issue tracking updates
- Working agreement and process guidance
- Coordination with PMs and engineering leads on team-level impediments

### Interaction with existing roles
- Supports the Project Manager and Developers by improving team execution and reducing blockers
- Works with the Product Manager to keep backlog health and prioritization discussions productive
- Does not replace product ownership or project accountability; instead, helps the team operate effectively
- Escalates systemic issues to the Project Manager or Sponsor when needed

---

## Operations / SRE / Release Manager

### Role Summary
Operations, SRE, and Release Managers ensure systems are reliable, observable, and ready for deployment. They coordinate readiness and rollback preparation across the lifecycle.

### Responsibilities
- Define operational readiness checks and deployment guardrails
- Monitor observability, reliability, and production health signals
- Coordinate release windows, rollback planning, and incident handling readiness
- Support post-deployment validation and mitigations when issues appear
- Partner with Developers and QA to ensure production readiness

### Goals
- Reduce deployment risk and production disruption
- Maintain a clear path to recovery during incidents or failed changes
- Ensure customer impact is minimized through proactive monitoring and readiness

### Typical Communication
- Release readiness reviews, rollback planning, and operational status updates
- Incident communications and recovery coordination
- Dependency tracking with engineering, security, and product teams

### Interaction with existing roles
- Works with Developers and QA/Testing to validate release quality and regression risk
- Coordinates with the Project Manager on release timing, stakeholder communication, and rollback decisions
- Supports the Security / Privacy Representative on secure deployment and operational controls
- Helps the Product Manager and Stakeholders communicate impact and readiness before launch

---

## Security / Privacy Representative

### Role Summary
Security and Privacy representatives ensure the solution meets required safeguards, compliance expectations, and risk controls throughout the lifecycle.

### Responsibilities
- Review threats, vulnerabilities, and privacy risks early in planning and delivery
- Define secure design requirements, review checkpoints, and compliance expectations
- Coordinate security testing and remediation with Developers and QA
- Support release approval when security or privacy controls are required
- Help establish clear escalation paths for incidents or policy violations

### Goals
- Reduce preventable security and privacy risks
- Ensure work meets the organization’s standards and obligations
- Embed security and privacy expectations into delivery instead of treating them as late-stage gates

### Typical Communication
- Security review meetings, privacy check-ins, and remediation follow-ups
- Release readiness and risk escalation updates
- Collaboration with technical and operational stakeholders on controls and validation

### Interaction with existing roles
- Advises the Technical Lead and Developers on secure design and implementation patterns
- Reviews work with QA/Testing before release and during validation
- Coordinates with the Project Manager on risk tracking and reporting
- Supports Operations and Release planning to ensure production safety and compliance

---

## Data / Analytics Representative

### Role Summary
Data and Analytics representatives define the instrumentation, reporting, and measurement approach needed to evaluate outcomes and validate whether the project is creating value.

### Responsibilities
- Define metrics, dashboards, and instrumentation plans
- Support event tracking, quality checks, and measurement alignment
- Help validate whether product or operational outcomes are being met
- Connect product, engineering, and stakeholder success reporting
- Identify data quality, privacy, and reporting issues early

### Goals
- Ensure decisions are informed by reliable data
- Make progress and impact measurable across delivery and release
- Support evidence-based iteration and improvement

### Typical Communication
- Success metrics reviews, reporting checkpoints, and instrumentation updates
- Gap analysis with Product and Project leadership
- Coordination with engineering and analytics tooling stakeholders

### Interaction with existing roles
- Works with the Product Manager to define success metrics and validate outcomes
- Collaborates with Developers and QA/Testing to confirm tracking accuracy and reporting assumptions
- Supports the Project Manager in milestone and status reporting
- Helps Stakeholders understand measurable business or user impact

---

## Customer Success / Support Representative

### Role Summary
Customer Success and Support representatives bring frontline user and customer context to project planning and release activities. They help ensure that customer impact, readiness, and communication needs are represented.

### Responsibilities
- Share customer pain points, support trends, and service-impact observations
- Help define readiness, change communication, and onboarding needs
- Validate whether the solution addresses real customer workflows and service issues
- Support launch readiness and stakeholder messaging for customer-facing changes
- Escalate operational or customer-impact concerns during rollout and incident response

### Goals
- Improve customer experience and reduce avoidable confusion during change cycles
- Align product changes with real-world usage and support realities
- Strengthen readiness and communication around launches or incidents

### Typical Communication
- Feedback loops with Product, Project, and Release teams
- Support or customer-impact summaries during planning and launch phases
- Coordination with incident and release stakeholders when user impact is involved

### Interaction with existing roles
- Brings customer context to the Product Manager and Project Manager
- Helps Developers and QA/Testing understand real-world edge cases and risk areas
- Supports Operations and Release teams with readiness and communication needs
- Works with Stakeholders to communicate customer impact and adoption considerations

---

## Subject-Matter Expert / Dependency Owner

### Role Summary
Subject-Matter Experts (SMEs) and Dependency Owners provide specialized knowledge or cross-team commitments needed for success. They help reduce ambiguity, unblock decisions, and identify risk areas that are outside the core project team.

### Responsibilities
- Provide domain expertise, validation, or approval in a specific area
- Own critical dependencies, integrations, or external commitments
- Help define requirements, constraints, and acceptance considerations for specialist work
- Participate in reviews, planning, and escalation when a dependency is at risk
- Support risk mitigation and contingency planning for cross-team deliverables

### Goals
- Reduce delays caused by unclear ownership or missing expertise
- Ensure critical decisions are informed by the right specialists
- Preserve accountability for external dependencies and cross-functional delivery commitments

### Typical Communication
- Dependency reviews, domain-specific clarifications, and integration check-ins
- Planning inputs, handoff updates, and escalation notices when timelines are at risk
- Updates recorded in the risk register or project board

### Interaction with existing roles
- Provides expertise directly to the Product Manager, Developers, and Technical Lead
- Helps the Project Manager track risks, dependencies, and escalation paths
- May work with Security, Operations, or Data teams when cross-functional controls or measurements are required
- Provides explicit accountability for decisions or outputs that influence project milestones

---

## Role Interaction Matrix

Use this matrix to clarify who typically owns, informs, or reviews key project decisions:

- Product value and prioritization: Product Manager + Sponsor + Stakeholders
- Delivery planning and coordination: Project Manager + Development team + Delivery Lead
- User experience and usability: Product Manager + UX / Product Designer + QA
- Technical design and architecture: Technical Lead + Developers + Security / Privacy
- Release readiness and rollout: Operations / SRE / Release Manager + Project Manager + QA
- Security and compliance: Security / Privacy Representative + Technical Lead + Developers
- Outcome measurement: Product Manager + Data / Analytics Representative + Stakeholders
- Customer impact and support readiness: Customer Success / Support Representative + Product Manager + Release team
- Cross-team dependencies: Project Manager + Subject-Matter Expert / Dependency Owner + relevant team leads

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Keep the role model lightweight: add only the roles needed for the initiative, and document the accountable owner for each decision and handoff.

