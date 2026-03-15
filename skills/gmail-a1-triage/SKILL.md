# Skill: gmail-a1-triage (skeleton)

## Purpose
Turn a (private) Gmail message into an **A1 triage output**:
- conclusion in 30 seconds
- next 1–3 actions
- open questions
- reply draft

## Inputs
- `email_subject` (string)
- `email_from` (string, optional)
- `email_received_at` (string, optional)
- `email_body` (string) — **private** (do not publish)

## Output
A1 formatted block.

## Procedure
1. Identify intent + urgency
2. Extract hard constraints: deadlines, requested deliverables, dates
3. Convert to 1–3 concrete actions
4. List uncertainties
5. Draft a short reply

## Failure modes
- Missing dates/attachments → ask for confirmation
- Ambiguous request → propose 2 options

## Examples
See `examples/` (synthetic only).
