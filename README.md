# Durable_CHATGPT

Global durable-workflow framework and GitHub-backed project state for `Durable_CHATGPT`. Independent project repositories inherit versioned policies and keep their own durable records.

## Durable state

- [Context](Durable_CHATGPT_Context.md) — current authoritative project state
- [TODO](Durable_CHATGPT_TODO.md) — unfinished, blocked, waiting, and deferred work
- [Decision Log](Durable_CHATGPT_Decision_Log.md) — durable project decisions
- [New Chat Bootstrap](Durable_CHATGPT_New_Chat_Bootstrap_Prompt.md) — restore instructions for a fresh ChatGPT conversation

## Operating model

**ChatGPT conversations are working sessions. GitHub holds the durable project memory.**

Restore the latest repository state before relying on prior conversation context, and reconcile material changes back into the durable records as work progresses.

## Global framework

Current policy release: **1.0.0**, adopted here on 2026-10-19 (DCHAT-DEC-006 through DCHAT-DEC-009).

- [Versioned policies, inheritance, and adoption plan](policies/README.md)
- [Guided Switching](policies/v1.0.0/Guided_Switching.md)
- [Usage Efficiency](policies/v1.0.0/Usage_Efficiency.md)
- [Digest manifest](policies/manifest.json)
- [Project bootstrap template](templates/Project_New_Chat_Bootstrap_Template.md)
- [Execution handoff template](templates/Execution_Handoff_Template.md)
- [Reconciliation template](templates/Reconciliation_Checkpoint_Template.md)
- [Policy pin template](templates/Policy_Pin_Template.md)

Plan in Chat; when design is ready, prepare a handoff and recommend Work/Codex. The user authorizes launch, then execution continues autonomously within the approved batch. These documents guide sessions; they do not automatically change UI modes, project instructions, or other repositories.
