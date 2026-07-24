# Session Open

Use at the start of every session before the agent acts on any project work.

## Activation

Trigger when a new session begins, a fresh agent instance loads, or the human opens the project after time away.

## Steps

1. Confirm the workspace, repository, or connected source matches the intended project. If identity cannot be verified, state that plainly and stop.
2. Load the framework canonical files at the root of this repo if not already loaded in this session: `OPERATING_SYSTEM.md`, `AGENT_PROTOCOL.md`, `GOVERNANCE.md`, `REPOSITORY_STANDARD.md`.
3. Read the target project's brief. See the project's `project-brief.md`.
4. Read the target project's most recent session log. The project brief identifies where session logs live for that project.
5. Confirm the current request belongs in this framework repository or in a target project before proceeding.

## Output

State the loaded context in one line before beginning work. Do not restate the full brief or session log inline.

## Uncertainty

If any step cannot be completed, name what is missing and ask the human before continuing.
