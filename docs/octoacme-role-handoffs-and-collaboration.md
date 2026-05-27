# OctoAcme — Role Handoffs & Collaboration Guide

## Purpose
Provide practical guidance on how personas interact across the project lifecycle, clarify handoff points, and prevent gaps in ownership and communication.

## Core Handoff Points

### Initiation → Planning
- **From:** Product Manager, Project Manager, Stakeholders
- **To:** Full delivery team (Developers, Designer/UX, QA Lead, Technical Writer)
- **Handoff:** Project One-pager, success metrics, high-level requirements
- **Key Actions:**
  - Product Manager presents vision and success metrics
  - Project Manager confirms timeline and resource availability
  - Designer/UX identifies user research and accessibility requirements
  - Technical Writer flags documentation needs
  - Support Advocate highlights support readiness gaps

### Planning → Design & Development
- **From:** Product Manager, Project Manager
- **To:** Designer/UX, Developers
- **Handoff:** Acceptance criteria, user stories, design specifications
- **Key Actions:**
  - Designer/UX creates wireframes and design specs aligned with accessibility standards
  - Developers review feasibility and propose technical approach
  - QA Lead drafts test strategy and acceptance criteria checklist
  - Technical Writer begins identifying documentation requirements

### Development → Testing
- **From:** Developers
- **To:** QA Lead
- **Handoff:** Code changes, test coverage, feature documentation
- **Key Actions:**
  - Developers mark PR as "ready for QA" when all acceptance criteria met
  - QA Lead executes test plan and identifies defects
  - QA Lead works with Developers to resolve quality issues
  - Designer/UX validates accessibility and usability in QA environment

### Testing → Release
- **From:** QA Lead, Product Manager
- **To:** Release Manager
- **Handoff:** Quality sign-off, release notes, deployment plan
- **Key Actions:**
  - QA Lead provides formal quality sign-off and known issues list
  - Technical Writer finalizes release notes and user-facing documentation
  - Release Manager prepares deployment plan and rollback procedures
  - Support Advocate prepares support runbooks and escalation guides

### Release → Support & Feedback
- **From:** Release Manager
- **To:** Support Advocate, Product Manager
- **Handoff:** Release announcement, known issues, customer impact areas
- **Key Actions:**
  - Release Manager communicates deployment status to support and stakeholders
  - Support Advocate monitors escalations and customer feedback post-launch
  - Product Manager tracks success metrics against initial goals
  - Technical Writer updates documentation based on customer feedback

---

## Collaboration Patterns

### Daily Standup Responsibilities
- **Developers:** Code progress, blockers, estimated completion
- **Designer/UX:** Design review progress, usability concerns, accessibility validations
- **QA Lead:** Testing progress, defect summary, blockers to quality sign-off
- **Technical Writer:** Documentation drafts, gaps identified, review status
- **Support Advocate:** Escalation preview, likely impact areas, readiness concerns
- **Project Manager:** Risk updates, dependency status, schedule confidence
- **Release Manager:** (if in release phase) Deployment readiness, pre-release activity status

### Weekly Sync (PM + PdM + Key Contributors)
- **Agenda:** Progress against milestones, risks, cross-team dependencies
- **Participants:** Project Manager, Product Manager, Developers (lead), QA Lead, Designer/UX lead
- **Outcomes:** Updated risk register, confirmed next milestone plan, escalations identified

### Design Review Cadence
- **Participants:** Designer/UX, Product Manager, Developers, QA Lead, Accessibility champion (if separate)
- **Frequency:** Weekly or as design progresses
- **Goals:** Validate design feasibility, accessibility compliance, alignment with acceptance criteria
- **Outcomes:** Approved designs, technical constraints documented, QA approach agreed

### Quality Sign-Off Gate
- **Conducted by:** QA Lead, with Product Manager approval
- **Required conditions:**
  - All acceptance criteria met and tested
  - Accessibility standards validated (WCAG compliance)
  - Automated tests passing
  - Known issues documented
  - Release notes prepared
- **Output:** Quality sign-off memo or checklist, cleared for release planning

### Release Readiness Review
- **Participants:** Release Manager, QA Lead, Developers (tech lead), Technical Writer, Support Advocate
- **Frequency:** 1–2 days before planned deployment
- **Checklist:**
  - Deployment procedure documented and tested
  - Rollback plan in place
  - Release notes finalized
  - Support runbooks prepared
  - Communication plan confirmed
  - Smoke test procedures ready
- **Output:** Go/no-go decision, deployment scheduled

---

## Escalation & Blocker Resolution

### Level 1: Team Triage (Daily Standup)
- **Blocker identified by:** Any team member
- **Resolution approach:** Team discussion, propose workaround or parallel path
- **Owner:** Project Manager or affected lead
- **Timeline:** Same day if possible

### Level 2: Cross-Team Coordination (Weekly Sync)
- **Escalation by:** Project Manager or team lead
- **Participants:** Product Manager, dependent team leads, possibly Sponsor
- **Resolution:** Negotiate scope, schedule, or resource adjustments
- **Owner:** Project Manager + Product Manager
- **Timeline:** Within 48 hours

### Level 3: Sponsor / Steering Committee
- **Escalation by:** Product Manager or Sponsor (if informed)
- **Participants:** Sponsor, Product Lead, key stakeholders
- **Resolution:** Business-level trade-offs, resource reallocation, scope reduction
- **Owner:** Sponsor or executive stakeholder
- **Timeline:** Within 1 week

### Common Blocker Types & Owners

| Blocker Type | Primary Owner | Secondary Stakeholders |
|---|---|---|
| Design feasibility | Developers | Designer/UX |
| QA sign-off hold | QA Lead | Developers, Product Manager |
| Resource unavailable | Project Manager | Sponsor, affected team lead |
| Dependency on another team | Project Manager | Dependent team PM |
| Test environment issue | QA Lead / Ops | Developers |
| Documentation gap | Technical Writer | QA Lead, Support Advocate |
| Support readiness risk | Support Advocate | Release Manager, Product Manager |

---

## Ownership & Accountability Matrix

Use this matrix to clarify who is responsible, accountable, consulted, and informed for key activities:

| Activity | Responsible | Accountable | Consulted | Informed |
|---|---|---|---|---|
| Define acceptance criteria | Product Manager | Product Manager | Developers, QA Lead | Designer/UX, Tech Writer |
| Design solution | Designer/UX | Designer/UX | Developers, Product Mgr | QA Lead, Tech Writer |
| Implement feature | Developers | Developers | Designer/UX, QA Lead | Product Mgr, Tech Writer |
| Test & validate | QA Lead | QA Lead | Developers, Product Mgr | Support Advocate, Tech Writer |
| Document (user-facing) | Technical Writer | Technical Writer | Designer/UX, QA Lead | Developers, Support Advocate |
| Prepare release | Release Manager | Release Manager | QA Lead, Tech Writer | Developers, Product Mgr, Support Adv |
| Deploy to production | Release Manager | Release Manager | Developers, QA Lead | Product Mgr, Support Adv, Stakeholders |
| Assess post-launch | Product Manager | Product Manager | Support Advocate, QA Lead | Developers, Release Mgr, Tech Writer |

**Legend:**
- **Responsible:** Does the work
- **Accountable:** Final authority / sign-off
- **Consulted:** Provides input before decision
- **Informed:** Kept in the loop but doesn't participate directly

---

## Communication Checklist for Key Milestones

### Feature Ready for QA
- [ ] Developers confirm code complete and merged
- [ ] All acceptance criteria documented in PR and issue
- [ ] Automated tests passing
- [ ] Designer/UX confirms visual/UX sign-off
- [ ] QA Lead receives detailed handoff and test environment ready
- [ ] Technical Writer notified for documentation planning

### Ready for Release
- [ ] QA Lead provides formal quality sign-off
- [ ] All known issues documented and prioritized
- [ ] Release notes drafted by Technical Writer
- [ ] Support Advocate confirms readiness (runbooks, FAQs, training)
- [ ] Release Manager confirms deployment plan and rollback ready
- [ ] Stakeholders informed of release date and scope

### Post-Launch (24–48 hours)
- [ ] Release Manager confirms stable deployment
- [ ] Support Advocate confirms no major escalations
- [ ] Product Manager begins tracking success metrics
- [ ] Technical Writer addresses urgent documentation updates
- [ ] Team notes lessons learned for retrospective

---

## References
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md)
