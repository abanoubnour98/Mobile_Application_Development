# Stage 05 — Mobile Architecture & Technology Selection

**Track:** Mobile Application Development  
**Objective:** Define maintainable application architecture, platform boundaries and data flow.

## Required specialist skills

- Mobile Architecture
- Swift/Kotlin/Flutter/React Native Evaluation
- Domain Modeling
- State Management
- ADR Writing
- Threat Modeling

## Dependencies / previous inputs

- Stages 01–04
- Platform support matrix
- Offline, performance and hardware requirements

## Execution checklist

1. Select native or cross-platform architecture using capability, team, performance and lifecycle needs.
2. Define presentation, domain and data boundaries with clear state management.
3. Design navigation, dependency injection, networking, persistence and error handling.
4. Specify platform channels/native modules and third-party SDK policies where applicable.
5. Define offline-first behavior, synchronization and secure storage.
6. Create architecture diagrams, ADRs and threat model.

## Required deliverables

- [ ] Architecture decision records
- [ ] Component and data-flow diagrams
- [ ] Module boundaries
- [ ] SDK evaluation
- [ ] Threat model

## Acceptance criteria

- [ ] Architecture supports target platforms and core features.
- [ ] Native access and trust boundaries are explicit.
- [ ] Key trade-offs are documented.

## Professional tips and common mistakes to avoid

- Avoid unnecessary abstraction layers.
- Keep business rules testable outside UI and platform lifecycle code.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile Architecture, Swift/Kotlin/Flutter/React Native Evaluation, Domain Modeling specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 05 — Mobile Architecture & Technology Selection
- Current objective: Define maintainable application architecture, platform boundaries and data flow.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stages 01–04
- Platform support matrix
- Offline, performance and hardware requirements
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 05: Mobile Architecture & Technology Selection. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile Architecture
- Swift/Kotlin/Flutter/React Native Evaluation
- Domain Modeling
- State Management
- ADR Writing
- Threat Modeling
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Select native or cross-platform architecture using capability, team, performance and lifecycle needs.
2. Define presentation, domain and data boundaries with clear state management.
3. Design navigation, dependency injection, networking, persistence and error handling.
4. Specify platform channels/native modules and third-party SDK policies where applicable.
5. Define offline-first behavior, synchronization and secure storage.
6. Create architecture diagrams, ADRs and threat model.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Architecture decision records
- Component and data-flow diagrams
- Module boundaries
- SDK evaluation
- Threat model
Save relevant files under `deliverables/stage-05-mobile-architecture-technology-selection/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Architecture supports target platforms and core features.
- Native access and trust boundaries are explicit.
- Key trade-offs are documented.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Avoid unnecessary abstraction layers.
- Keep business rules testable outside UI and platform lifecycle code.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
