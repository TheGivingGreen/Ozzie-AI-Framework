# Review Checklist

Use this before merging framework changes or copying the framework into another project.

## Framework Review

- The repo contains no application code.
- New guidance applies across multiple future projects.
- Instructions are understandable without private context.
- Terminology is consistent with the README.
- Navigation is updated.
- Generated artifacts are absent.

## Review Lenses

Use the lenses that match the work:

- Strategy: the work supports the real goal and avoids unnecessary scope.
- Audience or user: the artifact makes sense for the people it serves.
- Design: the experience, structure, visuals, or composition are coherent and polished.
- Technical: the implementation, architecture, data, or process is sound.
- QA: the artifact has been tested, proofread, inspected, or exercised realistically.
- Risk and security: likely failures, misuse, privacy, safety, compliance, and operational risks are considered.
- Documentation: future humans and agents can understand what changed and why.
- Release or publishing: the artifact is ready for its intended handoff, launch, or distribution path.

## Git Safeguard Review

Before Git operations that stage, commit, push, change branches, change remotes, or clean files, confirm:

- Current absolute project path
- Current branch and upstream
- Working tree status
- Untracked files
- Staged changes
- Latest local commit
- Remote URLs
- Whether the operation is local-only or remote-affecting
- User approval for remote, destructive, or history-changing actions

## Project Adoption Review

- The target project has a completed project brief.
- Framework files were copied intentionally.
- Project-specific instructions live in the target project.
- Any deviations from framework standards are documented.
- Handoff notes exist for the next agent or human.
