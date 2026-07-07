# Framework Architecture

This document explains how the repository is organized. Canonical rules live at the repository root.

## Layers

### Canonical Root

The root files are the source of truth:

- `README.md`
- `OPERATING_SYSTEM.md`
- `AGENT_PROTOCOL.md`
- `GOVERNANCE.md`
- `REPOSITORY_STANDARD.md`

### Expanded References

`docs/` contains deeper explanations, standards, and playbooks that support the canonical root files.

Docs may expand on the canonical rules, but they should not replace or contradict them.

### Templates

`templates/` contains copyable project artifacts that get filled in inside target projects.

Templates should remain generic and free of client-specific facts.

### Tool Adapters

Tool-specific folders such as `.agents/`, `.codex/`, `.claude/`, `.cursor/`, and `.gemini/` are thin adapters.

Adapters exist only because some tools look for specific paths. They should point back to root canonical files instead of duplicating durable policy.

## Extension Pattern

When adding a new framework capability:

1. Put durable rules in the appropriate canonical root file.
2. Put detailed procedures or examples under `docs/`.
3. Put fillable artifacts under `templates/`.
4. Add or update a tool adapter only when a tool needs a specific entry point.
5. Keep adapters short and pointer-based.
