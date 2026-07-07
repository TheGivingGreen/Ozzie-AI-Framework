# Governance

This repository is maintained as a reusable AI operating framework. Its value comes from portability, clarity, and minimal duplication.

## Admission Test

Before adding or changing anything, ask:

1. Would this help multiple future projects, or define a foundational standard the framework should always carry?
2. Can an agent understand it without private conversation history?
3. Is it a workflow, standard, instruction, playbook, or template rather than implementation?
4. Does it avoid committing to one vendor, model, app stack, or product unless the guidance is explicitly comparative?

If the answer to any question is no, put the material in the target project instead.

## Source Of Truth

Canonical framework rules live at the repository root:

- `OPERATING_SYSTEM.md`
- `AGENT_PROTOCOL.md`
- `GOVERNANCE.md`
- `REPOSITORY_STANDARD.md`

Do not duplicate those rules in adapters. Tool-specific files should point back to the canonical root files.

## Change Types

- `Instruction`: changes how agents should behave.
- `Standard`: defines a durable quality bar.
- `Playbook`: defines a repeatable procedure.
- `Template`: provides a copyable starting artifact.
- `Adapter`: maps canonical instructions into a tool-specific entry point.
- `Governance`: changes how this framework is maintained.

## Review Expectations

Framework changes should be reviewed for:

- Portability across tools and project types
- Clear canonical ownership
- No duplicated durable rules
- No project-specific residue
- No generated artifacts or implementation files

## Deprecation

When a workflow is replaced, keep the old version only if future projects may still need it. Otherwise remove it and identify the replacement in the change notes.
