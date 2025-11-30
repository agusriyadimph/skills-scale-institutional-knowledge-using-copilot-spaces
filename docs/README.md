# OctoAcme Project Management Docs

Welcome! This README is the central entry point for OctoAcme's project management processes and links to the full set of process documents in this repository. Use this page to quickly orient yourself to how we plan, execute, and learn from cross-functional work.

Overview of key processes
OctoAcme runs projects using an iterative, outcome-driven approach that emphasizes small, shippable increments and clear ownership. Projects start with a lightweight initiation (a one‑pager that defines the problem, success metrics, stakeholders, and a go/no‑go decision), then move into planning where work is broken into a prioritized backlog with acceptance criteria and a release plan. Execution is tracked through a standard board flow and routine team rhythm; releases follow a checklist and include rollback and incident playbooks. Each project ends with a close and retrospective to capture learnings and convert them into tracked improvements.

Workflows and roles
Workflows center on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a pull request-based delivery cycle: small PRs, linked issues with acceptance criteria, CI gating (tests, linting, security), and formal review before merge. Roles are explicit: Product Managers (PdMs) define outcomes and prioritize the backlog; Project Managers (PMs) coordinate schedules, risks, and stakeholder communication; Developers implement code and tests; QA validates acceptance criteria and quality; Stakeholders provide input and approvals. Named ownership reduces single-person dependencies and speeds decisions.

Communication and risk
Communication is structured and frequent: daily standups for blockers, regular delivery/demo sessions, weekly PM–PdM syncs, and milestone or monthly stakeholder updates. Risk management is operationalized with a Risk Register (impact, likelihood, owner, mitigation) reviewed regularly and a clear escalation path from team triage to sponsor involvement for business-critical issues. Incident communications are blameless and follow an incident playbook.

Quality assurance and continuous improvement
Quality work is enforced through automated unit/integration tests, CI security scans, and targeted end-to-end smoke tests for critical flows; manual QA is used when acceptance requires human validation. Releases use a pre-release checklist (smoke tests, release notes, rollback plan) and post-release verifications. Retrospectives after sprints, releases, or incidents capture what went well, what to improve, and create prioritized action items tracked in the backlog to ensure continuous improvement.

Process documents in this folder
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to use these docs
- Keep the project one-pager and README updated in each project repo as the single source of truth.
- Add action items from retros to the backlog as tracked issues.
- For Copilot Spaces: put any process-specific, team-only context in .copilot/ so Copilot can use it while helping the team.

Acceptance criteria
- Content aligns with the existing process docs in docs/
- The README gives a short, actionable overview and links to each process doc
- README helps new team members discover the detailed docs and understand our core rhythms