# Durable_CHATGPT

GitHub-backed durable project state for the `Durable_CHATGPT` ChatGPT Project.

## Durable state

- [Context](Durable_CHATGPT_Context.md) — current authoritative project state
- [TODO](Durable_CHATGPT_TODO.md) — unfinished, blocked, waiting, and deferred work
- [Decision Log](Durable_CHATGPT_Decision_Log.md) — durable project decisions
- [New Chat Bootstrap](Durable_CHATGPT_New_Chat_Bootstrap_Prompt.md) — restore instructions for a fresh ChatGPT conversation

## Operating model

**ChatGPT conversations are working sessions. GitHub holds the durable project memory.**

Restore the latest repository state before relying on prior conversation context, and reconcile material changes back into the durable records as work progresses.
