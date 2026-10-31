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

## Project Sponsors / Business Owners

### Role Summary
Project Sponsors or Business Owners provide executive or business-level sponsorship and are accountable for the intended business outcomes and major investment decisions.

### Responsibilities
- Confirm the business need, expected outcomes, and success measures with the Product Manager
- Secure sponsorship, funding, and organizational support
- Make or escalate major scope, funding, and priority decisions outside the team's authority
- Resolve organizational barriers and provide timely direction when significant trade-offs arise

### Goals
- Achieve the intended business outcomes
- Ensure the project has clear sponsorship and appropriate support
- Make major decisions promptly and transparently

### Typical Communication
- Project kickoff and milestone reviews
- Business outcome and investment updates with the Product Manager
- Escalations and decision reviews with the Project Manager

### Interactions and Decision Ownership
- Partners with the Product Manager to align business outcomes, success measures, and product priorities; the Product Manager continues to own the product vision and backlog.
- Works with the Project Manager on sponsorship, constraints, milestone risks, and escalations; the Project Manager continues to coordinate day-to-day delivery.
- Provides business context to Developers when technical trade-offs affect agreed outcomes, while leaving implementation decisions to the engineering team.
- Owns major business or investment decisions that are outside the delegated authority of the delivery team.

---

## Business Analysts / Domain Subject Matter Experts

### Role Summary
Business Analysts and Domain Subject Matter Experts (SMEs) translate business workflows, policies, and domain knowledge into clear requirements and examples.

### Responsibilities
- Elicit and document business rules, workflows, and requirements
- Identify assumptions, exceptions, and domain-specific constraints
- Help the Product Manager refine requirements and acceptance criteria
- Validate that proposed behavior reflects the relevant business process

### Goals
- Reduce ambiguity in requirements and domain decisions
- Ensure delivered workflows reflect business needs and constraints
- Make domain knowledge accessible to the project team

### Typical Communication
- Requirements workshops and workflow reviews
- Examples and clarifications in backlog items
- Domain decision records and stakeholder discussions

### Interactions and Decision Ownership
- Works with the Product Manager to clarify user and business needs; the Product Manager retains prioritization and product decisions.
- Coordinates with the Project Manager to surface dependencies, review availability, and domain-related risks.
- Answers Developers' implementation questions and reviews whether proposed behavior matches documented requirements.
- Advises on domain rules; the designated business owner or sponsor decides policy questions that exceed the SME's authority.

---

## UX / Accessibility Designers and Researchers

### Role Summary
UX and Accessibility Designers and Researchers represent user needs through research, interaction design, usability guidance, and accessibility requirements.

### Responsibilities
- Plan and conduct user research appropriate to the project
- Define user flows, interaction patterns, and design guidance
- Identify usability and accessibility requirements and risks
- Validate designs and implemented experiences with users or established standards

### Goals
- Make the product useful, understandable, and accessible
- Ground design decisions in user evidence
- Identify experience issues early enough to address them efficiently

### Typical Communication
- Research findings and design reviews
- Prototypes, user flows, and accessibility guidance
- Usability and accessibility findings shared with the delivery team

### Interactions and Decision Ownership
- Partners with the Product Manager to connect user needs and research findings to product outcomes and priorities.
- Collaborates with Developers on feasibility and implementation details while preserving agreed user and accessibility needs.
- Works with the Project Manager to schedule research, design reviews, and validation within the delivery plan.
- Provides design and accessibility recommendations; product scope and prioritization remain with the Product Manager, and implementation decisions remain with Developers.

---

## QA / Test Leads

### Role Summary
QA and Test Leads establish how the team will verify product behavior and manage quality evidence and defect triage.

### Responsibilities
- Define test strategy, coverage, and quality gates for the project
- Coordinate test planning and report test results and defects
- Identify quality risks and recommend mitigation or additional validation
- Support release-readiness decisions with clear test evidence

### Goals
- Detect defects and quality risks early
- Provide transparent, repeatable evidence of product quality
- Ensure acceptance criteria and critical workflows are tested

### Typical Communication
- Test plans, test results, and defect reports
- Defect triage with Developers and the Product Manager
- Quality and readiness updates with the Project Manager

### Interactions and Decision Ownership
- Works with Developers to align test coverage, automate checks where appropriate, and reproduce and resolve defects.
- Coordinates with the Product Manager to clarify acceptance criteria and assess the product impact of defects.
- Shares readiness evidence and quality risks with the Project Manager for delivery planning and status reporting.
- Owns the test approach and quality evidence; product acceptance and release authorization follow the project's designated decision process.

---

## Release / Operations Owners

### Role Summary
Release and Operations Owners prepare the service and team for deployment and ongoing operation, including monitoring and recovery.

### Responsibilities
- Define deployment, operational-readiness, monitoring, and rollback requirements
- Coordinate operational dependencies and release procedures
- Confirm that required runbooks, alerts, and support arrangements are prepared
- Surface operational risks and incidents to the appropriate owners

### Goals
- Make releases controlled, observable, and recoverable
- Ensure support teams can operate the delivered service
- Reduce deployment risk and time to recovery

### Typical Communication
- Release plans, operational-readiness checklists, and runbooks
- Deployment coordination with Developers and QA
- Readiness, dependency, and incident updates with the Project Manager

### Interactions and Decision Ownership
- Coordinates with Developers on deployment design, monitoring, and operational documentation.
- Works with QA / Test Leads to confirm release evidence and validation steps.
- Partners with the Project Manager on release dependencies, timing, readiness, and stakeholder communications.
- Owns operational readiness recommendations and procedures; release authorization remains with the person or governance process designated by the project.

---

## Security / Privacy Reviewers

### Role Summary
Security and Privacy Reviewers identify security and privacy requirements, assess relevant risks, and advise on controls and mitigations.

### Responsibilities
- Identify applicable security, privacy, and data-handling requirements
- Review relevant designs, data flows, and release risks
- Recommend controls and track review findings to resolution or explicit acceptance
- Escalate material risks through the project's established governance process

### Goals
- Protect users, data, and systems
- Surface security and privacy risks early
- Make review findings and required mitigations clear and actionable

### Typical Communication
- Design and data-flow reviews
- Risk and mitigation findings with Developers
- Review timing and escalations with the Project Manager

### Interactions and Decision Ownership
- Works with Developers to assess technical risks and agree on mitigations.
- Partners with the Product Manager to understand user impact, data use, and product requirements.
- Coordinates review timing, dependencies, and escalations with the Project Manager.
- Provides specialist findings and recommendations; risk acceptance and release decisions belong to the project's designated accountable owner or governance process.

---

## Role Assignment and Accountability

- Assign an accountable owner to each decision and responsibility, even when one person holds multiple roles.
- On smaller teams, a person may cover more than one persona; the role responsibilities and decision boundaries still apply.
- Involve relevant specialist roles early enough for their input to affect planning and delivery, and use the Project Manager to coordinate cross-role dependencies and escalations.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
