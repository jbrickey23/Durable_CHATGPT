# Durable_CHATGPT — Decision Log

## DCHAT-DEC-001 — GitHub is durable project authority
- **Status:** CURRENT
- **Decision:** Use `JBrickey23/Durable_CHATGPT` as the durable source of truth for project-controlled state; ChatGPT conversations are working sessions.
- **Rationale:** The project is intended to survive long conversations, context limits, and transfers between chats.
- **Consequence:** Material project state must be reconciled into repository records rather than relying on chat history or memory alone.

## DCHAT-DEC-002 — Core durable state files
- **Status:** CURRENT
- **Decision:** Maintain Context, TODO, Decision Log, and New Chat Bootstrap files in the repository root.
- **Rationale:** These provide current state, unfinished work, durable decisions, and fresh-chat restoration instructions.
- **Consequence:** Future substantive sessions should restore and reconcile these records before continuing work.

## DCHAT-DEC-003 — Minimal repository structure
- **Status:** CURRENT
- **Decision:** Preserve the existing minimal repository and add durable state without unnecessary reorganization.
- **Rationale:** The repository currently contains only a README and has no application architecture or established workflow to reorganize.
- **Consequence:** Additional structure will be introduced only when actual project needs justify it.
