# Stage 16 — Analytics, Feedback & Continuous Improvement

**Track:** Mobile Application Development  
**Objective:** Improve product value, retention, reliability and usability using responsible measurement.

## Required specialist skills

- Mobile Product Analytics
- Crash Reporting
- UX Analytics
- Experimentation
- Customer Support
- Roadmapping

## Dependencies / previous inputs

- Production app
- Stage 01 success metrics
- Privacy and consent policy

## Execution checklist

1. Validate analytics events and attribution against the measurement plan.
2. Monitor activation, engagement, retention, task completion, crashes, ANRs and performance.
3. Analyze ratings, reviews, support tickets and opt-in feedback.
4. Prioritize improvements by user impact, evidence, effort and risk.
5. Maintain OS compatibility, SDK updates, privacy reviews and deprecation plans.
6. Refresh the roadmap based on measured outcomes.

## Required deliverables

- [ ] Product KPI dashboard
- [ ] Crash/performance dashboard
- [ ] Feedback themes
- [ ] Improvement backlog
- [ ] Maintenance roadmap

## Acceptance criteria

- [ ] Analytics is privacy-aware and useful.
- [ ] Product decisions have evidence and owners.
- [ ] Long-term support and update cadence are defined.

## Professional tips and common mistakes to avoid

- Collect minimum necessary analytics.
- Do not use sensitive data for analytics without a valid purpose and required permissions/consent.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile Product Analytics, Crash Reporting, UX Analytics specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 16 — Analytics, Feedback & Continuous Improvement
- Current objective: Improve product value, retention, reliability and usability using responsible measurement.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Production app
- Stage 01 success metrics
- Privacy and consent policy
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 16: Analytics, Feedback & Continuous Improvement. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile Product Analytics
- Crash Reporting
- UX Analytics
- Experimentation
- Customer Support
- Roadmapping
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Validate analytics events and attribution against the measurement plan.
2. Monitor activation, engagement, retention, task completion, crashes, ANRs and performance.
3. Analyze ratings, reviews, support tickets and opt-in feedback.
4. Prioritize improvements by user impact, evidence, effort and risk.
5. Maintain OS compatibility, SDK updates, privacy reviews and deprecation plans.
6. Refresh the roadmap based on measured outcomes.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Product KPI dashboard
- Crash/performance dashboard
- Feedback themes
- Improvement backlog
- Maintenance roadmap
Save relevant files under `deliverables/stage-16-analytics-feedback-continuous-improvement/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Analytics is privacy-aware and useful.
- Product decisions have evidence and owners.
- Long-term support and update cadence are defined.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Collect minimum necessary analytics.
- Do not use sensitive data for analytics without a valid purpose and required permissions/consent.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
