# Durable_CHATGPT — Decision Log
Decisions are captured newest first

## DCHAT-DEC-009 — Versioned policy inheritance and explicit adoption
- **Status:** CURRENT
- **Date:** 2026-10-19
- **Decision:** Publish immutable versioned policies with a digest manifest; projects pin a source commit/version and retain verified local copies plus approved exceptions.
- **Consequence:** Upgrades are deliberate per-project reconciliation batches. Cookie_Catalog is the first downstream adoption candidate; this implementation does not modify it or other repositories.

## DCHAT-DEC-008 — Usage efficiency within approved batches
- **Status:** CURRENT
- **Date:** 2026-10-19
- **Decision:** Batch related approved work, continue productive verified execution without artificial caps, checkpoint at meaningful milestones, reuse durable state, and minimize redundant reads and checks. Change approach after two unsuccessful attempts on one blocker.
- **Consequence:** Use the lowest capable model/reasoning (Light/lite for straightforward work, usually Medium for technical work, High/Extra High when warranted). Validate proportionately and stop for material decisions, blockers, completion, or unjustified usage. See DCHAT-POL-002 v1.0.0.

## DCHAT-DEC-007 — Global Guided Switching (Option B)
- **Status:** CURRENT
- **Date:** 2026-10-19
- **Decision:** Plan in ordinary Chat; proactively identify when design is ready, prepare a concrete handoff, recommend Work/Codex execution, and let the user authorize launch. Execute the approved batch autonomously through validation, commit, and reconciliation.
- **Consequence:** Do not repeatedly request authorization for routine steps inside an approved batch or claim automatic session switching. Preserve explicit exclusions and stop conditions. See DCHAT-POL-001 v1.0.0.

## DCHAT-DEC-006 — One global framework, independent project repositories
- **Status:** CURRENT
- **Date:** 2026-10-19
- **Decision:** Evolve Durable_CHATGPT from its initial learning sandbox into the single shared durable-workflow framework. Preserve its learning history and core conventions. Each project retains independent state and can use many planning chats and replaceable execution sessions.
- **Consequence:** This repository owns shared policies/templates, not downstream implementation or a centralized copy of all project state. Supersedes the purpose restriction of DCHAT-DEC-004; DCHAT-DEC-001/002/003/005 remain current. The small policies/templates directories are justified by distribution needs.


## DCHAT-DEC-005 — Naming consistency is an operating principle
- **Status:** CURRENT
- **Decision:** Maintain canonical naming consistently across durable state, ChatGPT working sessions, files, components, tasks, and commands. Informal aliases and descriptive domain labels must resolve to an existing canonical name and must not silently establish a new canonical name.
- **Rationale:** Inconsistent names create ambiguity about whether references identify the same project/component or a different one, weakening restoration and durable-state reliability.
- **Consequence:** Use established canonical names by default. If a user uses an informal or alternate name, map it to the canonical name unless an explicit rename is requested. Renames should be intentional and reconciled across affected durable records.

## DCHAT-DEC-004 — Project is a durable-workflow learning sandbox
- **Status:** SUPERSEDED in purpose by DCHAT-DEC-006; learning history retained
- **Decision:** Use `Durable_CHATGPT` primarily to learn, practice, and demonstrate a GitHub-backed durable-state workflow with ChatGPT, rather than treating creation of an application as the current objective.
- **Rationale:** The present goal is to become comfortable using ChatGPT and GitHub together for software, ideas, projects, passions, and other ongoing work.
- **Consequence:** Success is measured by demonstrated ability to restore state, work in disposable ChatGPT sessions, identify durable information, reconcile it to GitHub, and continue accurately in later or fresh conversations. New application structure should be added only when a learning exercise or future project actually requires it.

## DCHAT-DEC-003 — Minimal repository structure
- **Status:** CURRENT
- **Decision:** Preserve the existing minimal repository and add durable state without unnecessary reorganization.
- **Rationale:** The repository currently contains only a README and has no application architecture or established workflow to reorganize.
- **Consequence:** Additional structure will be introduced only when actual project needs justify it.

## DCHAT-DEC-002 — Core durable state files
- **Status:** CURRENT
- **Decision:** Maintain Context, TODO, Decision Log, and New Chat Bootstrap files in the repository root.
- **Rationale:** These provide current state, unfinished work, durable decisions, and fresh-chat restoration instructions.
- **Consequence:** Future substantive sessions should restore and reconcile these records before continuing work.

## DCHAT-DEC-001 — GitHub is durable project authority
- **Status:** CURRENT
- **Decision:** Use `JBrickey23/Durable_CHATGPT` as the durable source of truth for project-controlled state; ChatGPT conversations are working sessions.
- **Rationale:** The project is intended to survive long conversations, context limits, and transfers between chats.
- **Consequence:** Material project state must be reconciled into repository records rather than relying on chat history or memory alone.

