# Capability Map: Roadmap real-environment acceptance

## 目标

Verify that the released `spec-guard` roadmap reports an active module's
route and its real GitHub tracker state without writing to the repository.

## 模块

| Module id | Responsibility | Depends on |
|---|---|---|
| foundation | Establish the test fixture | — |
| current-work | Render the current roadmap | foundation |
| follow-up | Consume the rendered route | current-work |

Build order: foundation → current-work → follow-up
