# Ozzie AI Framework

Vendor-neutral AI operating framework for reusable software, marketing, and creative project workflows.

This repository is not an application. It contains canonical operating instructions, expanded references, and copyable project artifacts.

It governs both code and non-code deliverables, including software, design, marketing, operations, and creative work.

## Canonical Files

Read these first. They are the source of truth.

- `OPERATING_SYSTEM.md`: purpose, model, lifecycle, and adoption flow
- `AGENT_PROTOCOL.md`: vendor-neutral behavior expected from AI agents
- `GOVERNANCE.md`: what belongs here and how the framework changes
- `REPOSITORY_STANDARD.md`: repository hygiene and forbidden artifacts

## Supporting References

- `docs/`: expanded standards, architecture notes, and playbooks
- `templates/`: copyable project artifacts
- `.agents/`, `.codex/`, `.claude/`, `.cursor/`, and `.gemini/`: tool-specific adapters that point back to canonical files

## Use

1. Copy the framework into a new project.
2. Fill out `templates/project-brief.md` in that project.
3. Give agents the canonical root files as their operating context.
4. Use tool-specific adapters only when a tool expects a particular file path.

See `REPOSITORY_STANDARD.md` for what must stay out of this framework repository.
