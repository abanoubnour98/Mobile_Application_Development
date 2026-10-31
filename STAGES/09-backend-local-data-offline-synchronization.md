# Stage 09 — Backend, Local Data, Offline & Synchronization

**Track:** Mobile Application Development  
**Objective:** Connect mobile clients to services and provide reliable data behavior across network conditions.

## Required specialist skills

- API Integration
- Local Persistence
- Offline-First Design
- Sync
- Caching
- Conflict Resolution

## Dependencies / previous inputs

- Stage 05 data architecture
- Stage 08 feature requirements
- Backend/API contracts

## Execution checklist

1. Implement API client, authentication refresh and typed error handling.
2. Choose local persistence and cache strategy based on data sensitivity and access patterns.
3. Define offline access, queued actions, retries and sync conflict resolution.
4. Handle slow, dropped and captive network conditions.
5. Protect local data and clear account/session data safely on logout where required.
6. Test schema evolution, migrations, duplicate operations and partial sync failures.

## Required deliverables

- [ ] API client and data layer
- [ ] Offline and cache behavior
- [ ] Sync/conflict rules
- [ ] Migration strategy
- [ ] Network resilience tests

## Acceptance criteria

- [ ] Core data behavior is predictable offline and online.
- [ ] Sync does not silently lose or duplicate user actions.
- [ ] Sensitive local data is protected.

## Professional tips and common mistakes to avoid

- Do not equate cached data with authoritative server state.
- Use idempotent operations and explicit conflict policies.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior API Integration, Local Persistence, Offline-First Design specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 09 — Backend, Local Data, Offline & Synchronization
- Current objective: Connect mobile clients to services and provide reliable data behavior across network conditions.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stage 05 data architecture
- Stage 08 feature requirements
- Backend/API contracts
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 09: Backend, Local Data, Offline & Synchronization. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- API Integration
- Local Persistence
- Offline-First Design
- Sync
- Caching
- Conflict Resolution
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Implement API client, authentication refresh and typed error handling.
2. Choose local persistence and cache strategy based on data sensitivity and access patterns.
3. Define offline access, queued actions, retries and sync conflict resolution.
4. Handle slow, dropped and captive network conditions.
5. Protect local data and clear account/session data safely on logout where required.
6. Test schema evolution, migrations, duplicate operations and partial sync failures.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- API client and data layer
- Offline and cache behavior
- Sync/conflict rules
- Migration strategy
- Network resilience tests
Save relevant files under `deliverables/stage-09-backend-local-data-offline-synchronization/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Core data behavior is predictable offline and online.
- Sync does not silently lose or duplicate user actions.
- Sensitive local data is protected.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Do not equate cached data with authoritative server state.
- Use idempotent operations and explicit conflict policies.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
