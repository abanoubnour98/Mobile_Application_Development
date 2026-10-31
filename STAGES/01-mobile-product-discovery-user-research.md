# Stage 01 — Mobile Product Discovery & User Research

**Track:** Mobile Application Development  
**Objective:** Define the mobile-specific problem, context of use, audience and measurable product outcomes.

## Required specialist skills

- Product Discovery
- Mobile User Research
- Business Analysis
- Market Research
- Product Strategy

## Dependencies / previous inputs

- Project configuration
- Business context
- Customer/user evidence

## Execution checklist

1. Identify target users, usage context, frequency, environment and connectivity conditions.
2. Map problems, user goals, current alternatives and platform expectations.
3. Define core mobile use cases, business model and success metrics.
4. Identify privacy, safety, accessibility, localization and regulatory constraints.
5. Define MVP, non-goals and key assumptions to validate.

## Required deliverables

- [ ] Mobile product brief
- [ ] User segments/personas
- [ ] Problem and value proposition
- [ ] MVP scope
- [ ] Success metrics and assumptions log

## Acceptance criteria

- [ ] Mobile use cases and context are explicit.
- [ ] MVP is measurable and prioritized.
- [ ] Risks and assumptions are visible.

## Professional tips and common mistakes to avoid

- Design for real usage contexts: one-handed use, interruptions, variable connectivity and limited attention.
- Do not assume a mobile app is necessary if responsive web or PWA meets the need.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Product Discovery, Mobile User Research, Business Analysis specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 01 — Mobile Product Discovery & User Research
- Current objective: Define the mobile-specific problem, context of use, audience and measurable product outcomes.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Project configuration
- Business context
- Customer/user evidence
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 01: Mobile Product Discovery & User Research. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Product Discovery
- Mobile User Research
- Business Analysis
- Market Research
- Product Strategy
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Identify target users, usage context, frequency, environment and connectivity conditions.
2. Map problems, user goals, current alternatives and platform expectations.
3. Define core mobile use cases, business model and success metrics.
4. Identify privacy, safety, accessibility, localization and regulatory constraints.
5. Define MVP, non-goals and key assumptions to validate.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Mobile product brief
- User segments/personas
- Problem and value proposition
- MVP scope
- Success metrics and assumptions log
Save relevant files under `deliverables/stage-01-mobile-product-discovery-user-research/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Mobile use cases and context are explicit.
- MVP is measurable and prioritized.
- Risks and assumptions are visible.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Design for real usage contexts: one-handed use, interruptions, variable connectivity and limited attention.
- Do not assume a mobile app is necessary if responsive web or PWA meets the need.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
