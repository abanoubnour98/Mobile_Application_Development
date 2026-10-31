# Stage 13 — QA, Device Matrix & Release Candidate

**Track:** Mobile Application Development  
**Objective:** Verify functionality, compatibility, privacy and reliability before store submission.

## Required specialist skills

- Mobile QA
- Unit/Integration/UI Testing
- Device Farm
- Exploratory Testing
- Security Testing
- Regression

## Dependencies / previous inputs

- Stages 01–13
- Release candidate
- Device/OS support matrix

## Execution checklist

1. Run unit, integration, UI automation and manual exploratory tests.
2. Test supported OS versions, screen sizes, hardware, orientation and accessibility settings.
3. Test install, upgrade, uninstall, account deletion, permissions, offline, notifications and deep links.
4. Test interruptions such as phone calls, app switching, lock/unlock, low memory and network changes.
5. Review crash reports, security findings and analytics/privacy behavior.
6. Record defects and obtain release sign-off.

## Required deliverables

- [ ] Test plan and results
- [ ] Device compatibility matrix
- [ ] Defect log
- [ ] Security and privacy verification
- [ ] Release candidate approval

## Acceptance criteria

- [ ] All critical journeys pass on supported targets.
- [ ] No release-blocking defect remains.
- [ ] Store policy and privacy requirements are checked.

## Professional tips and common mistakes to avoid

- Test on physical devices in addition to simulators/emulators.
- Include clean install and upgrade from prior released versions.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile QA, Unit/Integration/UI Testing, Device Farm specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 13 — QA, Device Matrix & Release Candidate
- Current objective: Verify functionality, compatibility, privacy and reliability before store submission.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stages 01–13
- Release candidate
- Device/OS support matrix
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 13: QA, Device Matrix & Release Candidate. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile QA
- Unit/Integration/UI Testing
- Device Farm
- Exploratory Testing
- Security Testing
- Regression
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Run unit, integration, UI automation and manual exploratory tests.
2. Test supported OS versions, screen sizes, hardware, orientation and accessibility settings.
3. Test install, upgrade, uninstall, account deletion, permissions, offline, notifications and deep links.
4. Test interruptions such as phone calls, app switching, lock/unlock, low memory and network changes.
5. Review crash reports, security findings and analytics/privacy behavior.
6. Record defects and obtain release sign-off.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Test plan and results
- Device compatibility matrix
- Defect log
- Security and privacy verification
- Release candidate approval
Save relevant files under `deliverables/stage-13-qa-device-matrix-release-candidate/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- All critical journeys pass on supported targets.
- No release-blocking defect remains.
- Store policy and privacy requirements are checked.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Test on physical devices in addition to simulators/emulators.
- Include clean install and upgrade from prior released versions.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
