# Stage 12 — Accessibility, Performance, Battery & Reliability

**Track:** Mobile Application Development  
**Objective:** Optimize the mobile experience across real devices and usage conditions.

## Required specialist skills

- Mobile Performance
- Profiling
- Accessibility
- Battery Optimization
- Crash Diagnostics
- Device Compatibility

## Dependencies / previous inputs

- Working app build
- Quality requirements
- Representative device matrix

## Execution checklist

1. Measure launch time, frame stability, memory, network, battery and storage use.
2. Profile on representative lower- and mid-range devices.
3. Test dynamic type/font scaling, screen readers, contrast, focus and touch target sizes.
4. Test background/foreground, low storage, low battery, weak network and device rotation/resizing.
5. Set crash-free and performance goals based on user impact and feasibility.

## Required deliverables

- [ ] Performance baseline
- [ ] Accessibility audit
- [ ] Battery/reliability report
- [ ] Optimization backlog

## Acceptance criteria

- [ ] Performance meets agreed device-specific thresholds.
- [ ] Critical accessibility issues are fixed.
- [ ] App remains stable through expected interruptions and resource constraints.

## Professional tips and common mistakes to avoid

- Measure real-device behavior; emulator results are not sufficient alone.
- Avoid excessive background work and unnecessary location polling.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Mobile Performance, Profiling, Accessibility specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 12 — Accessibility, Performance, Battery & Reliability
- Current objective: Optimize the mobile experience across real devices and usage conditions.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Working app build
- Quality requirements
- Representative device matrix
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 12: Accessibility, Performance, Battery & Reliability. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Mobile Performance
- Profiling
- Accessibility
- Battery Optimization
- Crash Diagnostics
- Device Compatibility
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Measure launch time, frame stability, memory, network, battery and storage use.
2. Profile on representative lower- and mid-range devices.
3. Test dynamic type/font scaling, screen readers, contrast, focus and touch target sizes.
4. Test background/foreground, low storage, low battery, weak network and device rotation/resizing.
5. Set crash-free and performance goals based on user impact and feasibility.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Performance baseline
- Accessibility audit
- Battery/reliability report
- Optimization backlog
Save relevant files under `deliverables/stage-12-accessibility-performance-battery-reliability/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- Performance meets agreed device-specific thresholds.
- Critical accessibility issues are fixed.
- App remains stable through expected interruptions and resource constraints.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Measure real-device behavior; emulator results are not sufficient alone.
- Avoid excessive background work and unnecessary location polling.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
