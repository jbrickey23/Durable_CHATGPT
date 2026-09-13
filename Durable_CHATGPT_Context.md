# Durable_CHATGPT — Context

## Current authoritative state
- Project: `Durable_CHATGPT`.
- Repository: `JBrickey23/Durable_CHATGPT`.
- Default branch: `main`.
- Repository is public and contains `README.md` plus the four core durable-state files listed below.
- GitHub read/write capability has been verified; repository permissions report `push` and `admin` access, and durable-state writes have succeeded.
- The `Durable_CHATGPT` ChatGPT Project has been created and its Project Instructions have been configured to use GitHub as the durable source of truth.

## Purpose and scope
`Durable_CHATGPT` is a learning and sandbox project for becoming familiar with a GitHub-backed durable-state workflow in ChatGPT. Its purpose is to develop practical understanding of how ChatGPT and GitHub can be used together to develop software, ideas, projects, passions, and other ongoing work while keeping durable project truth outside any single conversation.

The primary deliverable is demonstrated understanding and confidence with the workflow: restore project state from GitHub, use ChatGPT as a working session, distinguish transient conversation from durable state, reconcile meaningful changes back to GitHub, and successfully continue the work later or in a fresh chat.

## Repository/system architecture
Current repository structure is minimal:
- `README.md`
- `Durable_CHATGPT_Context.md`
- `Durable_CHATGPT_TODO.md`
- `Durable_CHATGPT_Decision_Log.md`
- `Durable_CHATGPT_New_Chat_Bootstrap_Prompt.md`

No application architecture, source tree, CI/CD workflow, or specialized project records have been established yet. The repository itself is currently the learning vehicle rather than an application product.

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
- `DCHAT-TODO-001` is complete: the project's current purpose and primary deliverable have been defined as learning and demonstrating the durable ChatGPT/GitHub workflow.
- `DCHAT-TODO-002` is complete: the workflow was exercised end-to-end using the Decision Log newest-first ordering change, reconciliation to GitHub, and fresh-chat restoration.
- No substantive application implementation exists or is currently required; the repository is intentionally serving as a workflow-learning sandbox.

## Open issues and unresolved state
- No open durable tasks are currently established.
- No project-specific blockers or deferred implementation scope have been established.

## Immediate continuation point
The initial durable-workflow exercise is complete. Continue by choosing the next useful learning exercise or project task when needed; the next unused durable task ID is `DCHAT-TODO-003`.

## Restore instructions
Read, in order:
1. `README.md`
2. `Durable_CHATGPT_Context.md`
3. `Durable_CHATGPT_TODO.md`
4. `Durable_CHATGPT_Decision_Log.md`
5. `Durable_CHATGPT_New_Chat_Bootstrap_Prompt.md`
6. Any additional project-specific records required for the immediate task.
