# AI Agent Operating Model

## Recommended roles

| Role | Responsibility | Authority |
|---|---|---|
| Specialist Agent | Executes one assigned stage and creates artifacts. | May modify only the assigned scope and authorized files. |
| Reviewer Agent | Independently reviews outputs, evidence, quality and acceptance criteria. | May request changes and mark criteria fail; cannot authorize production actions. |
| Project Orchestrator | Tracks dependencies, stage status, risks, decisions and handoffs. | Coordinates work; production actions still require explicit owner approval. |
| Product / Project Owner | Sets priorities and accepts trade-offs and stage handoffs. | Approves scope, high-impact decisions and releases. |

## Suggested stage state machine

`NOT_STARTED → IN_PROGRESS → READY_FOR_REVIEW → CHANGES_REQUIRED → READY_FOR_REVIEW → APPROVED`

A stage may also be `BLOCKED` when a dependency, authorization or missing decision prevents safe execution.

## Rules for multi-agent work

1. Assign one accountable owner per stage.
2. Give every agent the same approved project configuration and relevant source artifacts.
3. Define shared contracts before parallel frontend/backend or client/server work.
4. Use separate branches or clearly isolated workspaces for concurrent code changes.
5. Resolve conflicting decisions through an ADR and project-owner review.
6. Never let multiple agents edit the same critical file concurrently without coordination.
7. Require evidence-based independent review for architecture, security, data migration and releases.
8. Record prompts and deliverable versions so a decision can be traced.

## Completion is evidence-based

A written claim is not proof. Require actual artifacts, executed test output, design links, diagrams, screenshots, logs or other evidence appropriate to the work. Use `NOT TESTED` when no test was run.
