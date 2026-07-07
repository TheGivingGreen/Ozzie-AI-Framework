# Workflow Standard

The framework assumes humans and AI agents collaborate through explicit context, small scoped changes, and clear handoffs.

## Default Workflow

1. Read the project brief.
2. Identify the active goal.
3. Route the task using `AGENT_PROTOCOL.md`.
4. Create or confirm the spec, acceptance criteria, and validation plan.
5. Inspect existing materials before proposing changes.
6. Make the smallest useful change.
7. Verify the result at the right level of risk.
8. Document decisions that future agents need.
9. Hand off with changed artifacts, validation performed, and open risks.

## Phase Flow

Use this phase flow for substantial work:

1. Discuss: clarify intent, constraints, audience, and success criteria.
2. Spec: define scope, requirements, acceptance criteria, and open questions.
3. Plan: break the approved scope into task briefs with validation steps.
4. Execute: produce or revise artifacts within scope.
5. Verify: gather evidence that the work satisfies the acceptance criteria.
6. Ship or hand off: prepare the artifact for review, publication, delivery, or continued work.

## Agent Expectations

Canonical agent behavior lives in `AGENT_PROTOCOL.md`.

Use this workflow standard for sequence and verification, not as a separate behavior policy.

## Verification

Documentation-only changes should be checked by reading the affected docs for:

- Broken navigation
- Contradictory instructions
- Project-specific residue
- Missing ownership or next-step guidance
