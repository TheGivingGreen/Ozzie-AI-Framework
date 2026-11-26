# ChatGPT and Codex Coordination

This playbook compares two OpenAI work surfaces. It does not replace the canonical framework rules or grant access to a source.

## Shared record

- GitHub carries the versioned framework and each target project's approved briefs, specialist specifications, task records, and handoffs.
- A ChatGPT conversation, a Codex session, and local files are separate context stores. A shared account or project name alone does not make one session's conversation available to the other.
- Connect the same target repository and identify its branch and commit in each task. Read the target project's instructions and current state from that repository before acting. The framework repository is a reusable source, not the destination for project-specific work.
- Notion may carry institutional memory, but a link or a role specification does not prove a tool can read it. Verify the connector and access in the active session. Put a short source reference and revision in the task record rather than copying whole private pages into the framework.

## Task route

1. ChatGPT clarifies the desired outcome and gathers authorized business context. Save durable decisions in the target project, with sources and status.
2. Codex works from the target repository and its root `AGENTS.md`. Confirm the active branch and the task brief before editing. Use a separate branch or worktree for concurrent changes.
3. When a bounded task benefits from specialists, the coordinating agent delegates within its active surface and collects their results. Codex project agents, when used, belong in the target project's `.codex/agents/`; a specialist description in this framework does not itself create a runnable agent.
4. Return a reviewable artifact, evidence, unresolved issues, and a handoff in the target project. The other surface reads that record and the exact revision. Avoid relying on pasted chat summaries as the sole shared state.

## Pilot acceptance check

Use one target project, one coordinator, and two narrow specialists. Verify that:

- Codex loads the target repository's root instructions in a fresh session.
- The coordinator assigns distinct bounded tasks and receives both results without the human relaying messages.
- Source access is checked in the executing session and specialists stay within the task's project boundary.
- A single task record identifies the input revision, outputs, verification, and next owner.
- The human reviews the final result once; no API integration or separate usage-based billing is assumed for the subscription pilot.

Native subagents coordinate inside a ChatGPT or Codex run. They do not by themselves create an unattended message channel between two separate conversations or between the ChatGPT app and a local Codex CLI session. If that cross-session trigger becomes a requirement, define it separately and measure the cost and access controls before implementation.
