# {{PROJECT}} — Execution Handoff

Template compatibility: Durable_CHATGPT policies 1.0.0.

- Repository / branch: {{OWNER_REPOSITORY_AND_BRANCH}}
- Restore from: {{CORE_RECORD_PATHS_AND_POLICY_PIN}}
- Prepared against revision: {{BASE_COMMIT_SHA}}
- Design ready: {{APPROVED_DECISIONS_AND_NONBLOCKING_UNCERTAINTIES}}
- Outcome / task IDs: {{BATCH_OUTCOME_AND_TASK_IDS}}
- Included work: {{IN_SCOPE}}
- Exclusions: {{OUT_OF_SCOPE_REPOSITORIES_RESOURCES_DEPLOYMENTS_AND_OTHER_LIMITS}}
- Acceptance checks: {{OBSERVABLE_CHECKS}}
- Model/reasoning recommendation and reason: {{LOWEST_CAPABLE_SETTING}}
- Launch/session step, if required: {{ACTUAL_INTERFACE_ACTION_OR_NONE}}
- Authorization: {{USER_APPROVAL_REFERENCE_OR_PENDING}}

If authorization is pending, present this handoff and wait for launch approval. Once approved, restore current state and reconcile any drift from the prepared revision. Execute related work autonomously, validate, commit, verify writes, and update durable records. Do not treat stale handoff text as authority to overwrite newer state. Do not renew approval for routine steps already covered by this batch.

Checkpoint at meaningful milestones and continue within scope. After two unsuccessful attempts on the same blocker, change approach. Stop for completion, material decisions outside scope, blockers, or unjustified further usage. Preserve a concrete continuation point and return results, commit reference, validation, and unresolved decisions to planning.
