# Stage 02 — Platform Strategy & Requirements

**Track:** Mobile Application Development  
**Objective:** Choose supported platforms and define functional and quality requirements.

## Required specialist skills

- Requirements Engineering
- iOS/Android Platform Analysis
- Native/Cross-Platform Evaluation
- Device Compatibility
- Release Strategy

## Dependencies / previous inputs

- Stage 01
- Target audience device mix
- Feature, hardware and distribution requirements

## Execution checklist

1. Decide iOS, Android or both based on audience, product needs and operational constraints.
2. Compare native Swift/Kotlin with cross-platform options such as Flutter or React Native.
3. Define minimum OS versions, screen sizes, device classes, tablets, foldables and hardware dependencies.
4. Specify offline behavior, background work, push notifications, deep links and app lifecycle needs.
5. Define store distribution, enterprise distribution, staged rollout and update expectations.
6. Create requirements traceability and platform-specific risk register.

## Required deliverables

- [ ] Platform decision matrix
- [ ] Requirements specification
- [ ] Device/OS support matrix
- [ ] Distribution strategy
- [ ] Prioritized MVP backlog

## Acceptance criteria

- [ ] Platform decision has evidence and trade-offs.
- [ ] OS/device support is explicit.
- [ ] All MVP requirements have acceptance criteria.

## Professional tips and common mistakes to avoid

- Do not choose cross-platform solely to share code; validate native capability and performance needs.
- Keep release, privacy and store requirements in scope from the start.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Requirements Engineering, iOS/Android Platform Analysis, Native/Cross-Platform Evaluation specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 02 — Platform Strategy & Requirements
- Current objective: Choose supported platforms and define functional and quality requirements.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stage 01
- Target audience device mix
- Feature, hardware and distribution requirements
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 02: Platform Strategy & Requirements. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Requirements Engineering
- iOS/Android Platform Analysis
- Native/Cross-Platform Evaluation
- Device Compatibility
- Release Strategy
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Decide iOS, Android or both based on audience, product needs and operational constraints.
2. Compare native Swift/Kotlin with cross-platform options such as Flutter or React Native.
3. Define minimum OS versions, screen sizes, device classes, tablets, foldables and hardware dependencies.
4. Specify offline behavior, background work, push notifications, deep links and app lifecycle needs.
5. Define store distribution, enterprise distribution, staged rollout and update expectations.
6. Create requirements traceability and platform-specific risk register.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Platform decision matrix
- Requirements specification
- Device/OS support matrix
- Distribution strategy
- Prioritized MVP backlog
Save relevant files under `deliverables/stage-02-platform-strategy-requirements/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Platform decision has evidence and trade-offs.
- OS/device support is explicit.
- All MVP requirements have acceptance criteria.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Do not choose cross-platform solely to share code; validate native capability and performance needs.
- Keep release, privacy and store requirements in scope from the start.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
