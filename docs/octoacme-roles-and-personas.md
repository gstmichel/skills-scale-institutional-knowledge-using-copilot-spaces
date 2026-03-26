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

## UX/UI Designer

### Role Summary
UX/UI Designers design and validate user flows, wireframes, and mockups to ensure that product features are usable, accessible, and aligned with both user needs and product goals.

### Responsibilities
- Create user journey maps, wireframes, and high-fidelity UI mockups
- Lead accessibility and design system reviews
- Hand off design specifications to Developers and provide implementation guidance
- Participate in sprint planning to provide input on design complexity and feasibility
- Conduct usability testing and incorporate feedback into iterative design improvements

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce friction in feature implementation by providing clear design artifacts
- Ensure product interfaces align with user research and acceptance criteria

### Typical Communication
- Design review sessions and sprint planning meetings
- Handoff documentation via design tools (e.g., Figma, Sketch)
- Async feedback on prototypes and implementation reviews

### Interaction Points
- **Product Managers**: Collaborates to align designs with product requirements, user research, and prioritization decisions
- **Developers**: Provides design handoffs, clarifies implementation questions, and reviews final UI output
- **QA Engineers**: Ensures usability and accessibility criteria are captured in test plans
- **Project Managers**: Aligns on design deliverable timelines and flags scope risks

---

## Technical Writer

### Role Summary
Technical Writers create, maintain, and improve process, feature, and end-user documentation to ensure all team members and stakeholders have accurate, accessible, and up-to-date information.

### Responsibilities
- Author and maintain internal process documents, API references, and user guides
- Review and edit documentation contributed by Developers and other team members
- Collaborate with all roles to verify documentation accuracy and completeness
- Establish and enforce documentation standards and templates
- Manage documentation versioning alongside product releases

### Goals
- Ensure every feature and process is clearly and accurately documented
- Reduce time-to-productivity for new team members through thorough onboarding docs
- Support external users and stakeholders with clear, discoverable documentation

### Typical Communication
- Regular syncs with Developers and Product Managers during feature development
- Documentation reviews as part of the definition of done
- Async comments and pull requests on documentation changes

### Interaction Points
- **Developers**: Gathers technical details, reviews code comments, and validates feature documentation accuracy
- **Product Managers**: Aligns documentation with feature specs, release notes, and user-facing messaging
- **Project Managers**: Coordinates documentation milestones with release schedules
- **QA Engineers**: Reviews test plans and bug reports to ensure documentation reflects current behavior
- **UX/UI Designers**: Incorporates UI copy and user flow descriptions into user guides

---

## DevOps Engineer

### Role Summary
DevOps Engineers own CI/CD pipelines, infrastructure automation, system monitoring, and release processes. They bridge development and operations to ensure reliable, repeatable, and fast software delivery.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and release workflows
- Automate infrastructure provisioning and configuration management
- Monitor system health, performance, and availability; respond to incidents
- Manage environments (development, staging, production) and promote deployments
- Enforce security and compliance requirements in infrastructure and deployment practices

### Goals
- Reduce deployment lead times and increase release frequency
- Maximize system reliability and minimize incident recovery time
- Automate repetitive operational tasks to free up engineering capacity

### Typical Communication
- Release coordination meetings and runbooks
- Incident post-mortems and on-call rotation documentation
- Infrastructure-as-code pull requests and environment status updates

### Interaction Points
- **Developers**: Collaborates on build configurations, deployment requirements, and environment troubleshooting
- **QA Engineers**: Coordinates environment provisioning and pipeline integrations for automated testing
- **Security Lead**: Implements security controls and scanning into pipelines; supports incident response
- **Project Managers**: Communicates deployment schedules, risks, and infrastructure dependencies

---

## QA Engineer

### Role Summary
QA Engineers plan and execute testing strategies—both manual and automated—to ensure product quality, validate acceptance criteria, and support release readiness decisions.

### Responsibilities
- Develop and maintain test plans, test cases, and automated test suites
- Execute exploratory and regression testing across features and releases
- Track, document, and verify defects in collaboration with Developers
- Collaborate with Product Managers to define and validate acceptance criteria
- Assess release readiness and communicate quality risks to the team

### Goals
- Prevent defects from reaching production through thorough and timely testing
- Increase test automation coverage to accelerate release cycles
- Provide clear quality signals that support confident release decisions

### Typical Communication
- Sprint planning and backlog refinement to review acceptance criteria
- Bug reports, test summary reports, and release readiness sign-offs
- Coordination with Developers during defect triage and fix verification

### Interaction Points
- **Developers**: Works with developers on defect reproduction, fix validation, and test automation integration
- **Product Managers**: Clarifies acceptance criteria and validates that features meet user expectations
- **DevOps Engineers**: Coordinates automated test execution within CI/CD pipelines and environment setup
- **Project Managers**: Reports on quality metrics, outstanding defects, and release readiness status
- **UX/UI Designers**: Validates that implemented UIs conform to design specifications and accessibility standards

---

## Data Analyst

### Role Summary
Data Analysts provide analytics, reporting, and decision-support metrics that enable Product and Project Managers to make evidence-based decisions, measure impact, and communicate progress to stakeholders.

### Responsibilities
- Define, collect, and analyze key performance indicators and project metrics
- Build and maintain dashboards and reports for product and project tracking
- Support A/B testing, feature adoption analysis, and post-release impact assessments
- Surface data insights to inform roadmap prioritization and process improvements
- Ensure data quality, integrity, and governance in all reporting outputs

### Goals
- Make project and product performance measurable and transparent
- Enable data-driven prioritization and planning decisions
- Demonstrate business value and impact of delivered features and process changes

### Typical Communication
- Regular reporting cadences with Product and Project Managers
- Ad-hoc analysis requests and data deep-dives
- Dashboard documentation and data dictionary maintenance

### Interaction Points
- **Product Managers**: Partners to define success metrics, interprets usage data, and supports roadmap prioritization
- **Project Managers**: Provides project health metrics, velocity trends, and milestone tracking data
- **Developers**: Collaborates on instrumentation, event tracking implementation, and data pipeline requirements
- **Customer Support/Success Representatives**: Analyzes support trends and customer feedback data to surface actionable insights

---

## Customer Support/Success Representative

### Role Summary
Customer Support/Success Representatives act as the voice of the customer within the project team, translating support interactions and customer feedback into actionable process improvements and roadmap inputs.

### Responsibilities
- Triage and resolve customer-reported issues, escalating to engineering as needed
- Document and aggregate customer feedback, feature requests, and pain points
- Collaborate with Product Managers to ensure customer needs are represented in planning
- Create and maintain customer-facing help content and FAQs
- Monitor customer satisfaction metrics and communicate trends to the team

### Goals
- Deliver a positive customer experience through timely and effective issue resolution
- Close the feedback loop between customers and the product/engineering team
- Reduce support volume through proactive communication and improved documentation

### Typical Communication
- Regular syncs with Product Managers to review support trends and escalations
- Defect reports and feature requests submitted to the project backlog
- Customer communications, status updates, and release announcement reviews

### Interaction Points
- **Product Managers**: Provides customer feedback and support trends to inform prioritization and feature decisions
- **Developers**: Escalates technical issues with reproduction steps and customer impact context
- **Technical Writers**: Collaborates on help documentation, FAQs, and release communications
- **Data Analysts**: Shares support ticket data and customer satisfaction scores for broader analysis
- **Project Managers**: Flags customer-impacting risks and coordinates communication around releases

---

## Security Lead

### Role Summary
The Security Lead advises on security best practices, reviews code and release plans for risk, and facilitates incident response. They ensure that security is embedded throughout the software development lifecycle.

### Responsibilities
- Define and communicate security standards, policies, and best practices for the team
- Conduct security reviews of architecture, code changes, and release plans
- Identify, track, and prioritize security vulnerabilities and risk items
- Lead or support incident response activities during security events
- Provide security training and awareness resources to team members

### Goals
- Minimize security risk exposure across all product and infrastructure changes
- Embed security practices early in the development lifecycle (shift-left)
- Ensure compliance with relevant security frameworks and organizational policies

### Typical Communication
- Security review checkpoints during sprint and release planning
- Vulnerability and risk reports shared with engineering and project leadership
- Incident response runbooks and post-mortems

### Interaction Points
- **Developers**: Reviews code for vulnerabilities, advises on secure coding patterns, and validates remediations
- **DevOps Engineers**: Collaborates on secure pipeline configurations, secrets management, and compliance controls
- **Product Managers**: Assesses security implications of proposed features and roadmap items
- **Project Managers**: Communicates security risks, remediation timelines, and compliance requirements
- **QA Engineers**: Integrates security testing (SAST, DAST) into quality assurance processes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

