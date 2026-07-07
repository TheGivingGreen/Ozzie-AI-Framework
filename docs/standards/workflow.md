# Workflow Standard

The framework assumes humans and AI agents collaborate through explicit context, small scoped changes, and clear handoffs.

## Default Workflow

1. Read the project brief.
2. Identify the active goal.
3. Inspect existing files before proposing changes.
4. Make the smallest useful change.
5. Verify the result at the right level of risk.
6. Document decisions that future agents need.
7. Hand off with changed files, checks run, and open risks.

## Agent Expectations

Canonical agent behavior lives in `AGENT_PROTOCOL.md`.

Use this workflow standard for sequence and verification, not as a separate behavior policy.

## Verification

Documentation-only changes should be checked by reading the affected docs for:

- Broken navigation
- Contradictory instructions
- Project-specific residue
- Missing ownership or next-step guidance
