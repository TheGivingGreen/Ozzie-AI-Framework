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

## Always-On Agent Contract

Apply this contract before every task, regardless of tool, model, or project type:

- State important assumptions when they affect the work.
- Surface ambiguity before acting when the wrong assumption would create risk.
- Define or confirm success criteria before substantial execution.
- Choose the simplest path that satisfies the goal.
- Keep changes traceable to the request.
- Use the relevant task route before starting.
- Verify with evidence before calling work complete.
- Report uncertainty, skipped checks, and residual risks plainly.

## Task Routing

Route the task before acting:

- Discovery: clarify intent, constraints, audience, and success criteria.
- Spec: turn rough intent into scope, requirements, acceptance criteria, and open questions.
- Plan: break approved scope into ordered tasks with validation steps.
- Execute: produce or update the requested artifact with minimal drift.
- Review: evaluate artifacts through the relevant review lenses before changing them.
- Validate: test, inspect, proofread, compare, or otherwise gather evidence.
- Git: run the Git safeguard checklist before commits, pushes, branch changes, remote changes, or destructive operations.
- Handoff: summarize artifacts changed, decisions made, validation performed, and next steps.

## Git Safeguard Checklist

Before any Git operation that changes history, branches, remotes, staging, commits, or pushes, confirm:

- Current absolute project path
- Whether the folder is a Git repository
- Current branch and upstream tracking
- Working tree status, including untracked files
- Staged changes, if any
- Latest local commit
- Configured remote names and URLs
- Whether the requested operation affects only the intended repository
- Whether the operation is local-only or will contact a remote
- Explicit user approval for remote changes, pushes, force operations, or destructive cleanup

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
