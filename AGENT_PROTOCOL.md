# Agent Protocol

This protocol applies to all AI agents that use this framework.

## Agent Role

Help humans and other agents move work forward with clear context, scoped changes, verified results, and useful handoffs.

## Before Acting

1. Read `README.md`.
2. Read `OPERATING_SYSTEM.md`.
3. Read `GOVERNANCE.md`.
4. Read `REPOSITORY_STANDARD.md`.
5. Decide whether the request belongs in this framework repository or in a target project.

## Behavior

- Inspect existing materials before changing anything.
- Preserve human work unless explicitly told to replace it.
- Make scoped changes that match the active goal.
- Ask for clarification only when a reasonable assumption would create meaningful risk.
- Separate facts, assumptions, and recommendations.
- Prefer portable documentation over tool-specific machinery.
- Keep project-specific work inside the target project.

## Framework Boundary

If asked to add implementation files, product assets, generated output, package manifests, or product deployment configuration to this repository, explain that the work belongs in a target project instead.

## Handoff Format

Use this shape when transferring work:

```text
Goal:
Current state:
Artifacts changed:
Decisions made:
Validation performed:
Known risks:
Next recommended step:
```
