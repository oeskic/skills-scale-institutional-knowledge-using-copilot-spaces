# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

### Leadership & Coordination
- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications.
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success.
- **Sponsor / Executive Stakeholder**: Provides strategic alignment, removes blockers, and approves major decisions.

### Delivery & Implementation
- **Developers**: Implement features, collaborate on design and testability.
- **Technical Lead / Solutions Architect**: Provides technical direction, design guidance, and quality oversight.
- **QA/Quality Assurance Engineer**: Validates quality and acceptance criteria; manages testing strategy.

### Process & Support
- **Scrum Master / Agile Coach**: Facilitates ceremonies, removes impediments, and coaches on agile practices.
- **Business Analyst**: Bridges stakeholder needs and technical implementation; clarifies requirements.
- **Security / DevSecOps Engineer**: Ensures security compliance, conducts threat modeling, leads incident response.

**📖 For detailed role descriptions, see [Roles & Personas](./octoacme-roles-and-personas.md)**

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register & Dependency Map
- Retrospective notes and action items
- Team Communication Plan
- Security & Compliance Checklist

## Lifecycle (high-level)
1. **Initiation**: Problem statement, stakeholders, high-level timeline, sponsor alignment.
2. **Planning**: Scope, resources, milestones, dependencies, team composition.
3. **Execution**: Build, test, review, iterate; maintain transparency through standups and syncs.
4. **Release**: Deploy, verify, announce; conduct smoke tests and post-deployment monitoring.
5. **Close & Retrospective**: Capture learnings, document decisions, identify process improvements.

## Communication Cadence

### Regular Meetings
- **Daily Standups** (15 min): Team syncs on progress, blockers, and dependencies (led by Scrum Master)
- **Weekly PM + PdM Sync** (30 min): Scope, priorities, risks, and stakeholder updates
- **Weekly Delivery Sync** (45 min): Cross-team progress review, risk register review, dependency escalation
- **Bi-weekly Sprint Planning** (1-2 hours): Backlog prioritization, capacity planning, story refinement
- **Monthly Stakeholder Update**: Executive summary of progress, metrics, and upcoming milestones
- **Sprint Retrospectives** (1-1.5 hours): Team reflection on process, action items for improvement

### Escalation Triggers
- Technical or schedule risks: Escalate in weekly delivery sync
- Cross-team dependency blocks: Flag immediately to PM and dependent team leads
- Budget or scope impact: Escalate to Sponsor for decision
- Security or compliance issues: Engage Security Engineer and escalate as needed

## Key Decision Gates

| Phase | Gate | Owner | Criteria |
|-------|------|-------|----------|
| **Initiation** | Go/No-Go | Sponsor + PdM | Success metrics clear; stakeholder alignment confirmed |
| **Planning** | Ready to Execute | PM + Tech Lead | Resources allocated; backlog prioritized; risks identified |
| **Release** | Go Live | PM + QA Lead | All acceptance criteria met; smoke tests pass; comms plan executed |
| **Retrospective** | Lessons Locked In | Scrum Master | Action items documented; owners assigned; follow-up scheduled |

## How to use these docs
- Keep the Project Charter updated in the project repo
- Add process-specific docs into `docs/` for version control and team reference
- Use role descriptions to clarify ownership and responsibilities at project kickoff
- Reference checklists to ensure no critical steps are missed
- Update Risk Register weekly and escalate high-impact items immediately
