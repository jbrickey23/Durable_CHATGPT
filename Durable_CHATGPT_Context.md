# Durable_CHATGPT — Context

## Current authoritative state
- Project: `Durable_CHATGPT`; repository: `JBrickey23/Durable_CHATGPT`; default branch: `main`; public.
- GitHub is durable project authority. Current evidence and specialized authoritative records take precedence over summaries, bootstrap copies, and old conversation/memory.
- Four root durable records, canonical names, stable DCHAT task IDs, and newest-first decisions are preserved.
- The ChatGPT Project was previously configured for GitHub-backed state; this batch does not change external Project Instructions.

## Purpose and scope
One global framework defines shared durable-workflow policies and bootstrap/handoff/reconciliation templates. Each adopting repository remains independent and owns its implementation, evidence, decisions, tasks, releases, and authorizations. Many planning chats and replaceable execution sessions can work from the same project records. The original learning exercises remain completed history.

## Repository/system architecture
- Root: README and the four existing Context/TODO/Decision Log/New Chat Bootstrap records.
- `policies/README.md`: distribution, versioning, exceptions, upgrade procedure, and adoption plan.
- `policies/v1.0.0/`: Guided Switching (DCHAT-POL-001) and Usage Efficiency (DCHAT-POL-002).
- `policies/manifest.json`: release metadata and SHA-256 policy digests.
- `templates/`: project bootstrap, execution handoff, reconciliation checkpoint, and policy pin.
- No application code, deployment, paid infrastructure, or CI service is introduced.

## Current rules and constraints
- Restore current repository state before relying on prior chat context. Read current contents and SHAs before editing, preserve unrelated changes, and verify writes.
- Maintain naming consistency, newest-first decisions, and stable task IDs. Proposed, approved, implemented, executed, and validated are distinct states.
- Plan in ordinary Chat. Proactively recommend execution when design is ready, prepare the handoff, and obtain launch authorization. Continue already authorized batches autonomously.
- Stop for completion, material decisions, blockers, or unjustified usage. Checkpoint at meaningful milestones; change approach after two unsuccessful attempts on one blocker.
- Reuse current evidence and use proportionate validation and the lowest capable reasoning. Keep durable records concise.
- Adopted policies: 1.0.0, paths above, DCHAT-DEC-006 through DCHAT-DEC-009, no local exceptions. This source repository uses its released files; downstream projects pin the published commit and local copies via the policy pin template.
- Do not modify other repositories or create paid resources under this implementation authorization.

## Current implementation/work state
- Initial setup, purpose-definition, and first restore/reconcile exercise remain complete (DCHAT-TODO-001/002).
- DCHAT-TODO-003 implements the approved 2026-10-19 global framework: versioned policies, digest manifest, four templates, inheritance/upgrade/adoption procedure, and reconciled core records.
- Local validation: policy digests, Markdown relative links, template placeholder resolution in a sample adoption, decision/task ordering, required workflow content, and whitespace checks. Publication requires a commit and verified remote readback; use Git history for the resulting commit and the completion report for publication evidence.

## Open issues and unresolved state
- DCHAT-TODO-004: downstream adoption beginning with Cookie_Catalog, awaiting a separately authorized adoption batch. No downstream adoption is claimed.
- No implementation blocker remains in this repository.

## Immediate continuation point
Verify the framework publication in Git history if resuming before its completion report. Then prepare the Cookie_Catalog adoption batch from its current repository state when authorized. Do not repeat framework initialization or begin feature implementation. Next unused task ID: `DCHAT-TODO-005`.

## Restore instructions
Read README, Context, TODO, Decision Log, New Chat Bootstrap, the policy index and adopted policy files, then only specialized records needed for the immediate task.
