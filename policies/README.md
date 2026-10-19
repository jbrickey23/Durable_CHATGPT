# Versioned global policies

Current release: **1.0.0** (2026-10-19).

| Policy | File |
| --- | --- |
| DCHAT-POL-001 | [Guided Switching](v1.0.0/Guided_Switching.md) |
| DCHAT-POL-002 | [Usage Efficiency](v1.0.0/Usage_Efficiency.md) |

## Distribution and inheritance

Released version directories are immutable. Publish changes under a new version; use major versions for incompatible behavior, minor versions for compatible additions, and patch versions for clarifications. Update this index, [manifest](manifest.json), templates, and core durable records together. Keep prior versions so projects can restore their adopted policy.

For a project adoption, copy the two policy files into that repository's `policies/v1.0.0/` (or its established equivalent). Fill in [the policy pin](../templates/Policy_Pin_Template.md) using the full source commit SHA and file SHA-256 digests from the manifest. Record the local paths, adoption decision, and any approved exceptions. Link the pin from the project's Context and Bootstrap. A URL to moving `main` alone is not a version pin.

The source commit is the commit containing the released files, obtained after publication with `git rev-parse HEAD` or GitHub's commit record. It is intentionally not embedded in its own release manifest. Verify each source file against the manifest at that commit before copying it.

Global policy intent applies across projects; copying and reconciling a project's records is a separate authorized adoption batch. Existing repositories retain their recorded version until deliberately upgraded. Compare versions, preserve local conventions and exceptions, validate the change, record the decision, update the pin and bootstrap, and commit. Never bulk-overwrite project state. If a policy is unavailable, use the verified local pinned copy and report the limitation; do not silently use a different version.

## Templates and compatibility

Templates shipped in this commit target policy version 1.0.0. Replace every `{{PLACEHOLDER}}` before use. Preserve existing project filenames and record structure. Templates supply missing workflow sections; they do not require renaming existing records. These files are prompts and documentation, not an automatic session launcher or enforcement service.

- [Project bootstrap](../templates/Project_New_Chat_Bootstrap_Template.md)
- [Execution handoff](../templates/Execution_Handoff_Template.md)
- [Reconciliation checkpoint](../templates/Reconciliation_Checkpoint_Template.md)
- [Policy pin](../templates/Policy_Pin_Template.md)

## Adoption plan

1. `Durable_CHATGPT` adopts 1.0.0 in this implementation.
2. `Cookie_Catalog` is the first downstream adoption candidate. In a separately authorized batch, inspect its current records and conventions, pin/copy the policies, integrate bootstrap/handoff/checkpoint sections, validate, and commit. Keep feature implementation and releases under its own approvals.
3. Adopt other repositories individually when authorized; track adoption in their own durable records.

No downstream repository has been modified or claimed adopted by this release. No deployment, paid resource, or external instruction-setting update is part of publication.
