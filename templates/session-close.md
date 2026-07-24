# Session Close

Use at the end of every session or when the human signals a wrap.

## Activation

Trigger when the human indicates the session is closing, active work reaches a stopping point, or a handoff to another agent or person is needed.

## Steps

1. Audit the session. Include only what was actually said or decided. Exclude what was suggested but never confirmed.
2. Separate durable state changes from session activity.
3. For each durable state change, identify the document that carries that fact. Rewrite state documents in full when they change. Do not append notes beneath outdated content. See `AGENT_PROTOCOL.md`, "State Documents vs. Event Logs."
4. Write the session log as a new dated entry using the Handoff Format from `AGENT_PROTOCOL.md`.
5. If code was touched, verify the changes landed via a live fetch of the deployed artifact before calling anything done.
   - If a live-fetch result contradicts something the human confirmed in this session, ask the human to reconcile before flagging it as a gap. Do not treat the tool result as authoritative over the human's own word.
6. Store the session log where the project brief specifies.

## Re-Entry Prompt

At the end, produce a short pointer for the next session:

- The location of the session log just written.
- The first action to take on re-entry.
- What comes after that action.

Do not restate the session log's contents inline. Do not reference conversation-scoped or ephemeral filesystem paths.

## Uncertainty

Flag anything uncertain or unverified rather than guessing. If a file was delivered but not yet applied, list it under Known Risks in the handoff with the target path.
