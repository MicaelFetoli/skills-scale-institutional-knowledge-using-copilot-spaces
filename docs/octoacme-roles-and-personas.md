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

## Security Champion

### Role Summary
The Security Champion is a cross-functional advisor accountable for ensuring security considerations are surfaced early and addressed through delivery, release, and operations.

### Responsibilities
- Review architecture, feature designs, and dependencies for security risks and compliance considerations
- Partner with developers and PMs to integrate security requirements into the backlog and release plans
- Coordinate security testing, threat review, and remediation follow-up
- Escalate high-risk issues to the appropriate owner and sponsor when needed

### Interactions with Existing Roles
- Works with Developers to review secure implementation patterns and testing requirements
- Coordinates with Project Managers on risk tracking, milestones, and mitigation planning
- Supports Product Managers by clarifying trade-offs between customer value, speed, and security risk
- Provides security input to release readiness and incident response planning

### Goals
- Reduce preventable security risk across the lifecycle
- Make security requirements clear, actionable, and measurable
- Promote secure-by-default delivery without slowing critical work unnecessarily

### Typical Communication
- Design review meetings and security checkpoints
- Risk register updates and incident escalation paths
- Release-readiness discussions and compliance reviews

---

## Release Manager

### Role Summary
The Release Manager coordinates the operational readiness of a release so changes are deployed predictably, monitored effectively, and communicated clearly.

### Responsibilities
- Own the release checklist and deployment timeline for milestones and production launches
- Confirm readiness across engineering, QA, stakeholders, and support teams
- Coordinate rollback, contingency, and communication plans for critical releases
- Support post-release verification, issue triage, and stakeholder updates

### Interactions with Existing Roles
- Collaborates with Developers and QA to confirm acceptance criteria and deployment readiness
- Works with Project Managers to align release timing with dependent milestones and stakeholder commitments
- Partners with Product Managers to communicate release scope and customer impact
- Escalates operational risk to sponsors or leadership when the release poses business exposure

### Goals
- Improve deployment reliability and transparency
- Reduce launch-day surprises and operational confusion
- Ensure the release process supports a predictable customer experience

### Typical Communication
- Release readiness meetings and launch checklists
- Weekly delivery updates and milestone communication
- Post-deploy review notes and incident updates

---

## Customer Success Partner

### Role Summary
The Customer Success Partner brings the voice of customers and support teams into planning and delivery so product work remains aligned with real user needs and adoption goals.

### Responsibilities
- Surface customer feedback, support trends, and adoption issues affecting product quality or satisfaction
- Help prioritize improvements based on user pain points, retention, and support load
- Align product changes with onboarding, enablement, and customer communication needs
- Participate in milestone reviews and launch readiness for customer-facing updates

### Interactions with Existing Roles
- Supports Product Managers with insights that shape roadmap priorities and success metrics
- Works with Developers and QA to validate whether fixes and features solve real user problems
- Coordinates with Project Managers to flag customer-impacting risks or delivery dependencies
- Contributes stakeholder context to release communications and follow-up plans

### Goals
- Improve customer experience and adoption outcomes
- Ensure product decisions consider real-world usage and support impact
- Reduce friction between product delivery and customer-facing teams

### Typical Communication
- Customer feedback review sessions
- Weekly stakeholder and roadmap updates
- Launch and post-launch success review discussions

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead ensures that project decisions are informed by measurable outcomes, operational health, and customer value signals.

### Responsibilities
- Define success metrics, dashboards, and reporting needs for the initiative
- Partner with Product Managers to evaluate whether the work is delivering expected outcomes
- Monitor key signals such as adoption, quality, latency, and conversion or engagement metrics
- Identify data and instrumentation gaps that affect product learning or operational decision-making

### Interactions with Existing Roles
- Provides Product Managers with evidence to prioritize work and validate impact
- Collaborates with Developers on instrumentation, testing, and observability requirements
- Works with Project Managers to connect project milestones to measurable outcomes and risks
- Supports stakeholders with clear summaries of adoption, quality, and business impact

### Goals
- Make outcomes visible and decision-ready
- Improve learning loops and evidence-based prioritization
- Reduce uncertainty in roadmap and release decisions

### Typical Communication
- Metric reviews and dashboard check-ins
- Planning sessions for instrumentation and reporting
- Readout of project performance at milestones and retrospectives

---

## Dependencies / Integration Lead

### Role Summary
The Dependencies / Integration Lead owns cross-team coordination so work is sequenced correctly, contracts are clear, and integration points are managed proactively.

### Responsibilities
- Identify internal and external dependencies, integration risks, and sequencing constraints
- Maintain alignment across teams that share APIs, data, tooling, or business workflows
- Coordinate decision-making and escalation when dependency owners are blocked or misaligned
- Track readiness for milestones that depend on downstream delivery or partner teams

### Interactions with Existing Roles
- Assists Project Managers with risk management and milestone coordination
- Works with Developers and QA to validate integration readiness and test coverage
- Supports Product Managers by clarifying timing and trade-offs for scope or sequencing
- Escalates cross-team blockers to sponsors or leadership when business impact is significant

### Goals
- Reduce delivery delays caused by hidden dependencies
- Improve coordination across teams and systems
- Make integration readiness a visible, managed part of project execution

### Typical Communication
- Dependency review meetings
- Cross-team planning and milestone checkpoint updates
- Escalation summaries and risk action tracking

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These additional roles help clarify decision ownership, accountability, and handoffs across delivery, operations, customer impact, and risk management.

