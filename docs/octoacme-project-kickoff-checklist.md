# OctoAcme Project Kickoff Checklist & Template

## Pre-Kickoff (1-2 weeks before)

- [ ] **Schedule kickoff meeting** with all key stakeholders, Sponsor, and team leads
- [ ] **Draft Project Charter / One-pager** (Problem, Goal, Success Metrics, Timeline, Budget)
- [ ] **Identify team members** and confirm availability
- [ ] **Prepare stakeholder list** and communication plan
- [ ] **Gather any existing requirements** or related documentation
- [ ] **Identify potential risks** or dependencies
- [ ] **Set up project tools** (GitHub project board, Slack channel, wiki or docs folder)

## Kickoff Meeting Agenda (90 minutes)

### 1. Welcome & Intro (5 min)
- Facilitator: Project Manager
- Confirm attendance; explain agenda and time blocks

### 2. Project Overview (15 min)
- **Presenter:** Sponsor or Project Manager
- **Content:** Problem statement, business goal, why this project matters
- **Q&A:** Clarify the "why" and strategic importance

### 3. Success Metrics & Timeline (10 min)
- **Presenter:** Product Manager
- **Content:** Definition of success, key metrics, high-level milestones
- **Q&A:** Confirm stakeholder alignment on scope and expectations

### 4. Team Roles & Decision-Making Authority (10 min)
- **Presenter:** Project Manager
- **Content:** Team composition, RACI matrix, who decides what
- **Q&A:** Clarify role expectations and escalation paths

### 5. Scope, Constraints & Dependencies (15 min)
- **Presenter:** Tech Lead (technical scope/constraints) + Business Analyst (dependencies)
- **Content:** What's in/out of scope, known constraints, external dependencies
- **Q&A:** Identify concerns early; flag high-risk dependencies

### 6. Initial Risks & Assumptions (10 min)
- **Presenter:** Tech Lead + Project Manager
- **Content:** Known risks, open assumptions, mitigations in progress
- **Q&A:** Brainstorm risk mitigation with team

### 7. Communication Plan & Cadence (10 min)
- **Presenter:** Project Manager
- **Content:** Meeting schedule (standups, syncs, retrospectives), communication channels, escalation path
- **Output:** Calendar invites sent immediately post-kickoff

### 8. Next Steps & Close (15 min)
- **Facilitator:** Project Manager
- **Content:** Planning phase activities, when planning begins, any pre-work for team
- **Action Items:** Capture and assign owners

## Post-Kickoff (within 1 week)

- [ ] **Send kickoff summary** to all attendees (decisions, action items, next meeting)
- [ ] **Create Project Charter** in repo with stakeholder sign-off
- [ ] **Set up communication channels** (Slack, GitHub discussions, wiki)
- [ ] **Initiate backlog refinement** with Product Manager and Tech Lead
- [ ] **Schedule planning phase** activities (estimation, design, dependency mapping)
- [ ] **Confirm all action items** from kickoff are assigned and tracked
- [ ] **Begin Risk Register** with initial risks identified in kickoff

---

## Project Charter Template

```markdown
# Project Charter: [Project Name]

## Executive Summary
[1-2 paragraphs describing the project at high level]

## Problem Statement
[What is the business problem we're solving?]

## Objectives / Goals (SMART)
- Goal 1: [Specific, Measurable, Achievable, Relevant, Time-bound]
- Goal 2: ...

## Success Metrics
- Metric 1: [Target value and how we measure it]
- Metric 2: ...
- Metric 3: ...

## Scope

### In Scope
- Feature/capability 1
- Feature/capability 2

### Out of Scope
- What we're explicitly NOT doing and why

## High-Level Timeline & Milestones

| Milestone | Target Date | Owner | Status |
|-----------|------------|-------|--------|
| Kickoff & Planning | [Date] | PM | Scheduled |
| Development Start | [Date] | Tech Lead | Planned |
| Beta/Testing Phase | [Date] | QA | Planned |
| Release to Production | [Date] | PM | Planned |

## Budget & Resources

### Team Composition
- Project Manager: [Name]
- Product Manager: [Name]
- Tech Lead: [Name]
- Developers: [Names, FTE]
- QA: [Names, FTE]
- Other roles as needed: [Names]

### Budget
- [Budget allocation, if applicable]

## Stakeholders & Communication

### Stakeholder List

| Name | Title | Role | Communication Frequency |
|------|-------|------|-------------------------|
| [Name] | [Title] | [Sponsor/Approver/Informed] | [Monthly/Weekly/As-needed] |

### Communication Plan
- Daily standups: 15 min, [Time], [Channel]
- Weekly delivery sync: 45 min, [Day/Time]
- Monthly stakeholder updates: [Day/Time]
- Escalation: [Contact PM first, then Sponsor]

## Known Risks & Assumptions

### Assumptions
- Assumption 1: [What we're assuming to be true]
- Assumption 2: ...

### Initial Risks

| Risk ID | Description | Impact | Probability | Mitigation | Owner |
|---------|-------------|--------|-------------|-----------|-------|
| R1 | [Description] | High/Med/Low | High/Med/Low | [Action] | [Owner] |

## Decision-Making Authority

### Who Decides What?

| Decision Type | Decision Maker | Consultation | Comment |
|-----------|-------------|--------------|---------|
| Feature scope | Product Manager | Sponsor, Tech Lead | Can add/remove with Sponsor approval |
| Technical approach | Tech Lead | Developers, QA | Balance quality/speed trade-offs |
| Timeline/resources | Project Manager | Sponsor, Tech Lead | Escalate conflicts to Sponsor |
| Release dates | Project Manager + Sponsor | PdM, Tech Lead, QA | Final go/no-go decision |

## Sign-Off

- [ ] Product Manager: ____________________ Date: _______
- [ ] Project Manager: ____________________ Date: _______
- [ ] Sponsor: ____________________ Date: _______
- [ ] Tech Lead: ____________________ Date: _______
```

---

## Kickoff Meeting Best Practices

✅ **Do:**
- **Start on time;** respect everyone's schedule
- **Keep it interactive;** invite questions and discussion
- **Document decisions;** capture action items with owners
- **Clarify roles early;** avoid ambiguity
- **Set psychological safety;** encourage concerns and candid feedback
- **End with next steps;** everyone leaves knowing what happens next

❌ **Don't:**
- **Over-explain details;** save deep dives for planning sessions
- **Leave ambiguity;** if something's unclear, address it now
- **Skip stakeholder input;** this is their chance to weigh in
- **Make promises** beyond team's capacity; realistic planning upfront
- **Rush through decisions;** take time needed for alignment
- **Forget to schedule follow-ups;** confirm calendar invites before people leave
