# Stage 11 — Mobile Security & Privacy Engineering

**Track:** Mobile Application Development  
**Objective:** Protect mobile data, credentials, network traffic, platform interfaces and user privacy.

## Required specialist skills

- Mobile Security
- OWASP MASVS/MASTG
- Secure Storage
- Keychain/Keystore
- Network Security
- Privacy Engineering

## Dependencies / previous inputs

- Stage 05 threat model
- Stages 09–10 data and permission flows
- Applicable legal requirements

## Execution checklist

1. Review secure storage, cryptography, authentication, session handling and network security.
2. Protect tokens and sensitive data using platform security facilities.
3. Assess deep links, exported components, intents, IPC, WebViews and inter-app communication.
4. Review SDK data collection, tracking, consent, retention and deletion.
5. Perform static, dynamic and dependency analysis based on risk.
6. Document vulnerability reporting and incident response.

## Required deliverables

- [ ] Mobile security assessment
- [ ] Privacy/data inventory
- [ ] SDK and permission review
- [ ] Security test evidence
- [ ] Remediation register

## Acceptance criteria

- [ ] No unresolved critical security issue remains for release.
- [ ] Sensitive data is not exposed through logs, backups or insecure storage.
- [ ] Privacy notices match actual SDK and data behavior.

## Professional tips and common mistakes to avoid

- Use OWASP MASVS and MASTG as security verification references.
- Do not rely on client-side obfuscation as the primary security control.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile Security, OWASP MASVS/MASTG, Secure Storage specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 11 — Mobile Security & Privacy Engineering
- Current objective: Protect mobile data, credentials, network traffic, platform interfaces and user privacy.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stage 05 threat model
- Stages 09–10 data and permission flows
- Applicable legal requirements
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 11: Mobile Security & Privacy Engineering. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile Security
- OWASP MASVS/MASTG
- Secure Storage
- Keychain/Keystore
- Network Security
- Privacy Engineering
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Review secure storage, cryptography, authentication, session handling and network security.
2. Protect tokens and sensitive data using platform security facilities.
3. Assess deep links, exported components, intents, IPC, WebViews and inter-app communication.
4. Review SDK data collection, tracking, consent, retention and deletion.
5. Perform static, dynamic and dependency analysis based on risk.
6. Document vulnerability reporting and incident response.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Mobile security assessment
- Privacy/data inventory
- SDK and permission review
- Security test evidence
- Remediation register
Save relevant files under `deliverables/stage-11-mobile-security-privacy-engineering/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- No unresolved critical security issue remains for release.
- Sensitive data is not exposed through logs, backups or insecure storage.
- Privacy notices match actual SDK and data behavior.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Use OWASP MASVS and MASTG as security verification references.
- Do not rely on client-side obfuscation as the primary security control.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
