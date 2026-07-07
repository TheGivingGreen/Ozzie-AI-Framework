# Operating System

The Ozzie AI Framework is a vendor-neutral operating layer for repeatable human and AI collaboration.

It is designed to be copied into future software, marketing, operations, and creative projects before project-specific work begins.

## Purpose

The framework gives projects a shared way to:

- Define intent before execution
- Coordinate humans and AI agents
- Keep work scoped and reviewable
- Preserve decisions for future collaborators
- Hand off work without relying on private chat history

## Repository Model

This repository contains the operating system itself, not the projects that use it.

Canonical guidance lives at the repository root. Supporting references live in `docs/`. Fillable project artifacts live in `templates/`. Tool-specific folders are adapters only.

## Project Modes

The framework should adapt to the kind of work being done:

- Software: architecture, implementation, tests, documentation, release readiness
- Design: briefs, concepts, critique, design systems, handoff assets
- Marketing: audience, message, channels, campaign assets, measurement
- Creative: direction, references, drafts, revisions, final deliverables
- Operations: workflows, ownership, process documentation, reporting

## Project Lifecycle

1. Start with a project brief.
2. Identify the active goal and constraints.
3. Create a scoped task brief.
4. Inspect existing materials before changing them.
5. Execute the smallest useful change.
6. Verify the work at the right level of risk.
7. Hand off with changed artifacts, validation performed, decisions made, and open risks.

## Operating Principles

- Portability beats tool preference.
- Canonical rules should live once.
- Adapters should point to canonical files instead of restating them.
- Project-specific decisions belong in the project that uses the framework.
- Durable documentation is preferred over hidden process knowledge.
- Implementation belongs in target projects, not in this framework repository.

## Adoption Flow

1. Copy the framework into the target project.
2. Complete `templates/project-brief.md`.
3. Create the first task brief from `templates/agent-task.md`.
4. Give participating agents `README.md`, `OPERATING_SYSTEM.md`, `AGENT_PROTOCOL.md`, `GOVERNANCE.md`, and `REPOSITORY_STANDARD.md`.
5. Use adapters only when an agent tool requires a specific instruction filename or folder.
