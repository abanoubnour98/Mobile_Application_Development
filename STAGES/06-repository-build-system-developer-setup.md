# Stage 06 — Repository, Build System & Developer Setup

**Track:** Mobile Application Development  
**Objective:** Establish a reproducible multi-platform development and build workflow.

## Required specialist skills

- Git
- Xcode/Android Tooling or Cross-Platform Toolchain
- Dependency Management
- CI
- Code Signing Setup
- Testing Automation

## Dependencies / previous inputs

- Stage 05
- Target build platforms
- Team tooling and release process

## Execution checklist

1. Create repository/module structure and coding standards.
2. Pin toolchain and dependency versions; document SDK and emulator/simulator setup.
3. Configure linting, formatting, static analysis and automated tests.
4. Set up CI builds for target platforms where feasible.
5. Protect signing certificates, provisioning profiles, keystores and secrets.
6. Document local setup, build flavors/configurations and troubleshooting.

## Required deliverables

- [ ] Repository and module structure
- [ ] Developer setup guide
- [ ] CI configuration
- [ ] Build variants
- [ ] Secret/signing process documentation

## Acceptance criteria

- [ ] A team member can build the app with documented steps.
- [ ] CI runs baseline checks.
- [ ] Signing secrets are protected.

## Professional tips and common mistakes to avoid

- Keep debug, staging and production configurations distinct.
- Do not put private keystores or provisioning assets in a public repository.

---

## READY-TO-USE PROMPT

Copy the prompt below into your AI agent or assign it to the relevant specialist. Attach the project configuration, master instructions and all previous-stage deliverables listed above.

```text
ROLE
Act as a senior Git, Xcode/Android Tooling or Cross-Platform Toolchain, Dependency Management specialist with substantial production experience shipping mobile application development. You are responsible for this stage only.

PROJECT CONTEXT
- Read PROJECT_CONFIGURATION.md and MASTER_EXECUTION_INSTRUCTIONS.md.
- Project: {{PROJECT_NAME}}
- Product: {{PRODUCT_NAME}}
- Track: Mobile Application Development
- Current stage: 06 — Repository, Build System & Developer Setup
- Current objective: Establish a reproducible multi-platform development and build workflow.

PREVIOUS WORK — REQUIRED
Review these inputs before doing anything:
- Stage 05
- Target build platforms
- Team tooling and release process
Also inspect relevant deliverables from all earlier stages that are available in the repository. Do not assume unavailable files exist. If a key dependency is missing, record it and decide whether work can safely proceed.

MISSION
Complete Stage 06: Repository, Build System & Developer Setup. Deliver production-usable work, not generic advice or a superficial checklist.

SPECIALIST SKILLS TO APPLY
- Git
- Xcode/Android Tooling or Cross-Platform Toolchain
- Dependency Management
- CI
- Code Signing Setup
- Testing Automation
Discover available specialist skills and official technical documentation relevant to this stage. Read and apply the applicable guidance. Never claim to have used a skill, tool, test or capability that is unavailable.

SCOPE AND TASKS
1. Create repository/module structure and coding standards.
2. Pin toolchain and dependency versions; document SDK and emulator/simulator setup.
3. Configure linting, formatting, static analysis and automated tests.
4. Set up CI builds for target platforms where feasible.
5. Protect signing certificates, provisioning profiles, keystores and secrets.
6. Document local setup, build flavors/configurations and troubleshooting.

REQUIREMENTS
- Preserve approved decisions from earlier stages unless evidence requires a change. Explain any proposed change and identify downstream impact.
- Research current or version-sensitive facts using primary sources and official documentation.
- Separate verified facts, assumptions, recommendations and unknowns.
- Do not fabricate usage data, performance results, benchmarks, user feedback, compliance status or test outcomes.
- Prefer maintainable, secure, accessible and proportionate solutions.
- Consider error, empty, loading, offline, permission-denied, recovery and edge cases wherever relevant.
- Keep the work within this stage. Do not silently begin later stages.

EXPECTED OUTPUTS
- Repository and module structure
- Developer setup guide
- CI configuration
- Build variants
- Secret/signing process documentation
Save relevant files under `deliverables/stage-06-repository-build-system-developer-setup/`. Include a concise README and evidence where useful. Do not create empty placeholder deliverables.

ACCEPTANCE TEST
The stage is complete only when all of the following are satisfied:
- A team member can build the app with documented steps.
- CI runs baseline checks.
- Signing secrets are protected.
For each criterion, report PASS, FAIL or NOT TESTED and attach evidence. Do not mark unverified work as passed.

PROFESSIONAL GUIDANCE
- Keep debug, staging and production configurations distinct.
- Do not put private keystores or provisioning assets in a public repository.

HANDOFF
Complete `templates/STAGE_HANDOFF.md` for this stage. Identify deliverable paths, decisions, unresolved issues, risks, evidence and the exact inputs the next stage must receive. End with a clear status: READY FOR REVIEW, BLOCKED or INCOMPLETE. Do not claim final approval; the project owner/reviewer owns approval.
```

## Stage completion record

- Status: Not started / In progress / Ready for review / Approved / Blocked
- Deliverables folder:
- Reviewer:
- Approval date:
- Notes:
