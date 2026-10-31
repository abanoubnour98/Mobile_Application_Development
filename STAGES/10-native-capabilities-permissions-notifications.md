# Stage 10 — Native Capabilities, Permissions & Notifications

**Track:** Mobile Application Development  
**Objective:** Integrate platform services safely and with clear user value.

## Required specialist skills

- iOS/Android APIs
- Permissions
- Push Notifications
- Camera/GPS/Bluetooth/Files as needed
- Deep Links
- Background Tasks

## Dependencies / previous inputs

- Stages 02, 04–05 and 08–09
- Feature capability requirements
- Privacy/data inventory

## Execution checklist

1. Implement only required device capabilities such as camera, location, photos, contacts, Bluetooth, biometrics or notifications.
2. Explain permission purpose before requesting access when appropriate.
3. Use least privilege and platform pickers/scoped access where possible.
4. Handle denied, limited, revoked and restricted permissions.
5. Configure push token lifecycle, notification preferences and deep links securely.
6. Test capability behavior across OS versions and device types.

## Required deliverables

- [ ] Native integration modules
- [ ] Permission purpose matrix
- [ ] Notification and deep-link flows
- [ ] Fallback behavior
- [ ] Platform tests

## Acceptance criteria

- [ ] Only necessary permissions are requested.
- [ ] Denial or revocation does not crash core functionality.
- [ ] Notifications and deep links route safely.

## Professional tips and common mistakes to avoid

- Do not request sensitive permissions for unrelated use cases.
- A push notification payload must not expose sensitive information on a lock screen.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior iOS/Android APIs, Permissions, Push Notifications specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 10 — Native Capabilities, Permissions & Notifications
- Current objective: Integrate platform services safely and with clear user value.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stages 02, 04–05 and 08–09
- Feature capability requirements
- Privacy/data inventory
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 10: Native Capabilities, Permissions & Notifications. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- iOS/Android APIs
- Permissions
- Push Notifications
- Camera/GPS/Bluetooth/Files as needed
- Deep Links
- Background Tasks
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Implement only required device capabilities such as camera, location, photos, contacts, Bluetooth, biometrics or notifications.
2. Explain permission purpose before requesting access when appropriate.
3. Use least privilege and platform pickers/scoped access where possible.
4. Handle denied, limited, revoked and restricted permissions.
5. Configure push token lifecycle, notification preferences and deep links securely.
6. Test capability behavior across OS versions and device types.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Native integration modules
- Permission purpose matrix
- Notification and deep-link flows
- Fallback behavior
- Platform tests
Save relevant files under `deliverables/stage-10-native-capabilities-permissions-notifications/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Only necessary permissions are requested.
- Denial or revocation does not crash core functionality.
- Notifications and deep links route safely.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Do not request sensitive permissions for unrelated use cases.
- A push notification payload must not expose sensitive information on a lock screen.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
