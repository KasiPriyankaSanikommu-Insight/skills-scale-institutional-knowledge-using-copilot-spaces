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
QA/Testing Leads ensure product quality through test strategies, automation, and acceptance-criteria validation. They make quality risks visible throughout delivery rather than only at release time.

### Responsibilities
- Define test plans and coverage expectations for features and releases
- Coordinate manual, automated, integration, and regression testing
- Validate acceptance criteria and the Definition of Done with Product Managers and developers
- Track defects, quality risks, and test results
- Recommend release readiness based on evidence

### Goals
- Prevent defects from reaching production
- Enable fast, confident releases through repeatable testing
- Maintain appropriate coverage for critical user journeys

### Success Criteria
- Acceptance criteria are testable before implementation begins
- Critical defects and quality risks are identified and tracked to resolution
- Automated and manual test results are visible before release decisions

### Typical Communication
- Test planning and acceptance-criteria reviews during refinement
- Defect triage and test-status updates with the delivery team
- Quality dashboards and release-readiness reports for stakeholders

### How They Interact with Existing Roles
- Partner with developers on testability, automation, defect diagnosis, and fixes
- Work with Product Managers to clarify acceptance criteria and prioritize quality risks
- Provide Project Managers with quality status, risks, and release recommendations

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects guide architectural decisions, technical standards, and system design. They balance delivery needs with scalability, security, maintainability, and long-term technical health.

### Responsibilities
- Lead design reviews and document significant technical decisions
- Define and promote coding, integration, and operational standards
- Identify technical risks and manage technical debt
- Mentor developers and support implementation trade-offs
- Assess the impact of proposed changes on system scalability and maintainability

### Goals
- Build systems that are scalable, secure, and maintainable
- Make timely, transparent technical decisions
- Balance short-term delivery with long-term engineering health

### Success Criteria
- Major designs and trade-offs are reviewed by the appropriate contributors
- Technical decisions, risks, and standards are documented and discoverable
- The delivered solution meets agreed architectural and operational constraints

### Typical Communication
- Design reviews, architecture decision records, and RFC discussions
- Technical spikes and implementation planning with developers
- Risk and dependency updates with Project Managers and Product Managers

### How They Interact with Existing Roles
- Guide developers through designs, standards, code reviews, and technical trade-offs
- Help Product Managers understand technical scope, risks, and sequencing options
- Provide Project Managers with technical estimates, dependencies, and risk escalations

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate Agile ceremonies, remove impediments, and coach teams on effective Scrum practices. They improve the delivery system without taking ownership away from the people doing the work.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Identify, track, and help resolve team impediments
- Coach the team on Scrum principles, flow, and continuous improvement
- Monitor delivery signals and help the team act on them
- Protect focused team collaboration from avoidable interruptions

### Goals
- Improve delivery predictability and sustainable pace
- Create psychological safety and a culture of continuous improvement
- Make blockers and process problems visible early

### Success Criteria
- Agile ceremonies produce clear decisions, commitments, and follow-up actions
- Impediments have owners and are resolved or escalated promptly
- Retrospective improvements are tested and reflected in team practices

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective discussions and action-item tracking
- Impediment escalation and process-health updates with Project Managers

### How They Interact with Existing Roles
- Help developers improve planning, collaboration, flow, and impediment resolution
- Support Product Managers with backlog refinement, prioritization readiness, and feedback loops
- Coordinate with Project Managers when team impediments affect timelines, dependencies, or risks

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical implementation. They gather requirements, document use cases, and help the team confirm that solutions address real business problems.

### Responsibilities
- Gather, analyze, and document business requirements
- Create use cases, user stories, and acceptance criteria with product and engineering
- Identify business rules, process impacts, assumptions, and dependencies
- Validate proposed solutions with users and business stakeholders
- Support traceability, sign-off, and clarification throughout delivery

### Goals
- Reduce rework caused by unclear or incomplete requirements
- Ensure delivered solutions solve meaningful business problems
- Create shared understanding between stakeholders and the delivery team

### Success Criteria
- Requirements and use cases are clear, prioritized, testable, and traceable
- Open questions and assumptions are resolved before implementation or explicitly tracked
- Stakeholders confirm that delivered outcomes meet the documented business need

### Typical Communication
- Requirements workshops and stakeholder interviews
- Backlog refinement and acceptance-criteria reviews
- Use-case walkthroughs, decision logs, and business-impact updates

### How They Interact with Existing Roles
- Work with Product Managers to translate outcomes and priorities into actionable requirements
- Clarify workflows and edge cases for developers and QA/Testing Leads
- Keep Project Managers informed about scope questions, dependencies, and stakeholder decisions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approvals, and governance. They ensure project decisions remain aligned with organizational strategy, expected value, and acceptable risk.

### Responsibilities
- Provide strategic context, priorities, constraints, and success measures
- Approve the project charter, scope, major changes, and key investments
- Participate in milestone reviews and go/no-go decisions
- Advocate for the project and help remove organizational barriers
- Resolve escalations that require business authority or cross-functional alignment

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between project outcomes and organizational strategy
- Make timely decisions and provide the team with appropriate support

### Success Criteria
- Required approvals and decisions are timely, documented, and understood
- Scope and investment remain aligned with strategic priorities
- Milestone and release decisions reflect business value, quality, risk, and readiness

### Typical Communication
- Project initiation, charter approval, and scope decisions
- Milestone reviews, stakeholder updates, and release-readiness briefings
- Escalation discussions and decision-log follow-up

### How They Interact with Existing Roles
- Set context and approve priorities with Product Managers
- Rely on Project Managers for status, risks, dependencies, and escalation options
- Review outcomes and trade-offs informed by developers, Technical Leads, QA/Testing Leads, and Business Analysts

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
