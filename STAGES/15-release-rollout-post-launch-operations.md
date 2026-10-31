# Stage 15 — Release, Rollout & Post-Launch Operations

**Track:** Mobile Application Development  
**Objective:** Publish safely, observe real-device outcomes and maintain app health.

## Required specialist skills

- Mobile Release Engineering
- Store Console Operations
- Crash Analytics
- Feature Flags
- Incident Management

## Dependencies / previous inputs

- Stage 14 approval
- Signed release artifacts
- Release notes and rollout plan

## Execution checklist

1. Build and sign production artifacts with protected credentials.
2. Submit to relevant stores or approved distribution channels.
3. Use phased/staged rollout where available and monitor crashes, ANRs, reviews and critical flows.
4. Prepare hotfix and rollback/roll-forward procedures consistent with store capabilities.
5. Confirm backend capacity, feature flags, support channels and release communications.
6. Document release version, build provenance and known issues.

## Required deliverables

- [ ] Published release
- [ ] Release notes
- [ ] Rollout dashboard
- [ ] Incident and hotfix plan
- [ ] Release record

## Acceptance criteria

- [ ] The production build matches the approved candidate.
- [ ] Rollout health is monitored and rollback/hotfix ownership is clear.
- [ ] Support and incident channels are active.

## Professional tips and common mistakes to avoid

- Do not roll out to all users before monitoring early cohorts.
- Ensure backend changes remain compatible with older supported app versions.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile Release Engineering, Store Console Operations, Crash Analytics specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 15 — Release, Rollout & Post-Launch Operations
- Current objective: Publish safely, observe real-device outcomes and maintain app health.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stage 14 approval
- Signed release artifacts
- Release notes and rollout plan
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 15: Release, Rollout & Post-Launch Operations. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile Release Engineering
- Store Console Operations
- Crash Analytics
- Feature Flags
- Incident Management
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Build and sign production artifacts with protected credentials.
2. Submit to relevant stores or approved distribution channels.
3. Use phased/staged rollout where available and monitor crashes, ANRs, reviews and critical flows.
4. Prepare hotfix and rollback/roll-forward procedures consistent with store capabilities.
5. Confirm backend capacity, feature flags, support channels and release communications.
6. Document release version, build provenance and known issues.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Published release
- Release notes
- Rollout dashboard
- Incident and hotfix plan
- Release record
Save relevant files under `deliverables/stage-15-release-rollout-post-launch-operations/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- The production build matches the approved candidate.
- Rollout health is monitored and rollback/hotfix ownership is clear.
- Support and incident channels are active.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Do not roll out to all users before monitoring early cohorts.
- Ensure backend changes remain compatible with older supported app versions.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
