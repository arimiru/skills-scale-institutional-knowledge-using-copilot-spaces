# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management process library. This README is the central entry point for the project management docs and provides a concise overview of how we initiate, plan, deliver, and improve work across OctoAcme. It connects the lifecycle phases to the detailed process documents in this folder and includes quick-start guidance for new team members.

Overview
OctoAcme runs projects with a lightweight, disciplined delivery process that moves validated ideas into repeatable execution. Initiatives begin with a short Project One-pager to capture the problem, objective, success metrics, stakeholders, and a high-level timeline. After the initiation gate, teams create a prioritized backlog, run planning sessions to size and scope work, and map releases to milestones. Work flows through a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) and follows a pull request workflow requiring small, reviewable PRs, CI passing, and an approval before merging.

Roles and responsibility are explicit: Product Managers define outcomes, prioritize the backlog, and validate success metrics; Project Managers coordinate schedules, risks, and communications; Developers implement features, tests, and docs; QA validates acceptance criteria; stakeholders provide approvals and inputs. The docs emphasize clear ownership for action items (e.g., risk owners, action-item owners from retrospectives) and encourage small, reviewable pull requests (goal ≤400 lines) with issue links and acceptance criteria in the PR description. The PR policy also requires CI (tests + linting) to pass before review and at least one approval before merging, reinforcing code quality and review discipline.

Communication and cadence are built into the rhythm: daily standups for progress and blockers, weekly delivery syncs to surface progress and risks, weekly PM+PdM alignment, and monthly stakeholder updates. Demos or reviews happen at the end of each sprint or milestone, and standard templates (weekly status, incident comms) plus a single source of truth (project README or release doc) are used to keep stakeholders aligned. Escalation paths are defined (team → PM → Product Lead → Sponsor) and incident communication follows a triage → action → retrospective flow.

Quality assurance is layered and treated as part of the pipeline: unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. CI includes security scanning and automated checks, and manual QA is used for acceptance when required. Releases follow a checklist (staging smoke tests, backups if applicable, post-deploy verifications) with rollback/mitigation plans and a clear release-notes template. Continuous improvement is enforced through retrospectives that produce prioritized action items tracked back into the backlog, closing the loop between learning and process change.

Quick start for new team members
- Start here: OctoAcme Project Management Overview (octoacme-project-management-overview.md)
- Read the Initiation guide to learn how to propose a project (octoacme-project-initiation.md)
- Read Planning to understand backlog, estimation, and release mapping (octoacme-project-planning.md)
- See Execution & Tracking for daily cadence and PR/CI expectations (octoacme-execution-and-tracking.md)
- Read Release & Deployment for release checklists and rollback procedures (octoacme-release-and-deployment.md)
- Read Retrospective & Continuous Improvement to see how we capture and act on learnings (octoacme-retrospective-and-continuous-improvement.md)
- Read Risk Management & Communication for the Risk Register and stakeholder templates (octoacme-risks-and-communication.md)
- Role definitions: OctoAcme Personas (octoacme-roles-and-personas.md)

Project lifecycle (linked docs)
1. Initiation
   - Document: octoacme-project-initiation.md
   - Purpose: validate business need, align stakeholders, and create a lightweight plan
2. Planning
   - Document: octoacme-project-planning.md
   - Purpose: break work into shippable increments, identify dependencies and risks
3. Execution & Tracking
   - Document: octoacme-execution-and-tracking.md
   - Purpose: manage day-to-day execution, cadence, and PR/CI workflows
4. Release & Deployment
   - Document: octoacme-release-and-deployment.md
   - Purpose: standardize releases, run pre/post-deploy checks, and manage rollbacks
5. Retrospective & Continuous Improvement
   - Document: octoacme-retrospective-and-continuous-improvement.md
   - Purpose: capture learnings, track action items, and close the improvement loop

Roles & responsibilities (quick reference)
- Product Manager: Defines problem, goals, success metrics, and prioritizes backlog.
- Project Manager: Coordinates delivery, manages risks/dependencies, and facilitates cadence.
- Developers: Implement features, write tests, and participate in reviews.
- QA: Validate acceptance criteria, run tests, and sign off on releases.
- Stakeholders: Provide input and approvals, receive regular status updates.

Key artifacts
- Project One-pager / Charter
- Roadmap and Release Plan
- Sprint / Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

Getting started checklist for a new project
- Complete Project One-pager and get Product Lead review
- Create repo or project board skeleton and add initial docs
- Populate backlog and prioritize first sprint
- Ensure CI and branch/PR conventions are documented in the repo

Contributing & updates
If you want to propose changes to these process docs, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ and reference the relevant document(s). Proposed edits should align with our principles and include acceptance criteria where relevant.
