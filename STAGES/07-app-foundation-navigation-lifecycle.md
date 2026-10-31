# Stage 07 — App Foundation, Navigation & Lifecycle

**Track:** Mobile Application Development  
**Objective:** Implement app startup, navigation, lifecycle handling and shared foundations.

## Required specialist skills

- Mobile UI Engineering
- Navigation
- Lifecycle Management
- State Restoration
- Localization
- Logging

## Dependencies / previous inputs

- Stages 03–06
- Approved designs
- Architecture and build setup

## Execution checklist

1. Implement app entry point, navigation structure, app theme and shared UI components.
2. Handle foreground/background transitions, process recreation and state restoration.
3. Implement dependency initialization, environment configuration and safe logging.
4. Add localization framework, accessibility defaults and reusable error/empty/loading components.
5. Configure deep-link routing and app-level lifecycle behavior where required.

## Required deliverables

- [ ] Runnable app foundation
- [ ] Navigation implementation
- [ ] Lifecycle/state restoration
- [ ] Shared components
- [ ] Localization and logging foundation

## Acceptance criteria

- [ ] App launches and navigates reliably.
- [ ] Critical user state survives supported interruptions.
- [ ] Foundation matches agreed design and architecture.

## Professional tips and common mistakes to avoid

- Test kill/relaunch and process recreation.
- Never assume the app remains active in the background.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile UI Engineering, Navigation, Lifecycle Management specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 07 — App Foundation, Navigation & Lifecycle
- Current objective: Implement app startup, navigation, lifecycle handling and shared foundations.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stages 03–06
- Approved designs
- Architecture and build setup
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 07: App Foundation, Navigation & Lifecycle. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile UI Engineering
- Navigation
- Lifecycle Management
- State Restoration
- Localization
- Logging
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Implement app entry point, navigation structure, app theme and shared UI components.
2. Handle foreground/background transitions, process recreation and state restoration.
3. Implement dependency initialization, environment configuration and safe logging.
4. Add localization framework, accessibility defaults and reusable error/empty/loading components.
5. Configure deep-link routing and app-level lifecycle behavior where required.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Runnable app foundation
- Navigation implementation
- Lifecycle/state restoration
- Shared components
- Localization and logging foundation
Save relevant files under `deliverables/stage-07-app-foundation-navigation-lifecycle/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- App launches and navigates reliably.
- Critical user state survives supported interruptions.
- Foundation matches agreed design and architecture.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Test kill/relaunch and process recreation.
- Never assume the app remains active in the background.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
