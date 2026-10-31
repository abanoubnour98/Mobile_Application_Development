# Stage 14 — Store Readiness, Compliance & Listing Assets

**Track:** Mobile Application Development  
**Objective:** Prepare accurate app metadata, privacy disclosures, assets and review materials.

## Required specialist skills

- App Store / Google Play Operations
- Policy Review
- Privacy Documentation
- ASO
- Release Management

## Dependencies / previous inputs

- Approved release candidate
- App functionality and data inventory
- Brand assets and legal information

## Execution checklist

1. Review current Apple App Review Guidelines and Google Play policies applicable to the app.
2. Prepare app name, description, category, screenshots, previews, age/content rating and support URLs.
3. Complete privacy labels/data safety disclosures based on actual SDK and app behavior.
4. Prepare privacy policy, account deletion path where required, permissions explanations and reviewer demo access.
5. Verify intellectual property rights for icons, media and screenshots.
6. Create staged rollout and review response plan.

## Required deliverables

- [ ] Store listing metadata
- [ ] Screenshots and promotional assets
- [ ] Privacy declarations
- [ ] Policy review checklist
- [ ] Reviewer notes and demo access

## Acceptance criteria

- [ ] Metadata truthfully represents the shipped app.
- [ ] Privacy and permission disclosures match implementation.
- [ ] Required review access and backend services are ready.

## Professional tips and common mistakes to avoid

- Store policies change; check current official rules before each submission.
- Never hide features or misrepresent app behavior to pass review.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior App Store / Google Play Operations, Policy Review, Privacy Documentation specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 14 — Store Readiness, Compliance & Listing Assets
- Current objective: Prepare accurate app metadata, privacy disclosures, assets and review materials.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Approved release candidate
- App functionality and data inventory
- Brand assets and legal information
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 14: Store Readiness, Compliance & Listing Assets. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- App Store / Google Play Operations
- Policy Review
- Privacy Documentation
- ASO
- Release Management
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Review current Apple App Review Guidelines and Google Play policies applicable to the app.
2. Prepare app name, description, category, screenshots, previews, age/content rating and support URLs.
3. Complete privacy labels/data safety disclosures based on actual SDK and app behavior.
4. Prepare privacy policy, account deletion path where required, permissions explanations and reviewer demo access.
5. Verify intellectual property rights for icons, media and screenshots.
6. Create staged rollout and review response plan.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Store listing metadata
- Screenshots and promotional assets
- Privacy declarations
- Policy review checklist
- Reviewer notes and demo access
Save relevant files under `deliverables/stage-14-store-readiness-compliance-listing-assets/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Metadata truthfully represents the shipped app.
- Privacy and permission disclosures match implementation.
- Required review access and backend services are ready.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Store policies change; check current official rules before each submission.
- Never hide features or misrepresent app behavior to pass review.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
