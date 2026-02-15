# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- **Identify**: during planning and ongoing execution (all team members, coordinated by Project Manager)
- **Assess**: estimate impact and likelihood (Project Manager with input from technical leads)
- **Mitigate**: reduced via actions, contingency plans (owned by specific roles based on risk type)
- **Monitor**: review at weekly syncs and update status (Project Manager tracks, Scrum Master surfaces blockers)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based) - coordinated by Project Manager
- Use a single source of truth (project README or release doc) for status
- Technical Writer maintains documentation and release communications
- Product Manager owns stakeholder messaging on product direction

See [Collaboration & Hand-off Guide](octoacme-collaboration-handoff-template.md) for stakeholder collaboration patterns.

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- **Level 1**: Team-level (Scrum Master facilitates resolution)
- **Level 2**: PM escalates to Product Lead and cross-functional leads (QA Lead, DevOps Engineer, etc.)
- **Level 3**: Product Lead escalates to Sponsor for business-critical issues
- For security incidents, follow the security incident runbook and notify Security on-call (DevOps Engineer coordinates)

See [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) for detailed escalation responsibilities by role.
