# Durable_CHATGPT — Context

## Current authoritative state
- Project: `Durable_CHATGPT`.
- Repository: `JBrickey23/Durable_CHATGPT`.
- Default branch: `main`.
- Repository is public and contains `README.md` plus the four core durable-state files listed below.
- GitHub read/write capability has been verified; repository permissions report `push` and `admin` access, and durable-state writes have succeeded.
- The `Durable_CHATGPT` ChatGPT Project has been created and its Project Instructions have been configured to use GitHub as the durable source of truth.

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
- Record important decisions in the Decision Log and unfinished actionable work in TODO using durable task IDs.
- Verify important GitHub writes after making them.

## Current implementation/work state
- Repository inspection completed.
- GitHub read/write capability verified.
- Four core durable-state files initialized and verified.
- ChatGPT Project Instructions configured for `Durable_CHATGPT`.
- Durable initialization is complete enough for normal use and fresh-chat restoration.
- No substantive application implementation exists; the repository currently provides the persistence/durable-state workflow only.

## Open issues and unresolved state
- `DCHAT-TODO-001` remains open: the actual long-term project purpose, application scope, architecture, requirements, and first substantive deliverable have not yet been defined beyond the persistence workflow.
- No project-specific blockers, deferred implementation scope, or substantive completed deliverables have been established.

## Immediate continuation point
Define the project's substantive purpose, scope, requirements, and first deliverable. Do not assume what the project should build. Record resulting decisions and actionable work in the durable records.

## Restore instructions
Read, in order:
1. `README.md`
2. `Durable_CHATGPT_Context.md`
3. `Durable_CHATGPT_TODO.md`
4. `Durable_CHATGPT_Decision_Log.md`
5. `Durable_CHATGPT_New_Chat_Bootstrap_Prompt.md`
6. Any additional project-specific records required for the immediate task.
