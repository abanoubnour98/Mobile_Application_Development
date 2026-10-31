<div align="center">

# Mobile Application Development

### A standalone, stage-gated AI-assisted development playbook

![Stages](https://img.shields.io/badge/stages-16-2563EB?style=for-the-badge) ![Prompts](https://img.shields.io/badge/AI--ready-prompts-805AD5?style=for-the-badge) ![Docs](https://img.shields.io/badge/docs-Markdown-475569?style=for-the-badge)

**An independent project folder with its own configuration, prompts, stage deliverables, quality gates and templates.**

[Quick Start](#-quick-start) · [Stage List](STAGE_INDEX.md) · [Workflow Overview](WORKFLOW_OVERVIEW.md) · [Templates](#-project-templates)

</div>

---

## What is this?

A stage-gated playbook for planning, designing, engineering, testing, securing, releasing and improving iOS and Android mobile applications.

This folder is a **standalone project playbook**. It contains everything required to run this workflow independently. It does not require a shared parent project, a sibling folder or another platform workflow.

## Visual workflow

![Mobile application workflow](assets/workflow.svg)

## 🚀 Quick Start

### 1. Configure your project

Open [`PROJECT_CONFIGURATION.md`](PROJECT_CONFIGURATION.md). Fill in the information already known and leave unknown fields blank. Never place API keys, passwords, private keys, signing certificates or production secrets in the configuration file.

### 2. Read the execution rules

Read [`MASTER_EXECUTION_INSTRUCTIONS.md`](MASTER_EXECUTION_INSTRUCTIONS.md). These instructions apply to every stage prompt and AI agent in this project.

### 3. Review the complete workflow

Read [`WORKFLOW_OVERVIEW.md`](WORKFLOW_OVERVIEW.md) and [`STAGE_INDEX.md`](STAGE_INDEX.md). The stage index links to every detailed execution prompt.

### 4. Execute Stage 01

Open the first file under `STAGES/` and copy its **READY-TO-USE PROMPT** section. Provide the agent with:

1. This project's `PROJECT_CONFIGURATION.md`.
2. `MASTER_EXECUTION_INSTRUCTIONS.md`.
3. The selected stage prompt.
4. The actual previous-stage deliverables required by that stage.

Do not assume an AI agent can access previous conversations, local files, designs or repositories automatically. Attach or explicitly link the required inputs.

### 5. Review and hand off

The agent must save its work under `deliverables/stage-XX-<short-name>/`, complete [`templates/STAGE_HANDOFF.md`](templates/STAGE_HANDOFF.md), and provide evidence for every acceptance criterion. Use [`REVIEWER_PROMPT.md`](REVIEWER_PROMPT.md) for an independent review. The project owner or assigned reviewer approves the handoff.

### 6. Continue stage by stage

Do not advance because an agent says the work is complete. Advance only when deliverables exist, acceptance criteria have evidence, unresolved issues are recorded and the handoff is approved.

## 🧭 Stage sequence

| Stage | Focus | Primary output |
|---:|---|---|
| 01 | [Mobile Product Discovery & User Research](STAGES/01-mobile-product-discovery-user-research.md) | Mobile product brief |
| 02 | [Platform Strategy & Requirements](STAGES/02-platform-strategy-requirements.md) | Platform decision matrix |
| 03 | [Mobile UX Research & Interaction Design](STAGES/03-mobile-ux-research-interaction-design.md) | Mobile journey maps |
| 04 | [Mobile UI Design & Design System](STAGES/04-mobile-ui-design-design-system.md) | High-fidelity mobile screens |
| 05 | [Mobile Architecture & Technology Selection](STAGES/05-mobile-architecture-technology-selection.md) | Architecture decision records |
| 06 | [Repository, Build System & Developer Setup](STAGES/06-repository-build-system-developer-setup.md) | Repository and module structure |
| 07 | [App Foundation, Navigation & Lifecycle](STAGES/07-app-foundation-navigation-lifecycle.md) | Runnable app foundation |
| 08 | [Feature Development & App State](STAGES/08-feature-development-app-state.md) | Implemented mobile features |
| 09 | [Backend, Local Data, Offline & Synchronization](STAGES/09-backend-local-data-offline-synchronization.md) | API client and data layer |
| 10 | [Native Capabilities, Permissions & Notifications](STAGES/10-native-capabilities-permissions-notifications.md) | Native integration modules |
| 11 | [Mobile Security & Privacy Engineering](STAGES/11-mobile-security-privacy-engineering.md) | Mobile security assessment |
| 12 | [Accessibility, Performance, Battery & Reliability](STAGES/12-accessibility-performance-battery-reliability.md) | Performance baseline |
| 13 | [QA, Device Matrix & Release Candidate](STAGES/13-qa-device-matrix-release-candidate.md) | Test plan and results |
| 14 | [Store Readiness, Compliance & Listing Assets](STAGES/14-store-readiness-compliance-listing-assets.md) | Store listing metadata |
| 15 | [Release, Rollout & Post-Launch Operations](STAGES/15-release-rollout-post-launch-operations.md) | Published release |
| 16 | [Analytics, Feedback & Continuous Improvement](STAGES/16-analytics-feedback-continuous-improvement.md) | Product KPI dashboard |

See [`STAGE_INDEX.md`](STAGE_INDEX.md) for the full sequence and direct links to all prompts.

## 📦 Project structure

```text
Mobile_Application_Development/
├── README.md
├── PROJECT_CONFIGURATION.md
├── MASTER_EXECUTION_INSTRUCTIONS.md
├── AGENT_OPERATING_MODEL.md
├── REVIEWER_PROMPT.md
├── WORKFLOW_OVERVIEW.md
├── STAGE_INDEX.md
├── STAGES/
├── templates/
├── assets/
├── CONTRIBUTING.md
├── SECURITY.md
└── GITHUB_REPOSITORY_DETAILS.md
```

## 🤖 Working with AI agents

- Assign one specialist agent to execute the stage.
- Use a separate reviewer agent for independent verification.
- Keep the project configuration and approved decisions consistent.
- Pass the actual artifacts from previous stages to the next agent.
- Record assumptions, decisions, risks and evidence.
- Never claim a test, audit, deployment or compliance check passed unless it was actually performed.

See [`AGENT_OPERATING_MODEL.md`](AGENT_OPERATING_MODEL.md) for the full operating model.

## 🧩 Project templates

| Template | Purpose |
|---|---|
| [`templates/STAGE_HANDOFF.md`](templates/STAGE_HANDOFF.md) | Stage-to-stage handoff and approval. |
| [`templates/ADR_TEMPLATE.md`](templates/ADR_TEMPLATE.md) | Architecture Decision Records. |
| [`templates/DEFECT_REPORT.md`](templates/DEFECT_REPORT.md) | Reproducible bug and defect tracking. |
| [`templates/RISK_REGISTER.md`](templates/RISK_REGISTER.md) | Project risk tracking. |
| [`templates/RELEASE_READINESS.md`](templates/RELEASE_READINESS.md) | Release readiness checklist. |
| [`templates/PROJECT_STAGE_TRACKER.md`](templates/PROJECT_STAGE_TRACKER.md) | Stage progress and ownership. |

## ✅ Quality principles

- Security, privacy, accessibility and reliability are cross-cutting requirements.
- Use official and current platform documentation for version-sensitive decisions.
- Prefer maintainable, testable and appropriately simple architecture.
- Validate on representative target environments and devices.
- Preserve evidence for test results and important decisions.
- Do not deploy, publish, delete production data, spend money or perform irreversible actions without explicit authorization.

## 📚 Repository and contribution guidance

- [GitHub repository details](GITHUB_REPOSITORY_DETAILS.md)
- [Contributing](CONTRIBUTING.md)
- [Security policy](SECURITY.md)

## Important

This package provides workflow guidance and prompt templates. It does not mean research, design, implementation, testing or release work has already been completed. Every stage must be executed and supported by actual, reviewable deliverables.
