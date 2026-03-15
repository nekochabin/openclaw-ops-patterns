# Safety Gate Pattern (Send/Delete/Permissions/Payments)

## Goal
Prevent irreversible or externally visible actions from happening without a deliberate final confirmation.

## Applies to
- Sending messages/emails/DMs
- Deleting items (files, messages)
- Changing permissions or sharing links
- Purchases / paid API calls / subscriptions
- Updates / upgrades that can impact uptime

## Pattern
1. Draft the action and show exactly what will happen
2. Ask a **binary final confirmation**: `Yes/No`
3. Only execute after explicit `Yes`

## Example confirmation prompt

- What I will do:
  - Send X to Y
  - Attach file Z
- Final confirmation:
  - “Proceed? (Yes/No)”

## Notes
- If multiple actions exist, confirm them as a single batch when safe.
- If the target is ambiguous, do not proceed—ask to clarify.
