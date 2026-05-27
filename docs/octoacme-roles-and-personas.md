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
- Support QA Lead and Release Manager during testing and deployment phases

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Collaboration with QA Lead on test strategies

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Work with Designer/UX to ensure user-centric solutions
- Partner with Support Advocate to understand customer impact areas

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Design reviews and user feedback sessions

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
- Escalate blockers and align release activities with Release Manager
- Ensure all roles have clear handoffs and visibility

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Release coordination meetings

---

## Release Manager

### Role Summary
Release Managers oversee all release activities, ensuring smooth and predictable deployments to production. They coordinate scheduling, communications, rollback plans, and post-release verification.

### Responsibilities
- Develop and maintain release and deployment plans
- Coordinate pre-release activities (testing sign-off, release notes, documentation)
- Schedule and communicate deployment windows to stakeholders
- Execute or oversee deployment to staging and production environments
- Manage rollback procedures and incident response during releases
- Verify post-deployment health and smoke tests
- Communicate release status and outcomes to stakeholders and support

### Interactions
- Works closely with **Developers** on deployment readiness and technical validation
- Collaborates with **QA Lead** to ensure testing sign-off before deployment
- Coordinates with **Project Managers** on timeline and stakeholder communication
- Aligns with **Technical Writers** on release notes and documentation
- Briefs **Support Advocate** on new features and known issues pre-launch

### Goals
- Minimize deployment risk and downtime
- Enable predictable, frequent releases
- Ensure stakeholder confidence in release quality

### Typical Communication
- Pre-release readiness meetings
- Deployment window announcements
- Post-release retrospectives and incident reports

---

## QA Lead

### Role Summary
QA Leads own the test strategy and quality sign-off for releases. They manage manual and automated testing, define acceptance criteria validation, and ensure release readiness.

### Responsibilities
- Define test strategy and acceptance criteria for features
- Create and maintain automated test suites
- Execute manual testing for complex or user-facing scenarios
- Validate that all acceptance criteria are met before sign-off
- Coordinate with Developers on test coverage and defect resolution
- Document known issues and limitations before release
- Participate in release readiness reviews with Release Manager

### Interactions
- Partners with **Developers** on test design and code review
- Collaborates with **Product Managers** to clarify acceptance criteria
- Works with **Release Manager** on quality sign-off and deployment readiness
- Supports **Designer/UX** in validating accessibility and usability standards
- Alerts **Support Advocate** to edge cases and known limitations

### Goals
- Ensure high product quality and reliability
- Reduce post-release defects and support burden
- Enable faster release cycles with confidence

### Typical Communication
- Test plans and defect reports
- Quality metrics and test coverage dashboards
- Release readiness and sign-off meetings

---

## Designer / UX

### Role Summary
Designers and UX specialists ensure solutions meet usability and accessibility standards. They collaborate early with Product Managers and Developers and participate actively in review cycles.

### Responsibilities
- Conduct user research and define user needs
- Create wireframes, prototypes, and design specifications
- Ensure accessibility (WCAG compliance) and usability standards
- Participate in design reviews and iterate based on feedback
- Collaborate with Developers on implementation details and constraints
- Validate final designs against acceptance criteria before QA handoff
- Document design decisions and design systems

### Interactions
- Partners with **Product Managers** on user research and requirements
- Works closely with **Developers** on feasibility and technical constraints
- Collaborates with **QA Lead** to validate accessibility and usability in testing
- Supports **Technical Writers** with UI documentation and user-facing copy
- Informs **Support Advocate** on likely user confusion points

### Goals
- Deliver user-centric, accessible solutions
- Reduce post-launch usability issues and support tickets
- Maintain design consistency and quality

### Typical Communication
- Design specs and wireframes in design tools (Figma, Adobe XD, etc.)
- Design review meetings
- Accessibility audit reports

---

## Technical Writer

### Role Summary
Technical Writers document key artifacts and ensure process, user-facing, and system documentation stays current with releases. They work with all roles and signal documentation gaps.

### Responsibilities
- Document technical architecture and implementation details
- Create and maintain user-facing documentation and help content
- Ensure process documentation aligns with current practices
- Participate in design and planning to capture requirements early
- Review release notes and communicate product changes to users
- Audit documentation for gaps and maintain a documentation backlog
- Support onboarding and training materials

### Interactions
- Works with **Developers** on technical documentation and API specs
- Partners with **Product Managers** on feature announcements and documentation strategy
- Collaborates with **Designer/UX** on UI labels and user experience copy
- Supports **Release Manager** in preparing release notes and deployment guides
- Alerts **Support Advocate** to documentation updates that affect support processes
- Coordinates with **QA Lead** on test documentation and edge case communication

### Goals
- Keep documentation accurate, clear, and accessible
- Reduce support burden by providing clear user guidance
- Enable fast onboarding and knowledge sharing

### Typical Communication
- Documentation drafts and updates
- Documentation audits and gap analyses
- Content reviews and feedback

---

## Support Advocate

### Role Summary
Support Advocates represent the support team's perspective throughout the project lifecycle. They highlight likely customer impact areas, ensure readiness for escalations post-release, and advocate for supportability.

### Responsibilities
- Identify likely support impact and escalation points during planning
- Ensure support team readiness for new features (runbooks, FAQs, training)
- Provide feedback on feature clarity and usability from a support perspective
- Review release notes and documentation for completeness and clarity
- Participate in release preparation to identify edge cases and known issues
- Coordinate support communication strategy with **Release Manager**
- Gather support team feedback and signal product improvement opportunities

### Interactions
- Partners with **Product Managers** to identify customer-impacting changes
- Works with **Developers** to understand technical limitations and workarounds
- Collaborates with **QA Lead** on edge cases and known limitations
- Reviews **Technical Writer** documentation for support completeness
- Coordinates release communication and support readiness with **Release Manager**
- Informs **Designer/UX** of common user confusion points

### Goals
- Minimize support escalations and customer frustration
- Enable support team to deliver excellent customer experience
- Provide early warning of customer-impacting issues

### Typical Communication
- Support impact assessments
- Escalation runbooks and FAQ documents
- Release readiness and support preparation meetings

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning work or creating checklists, refer to persona responsibilities to clarify ownership and handoffs.
- During retrospectives, identify gaps where personas were unclear or handoffs failed, then use this document to improve future iterations.
