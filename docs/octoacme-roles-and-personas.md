# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Note:** This document was expanded based on analysis in [Issue #4](https://github.com/GijsL/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to address gaps in persona coverage and improve clarity, accountability, and cross-team collaboration.

---

## Core Roles

<!-- 
Rationale: Core roles are foundational team members involved in every project.
These personas interact most frequently and drive day-to-day delivery.
-->

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions with Other Roles
- **Product Managers:** Receive requirements and acceptance criteria; provide technical feasibility feedback
- **Project Managers:** Report progress and blockers; collaborate on estimates and timeline
- **QA/Testers:** Collaborate on test coverage and bug resolution
- **UX/UI Designers:** Implement designs and provide feedback on feasibility
- **Security Engineers:** Address security findings and implement secure coding practices
- **DevOps Engineers:** Collaborate on CI/CD pipelines and deployment processes

---

### Product Managers (PdM)

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions with Other Roles
- **Project Managers:** Align on priorities, timelines, and resource allocation
- **Developers:** Define acceptance criteria; clarify requirements
- **Stakeholders:** Gather input and communicate roadmap decisions
- **UX/UI Designers:** Collaborate on feature scope and user experience
- **Business Analysts:** Review requirements analysis and business impact
- **Customer Support:** Receive user feedback and prioritize fixes

---

### Project Managers (PM)

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions with Other Roles
- **Product Managers:** Align on priorities and communicate delivery status
- **Developers:** Track progress and remove blockers
- **Stakeholders:** Provide updates and manage expectations
- **DevOps Engineers:** Coordinate release schedules
- **QA/Testers:** Ensure quality gates are met before releases
- **All roles:** Facilitate cross-team communication and escalation

---

### QA/Testers

<!-- 
Rationale: QA/Testers are referenced throughout other process docs but were 
not fully defined. Adding this section ensures consistency and clear ownership
for quality assurance activities.
-->

#### Role Summary
QA/Testers validate that software meets acceptance criteria and quality standards before release. They identify bugs, ensure test coverage, and advocate for end-user quality.

#### Responsibilities
- Create and execute test plans (manual and automated)
- Validate acceptance criteria and Definition of Done
- Report and track defects to resolution
- Perform regression testing before releases
- Collaborate on test automation strategy

#### Goals
- Ensure high-quality releases with minimal defects
- Maintain comprehensive test coverage
- Reduce time from bug discovery to resolution

#### Typical Communication
- Bug reports and test status updates
- Test plan reviews with Developers and PMs
- QA sign-off at sprint/release gates

#### Interactions with Other Roles
- **Developers:** Collaborate on bug fixes and test coverage
- **Product Managers:** Clarify acceptance criteria
- **Project Managers:** Report quality status and blockers
- **DevOps Engineers:** Integrate tests into CI/CD pipelines
- **Customer Support:** Validate reported issues

---

### Stakeholders

<!-- 
Rationale: Stakeholders are frequently referenced but not formally defined.
This section clarifies their role in providing inputs, approvals, and feedback.
-->

#### Role Summary
Stakeholders are individuals or groups with interest in project outcomes. They provide inputs, approvals, and feedback to shape project direction and success.

#### Responsibilities
- Provide business context and requirements input
- Review and approve key milestones and deliverables
- Participate in demos and feedback sessions
- Escalate concerns through appropriate channels

#### Goals
- Ensure project outcomes align with business objectives
- Stay informed on progress and risks
- Provide timely feedback and decisions

#### Typical Communication
- Monthly stakeholder updates
- Demo attendance and feedback
- Approval gates at key milestones

#### Interactions with Other Roles
- **Product Managers:** Provide input on priorities and validate outcomes
- **Project Managers:** Receive status updates and escalate concerns
- **Business Analysts:** Collaborate on requirements clarification

---

## Extended Roles

<!-- 
Rationale: Extended roles support specific aspects of delivery but may not be 
involved in every project. These personas were added per Issue #4 to provide 
complete coverage of team structures and improve cross-functional collaboration.
-->

### UX/UI Designers

#### Role Summary
UX/UI Designers drive user-centered design, create wireframes, prototypes, and visual assets for product features. They ensure the product is intuitive, accessible, and visually consistent.

#### Responsibilities
- Collaborate with Product Managers and Developers to shape feature scope
- Create wireframes, mockups, and interactive prototypes
- Conduct usability testing and incorporate feedback
- Ensure compliance with accessibility standards (a11y)
- Maintain design systems and style guides

#### Goals
- Deliver intuitive, accessible user experiences
- Ensure visual consistency across the product
- Reduce design-related rework through early validation

#### Typical Communication
- Design reviews with PMs and Developers
- Usability testing reports
- Design handoff documentation

#### Interactions with Other Roles
- **Product Managers:** Align on user needs and feature scope
- **Developers:** Provide design assets and specifications for implementation
- **QA/Testers:** Support UI/UX testing and validation
- **Business Analysts:** Understand user workflows and business context
- **Customer Support:** Receive feedback on usability issues

#### Rationale for Inclusion
UX/UI Designers bridge user needs and technical implementation. Including this role clarifies design ownership and ensures user experience is considered throughout development.

---

### Security Engineers

#### Role Summary
Security Engineers identify, assess, and address security risks during development and deployment. They ensure the product meets security and compliance requirements.

#### Responsibilities
- Review architecture and code for vulnerabilities
- Advise on secure coding practices and compliance requirements
- Configure and monitor security scanning tools
- Respond to security incidents and coordinate remediation
- Maintain security documentation and runbooks

#### Goals
- Minimize security vulnerabilities in production
- Ensure compliance with security policies and regulations
- Enable rapid response to security incidents

#### Typical Communication
- Security review findings and recommendations
- Incident response coordination
- Security training and awareness sessions

#### Interactions with Other Roles
- **Developers:** Review code and advise on secure implementation
- **DevOps Engineers:** Integrate security scanning into CI/CD; coordinate on infrastructure security
- **Project Managers:** Report security risks and remediation status
- **Product Managers:** Advise on security requirements for features
- **QA/Testers:** Collaborate on security testing

#### Rationale for Inclusion
Security is a cross-cutting concern that affects all projects. Defining this role ensures security considerations are explicit and that escalation paths for security issues are clear (see `octoacme-risks-and-communication.md`).

---

### DevOps / Release Engineers

#### Role Summary
DevOps/Release Engineers maintain CI/CD pipelines, support automated testing and deployments, and ensure system reliability. They bridge development and operations.

#### Responsibilities
- Set up and maintain build, test, and deployment infrastructure
- Collaborate with Developers to automate workflows
- Troubleshoot deployment issues and monitor system uptime
- Manage release schedules and deployment windows
- Document infrastructure and operational procedures

#### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment failures and downtime
- Improve observability and incident response

#### Typical Communication
- Deployment status and release coordination
- Infrastructure change notifications
- Incident response and postmortems

#### Interactions with Other Roles
- **Developers:** Support CI/CD integration and deployment automation
- **Project Managers:** Coordinate release schedules and communicate deployment status
- **QA/Testers:** Integrate automated tests into pipelines
- **Security Engineers:** Implement security scanning and infrastructure controls
- **Customer Support:** Communicate deployment schedules and known issues

#### Rationale for Inclusion
DevOps Engineers are critical to the release process documented in `octoacme-release-and-deployment.md`. Defining this role clarifies ownership of deployment infrastructure and coordination responsibilities.

---

### Customer Support

#### Role Summary
Customer Support serves as the interface with end users, triaging issues, relaying feedback, and supporting product adoption. They are the voice of the customer within the organization.

#### Responsibilities
- Serve as first point of contact for bug reports and questions
- Triage and escalate issues to appropriate teams
- Relay user feedback to Product and Project Managers
- Document support interactions and identify recurring themes
- Support user onboarding and product adoption

#### Goals
- Provide timely, helpful responses to users
- Ensure user issues are resolved efficiently
- Surface actionable feedback to improve the product

#### Typical Communication
- Support ticket updates and escalations
- Weekly feedback summaries to PdM
- Documentation of known issues and workarounds

#### Interactions with Other Roles
- **Product Managers:** Relay user feedback and prioritize fixes
- **Developers:** Escalate bugs and provide reproduction steps
- **QA/Testers:** Validate reported issues
- **DevOps Engineers:** Coordinate on deployment-related user impacts
- **Business Analysts:** Provide insights on user workflows and pain points

#### Rationale for Inclusion
Customer Support provides critical feedback loops that inform product decisions. Including this role ensures user feedback is systematically captured and routed to appropriate teams.

---

### Business Analysts

#### Role Summary
Business Analysts bridge business needs and technical solutions. They analyze data, document requirements, and ensure solutions align with business objectives.

#### Responsibilities
- Gather and document business requirements
- Map processes and identify improvement opportunities
- Support test case development and acceptance criteria
- Analyze data to inform decisions
- Communicate insights to stakeholders and PMs

#### Goals
- Ensure requirements are clear, complete, and aligned with business goals
- Identify opportunities for process improvement
- Bridge communication between business and technical teams

#### Typical Communication
- Requirements documents and process maps
- Analysis reports and recommendations
- Stakeholder workshops and interviews

#### Interactions with Other Roles
- **Product Managers:** Collaborate on requirements and success metrics
- **Developers:** Clarify requirements and acceptance criteria
- **Stakeholders:** Gather input and validate requirements
- **QA/Testers:** Support test case development
- **Customer Support:** Understand user workflows and pain points

#### Rationale for Inclusion
Business Analysts ensure requirements are well-defined before development begins, reducing rework and misalignment. This role supports the planning process documented in `octoacme-project-planning.md`.

---

## Role Interaction Matrix

<!-- 
Rationale: This matrix provides a quick reference for understanding which roles
interact most frequently and on what topics. It supports onboarding and helps
team members understand communication paths.
-->

| From / To | Developer | PdM | PM | QA | Stakeholder | UX/UI | Security | DevOps | Support | BA |
|-----------|-----------|-----|----|----|-------------|-------|----------|--------|---------|-----|
| **Developer** | Code review | Requirements | Progress | Bugs | - | Implementation | Vulnerabilities | CI/CD | - | Requirements |
| **PdM** | Requirements | - | Priorities | Criteria | Roadmap | UX scope | Security reqs | Releases | Feedback | Requirements |
| **PM** | Blockers | Status | - | Quality gates | Updates | Timeline | Risk | Releases | - | Planning |
| **QA** | Bugs | Criteria | Status | - | - | UI testing | Security tests | Test automation | Issue validation | Test cases |
| **Stakeholder** | - | Input | Escalation | - | - | Feedback | - | - | - | Requirements |
| **UX/UI** | Handoff | UX scope | Timeline | UI testing | Feedback | - | - | - | Usability | Workflows |
| **Security** | Code review | Security reqs | Risk | Security tests | - | - | - | Infra security | - | Compliance |
| **DevOps** | CI/CD | Releases | Releases | Test automation | - | - | Infra security | - | Deployment | - |
| **Support** | Bug reports | Feedback | - | Issue validation | - | Usability | - | Deployment | - | User insights |
| **BA** | Requirements | Requirements | Planning | Test cases | Requirements | Workflows | Compliance | - | User insights | - |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference this document when clarifying responsibilities or escalation paths.

---

## Related Documentation
- [Project Management Overview](octoacme-project-management-overview.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment Guide](octoacme-release-and-deployment.md)
- [Onboarding Checklist](templates/onboarding-checklist.md)
- [Risk Escalation Template](templates/risk-escalation-template.md)

---

## Change History

| Date | Change | Reference |
|------|--------|-----------|
| Initial | Core roles (Developer, PdM, PM) | - |
| 2024 | Added QA/Testers, Stakeholders, UX/UI Designers, Security Engineers, DevOps/Release Engineers, Customer Support, Business Analysts; added interaction matrix | [Issue #4](https://github.com/GijsL/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) |

