# Stage 03 — Mobile UX Research & Interaction Design

**Track:** Mobile Application Development  
**Objective:** Design touch-first, interruption-aware and platform-appropriate journeys.

## Required specialist skills

- Mobile UX
- Task Analysis
- Navigation Design
- Gesture Design
- Usability Testing
- Accessibility

## Dependencies / previous inputs

- Stages 01–02
- User research
- Platform conventions

## Execution checklist

1. Map onboarding, primary tasks, authentication, settings, notification and recovery flows.
2. Design touch targets, safe areas, gestures, bottom navigation/tabs and navigation stacks.
3. Define behavior for app backgrounding, resuming, interruptions and state restoration.
4. Design permission education and just-in-time permission requests.
5. Create loading, offline, empty, error, denied-permission and success states.
6. Validate prototypes on representative devices and with accessibility considerations.

## Required deliverables

- [ ] Mobile journey maps
- [ ] Navigation and task flows
- [ ] Wireframes
- [ ] Interaction specifications
- [ ] Usability findings

## Acceptance criteria

- [ ] Core tasks are usable on target screen sizes.
- [ ] Interruption and recovery flows are defined.
- [ ] Platform conventions and accessibility are addressed.

## Professional tips and common mistakes to avoid

- Avoid hiding critical actions behind gestures alone.
- Do not request permissions on first launch without a clear user benefit.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile UX, Task Analysis, Navigation Design specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 03 — Mobile UX Research & Interaction Design
- Current objective: Design touch-first, interruption-aware and platform-appropriate journeys.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stages 01–02
- User research
- Platform conventions
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 03: Mobile UX Research & Interaction Design. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile UX
- Task Analysis
- Navigation Design
- Gesture Design
- Usability Testing
- Accessibility
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Map onboarding, primary tasks, authentication, settings, notification and recovery flows.
2. Design touch targets, safe areas, gestures, bottom navigation/tabs and navigation stacks.
3. Define behavior for app backgrounding, resuming, interruptions and state restoration.
4. Design permission education and just-in-time permission requests.
5. Create loading, offline, empty, error, denied-permission and success states.
6. Validate prototypes on representative devices and with accessibility considerations.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Mobile journey maps
- Navigation and task flows
- Wireframes
- Interaction specifications
- Usability findings
Save relevant files under `deliverables/stage-03-mobile-ux-research-interaction-design/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Core tasks are usable on target screen sizes.
- Interruption and recovery flows are defined.
- Platform conventions and accessibility are addressed.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Avoid hiding critical actions behind gestures alone.
- Do not request permissions on first launch without a clear user benefit.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
