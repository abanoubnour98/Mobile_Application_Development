# Stage 08 — Feature Development & App State

**Track:** Mobile Application Development  
**Objective:** Implement prioritized mobile features in testable vertical slices.

## Required specialist skills

- Mobile Development
- Swift/Kotlin or Selected Framework
- State Management
- Domain Logic
- UI Testing

## Dependencies / previous inputs

- MVP backlog
- Stages 04–07
- API and data contracts where available

## Execution checklist

1. Implement core features with clear presentation/domain/data boundaries.
2. Handle touch input, validation, loading, errors, empty states and accessibility.
3. Manage state across navigation, rotation/resizing where applicable and app lifecycle transitions.
4. Add unit and UI tests for core flows and edge cases.
5. Review battery, memory, responsiveness and user feedback behavior.

## Required deliverables

- [ ] Implemented mobile features
- [ ] Feature tests
- [ ] Updated design/technical notes
- [ ] Acceptance evidence

## Acceptance criteria

- [ ] Each feature meets acceptance criteria on target platforms.
- [ ] Critical flows are automated or covered by repeatable test cases.
- [ ] No dead or placeholder release controls remain.

## Professional tips and common mistakes to avoid

- Build and test increments on real devices early.
- Avoid long-running work on the main/UI thread.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile Development, Swift/Kotlin or Selected Framework, State Management specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 08 — Feature Development & App State
- Current objective: Implement prioritized mobile features in testable vertical slices.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- MVP backlog
- Stages 04–07
- API and data contracts where available
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 08: Feature Development & App State. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile Development
- Swift/Kotlin or Selected Framework
- State Management
- Domain Logic
- UI Testing
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Implement core features with clear presentation/domain/data boundaries.
2. Handle touch input, validation, loading, errors, empty states and accessibility.
3. Manage state across navigation, rotation/resizing where applicable and app lifecycle transitions.
4. Add unit and UI tests for core flows and edge cases.
5. Review battery, memory, responsiveness and user feedback behavior.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Implemented mobile features
- Feature tests
- Updated design/technical notes
- Acceptance evidence
Save relevant files under `deliverables/stage-08-feature-development-app-state/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Each feature meets acceptance criteria on target platforms.
- Critical flows are automated or covered by repeatable test cases.
- No dead or placeholder release controls remain.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Build and test increments on real devices early.
- Avoid long-running work on the main/UI thread.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
