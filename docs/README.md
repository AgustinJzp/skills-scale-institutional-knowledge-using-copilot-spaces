# OctoAcme Project Management Docs

This README acts as a central entry point for all OctoAcme project management process documents. Use these resources to understand how projects are run, managed, and improved within the OctoAcme organization.

## Process Overview

OctoAcme projects follow a clear, iterative, and collaborative process that emphasizes customer value, data-informed decisions, and psychological safety. The framework is structured around five key phases, each with explicit decision gates and deliverables:

- **Initiation:** Define the problem, success metrics, stakeholders, and alignment for new projects ([Initiation Guide](octoacme-project-initiation.md)).
- **Planning:** Break work into milestones, define acceptance criteria, prioritize the backlog, and address dependencies ([Project Planning](octoacme-project-planning.md)).
- **Execution and Tracking:** Use project boards, PR workflows, and metrics to track delivery with regular standups and demos ([Execution & Tracking](octoacme-execution-and-tracking.md)).
- **Risk and Communication:** Maintain a risk register, communicate status, and escalate blockers when needed ([Risk Management & Communication](octoacme-risks-and-communication.md)).
- **Release & Deployment:** Standard checks for pre-release, deployment, and rollback ([Release & Deployment Guide](octoacme-release-and-deployment.md)).
- **Retrospective & Improvement:** Structured after-action reviews to capture learnings and drive continuous improvement ([Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)).

## Core Principles

OctoAcme project management is built on three foundational principles:

1. **Customer-First:** Prioritize customer value and usability in all decisions.
2. **Iterative Delivery:** Deliver small, testable increments with regular feedback loops.
3. **Clear Ownership:** Each project has a named Project Manager (PM) and Product Manager (PdM) with explicit responsibilities.

## Key Roles & Responsibilities

OctoAcme projects involve multiple personas, each with distinct responsibilities:

- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications. Ensures projects move through milestones on time and within scope.
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, and measures success. Owns the product vision and stakeholder alignment.
- **Developers:** Implement features and fixes to meet acceptance criteria. Write and maintain tests, participate in code reviews, and identify technical risks.
- **QA/Testing:** Validate quality, test acceptance criteria, and ensure end-to-end smoke tests pass before release.
- **Stakeholders:** Provide inputs, approvals, and guidance throughout the project lifecycle.

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed descriptions of each role.

## Execution Highlights

### Communication Cadence
- **Daily Standups** (15 min): Focus on progress, blockers, and dependencies.
- **Weekly PM/PdM Sync:** Alignment on delivery status, backlog, risks, and decisions.
- **Twice-Weekly Team Standups:** For delivery teams (or as agreed).
- **Monthly Stakeholder Updates:** High-level progress and business impact.
- **Ad-hoc Escalations:** As needed for business-impacting issues.

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Tracking & Metrics
- Use GitHub Projects (or similar) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Track velocity and burndown to monitor progress
- Monitor success metrics defined in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

### Risk Management
- **Level 1:** Team-level triage in daily standups
- **Level 2:** PM escalates to Product Lead and dependent teams
- **Level 3:** Sponsor-level escalation for business-impacting issues
- Maintain a Risk Register with ID, description, impact, likelihood, owner, mitigation, and status

### Continuous Improvement
- Retrospectives after each sprint, release, or important milestone
- Capture learnings: what went well, what could improve, and 2–3 prioritized action items
- Action items tracked in the backlog with clear owners and due dates
- Measure impact of improvements and iterate

## Core Documents

| Document | Purpose |
|----------|----------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate, authorize, and align on new projects |
| [Project Planning](octoacme-project-planning.md) | Turn approved initiatives into actionable plans and backlogs |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Guidance for day-to-day execution and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize how features are released to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive iterative improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed role descriptions and responsibilities |

## Getting Started

**New to OctoAcme projects?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.

**Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate the idea and get stakeholder alignment.

**Planning a project?** Use the [Project Planning](octoacme-project-planning.md) document to structure your backlog and timeline.

**Executing a project?** Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) for workflow guidance, and [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation and stakeholder updates.

**Deploying to production?** Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release checks and rollback procedures.

**Wrapping up?** Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings.

## Contributing to Process Docs

To suggest updates or add new content to OctoAcme process documents, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

## Questions?

If you have questions about OctoAcme project management processes, refer to the relevant document above or reach out to your Project Manager or Product Manager.
