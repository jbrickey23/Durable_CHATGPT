# Durable_CHATGPT — Context

## Current authoritative state
- Project: Durable_CHATGPT.
- Repository: `JBrickey23/Durable_CHATGPT`.
- Default branch: `main`.
- Repository is public and currently contains only `README.md`.
- GitHub read/write capability has been verified; repository permissions report `push` and `admin` access.
- Persistent project-state files are being established now.

## Purpose and scope
This repository is the durable source of truth for a GitHub-backed ChatGPT project. ChatGPT conversations are working sessions; durable project state belongs in this repository.

## Repository/system architecture
Current repository structure is minimal:
- `README.md`
- `Durable_CHATGPT_Context.md`
- `Durable_CHATGPT_TODO.md`
- `Durable_CHATGPT_Decision_Log.md`
- `Durable_CHATGPT_New_Chat_Bootstrap_Prompt.md`

No application architecture, source tree, CI/CD workflow, or specialized project records have been established yet.

## Current rules and constraints
- Restore current repository state before relying on prior chat context.
- GitHub is authoritative over stale conversations, memory, and stale bootstrap copies.
- Preserve uncertainty: planned, proposed, approved, implemented, executed, and validated are distinct states.
- Before materially editing an existing file, retrieve its current contents and SHA and reconcile from that version.
- Keep durable records concise and actionable; do not create documentation bureaucracy without a need.

## Current implementation/work state
- Repository inspection completed.
- Read/write capability verified.
- Four durable state files are being initialized.
- No application implementation exists in the repository beyond the existing README.

## Open issues and unresolved state
- The actual long-term project purpose, application scope, architecture, and implementation requirements have not yet been defined beyond the persistence workflow.
- No project-specific completed work, blockers, or deferred implementation scope has been established.

## Immediate continuation point
Begin substantive project definition/work in a future session. First restore the repository state using the bootstrap file, then record meaningful requirements, decisions, and tasks as they become known.

## Restore instructions
Read, in order:
1. `README.md`
2. `Durable_CHATGPT_Context.md`
3. `Durable_CHATGPT_TODO.md`
4. `Durable_CHATGPT_Decision_Log.md`
5. `Durable_CHATGPT_New_Chat_Bootstrap_Prompt.md`
6. Any additional project-specific records required for the immediate task.
