# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — Project Manager shows progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone — Product Manager and stakeholders review deliverables
- Retrospectives — Scrum Master facilitates team reflection and continuous improvement

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (written by Developers)
- Integration tests where applicable (coordinated by QA Lead)
- End-to-end smoke tests for critical flows before release (QA Lead approves)
- Security scanning in CI (configured by DevOps Engineer)
- Manual QA for feature acceptance when needed (performed by QA team)
- Usability testing for user-facing features (coordinated by UX Designer)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup (Scrum Master facilitates)
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Regular demos scheduled (Product Manager and Scrum Master)
- [ ] Risk register updated weekly (Project Manager)
- [ ] Quality gates and sign-offs defined (QA Lead)
- [ ] Documentation updates tracked (Technical Writer)
- [ ] UX validation checkpoints scheduled (UX Designer, if applicable)
