# Sheets Increment Watch Template (privacy-safe)

## Goal
Detect new form responses by counting non-empty rows in a key column (e.g., column A), and notify only on increase.

## State
Maintain a local state file:

- `nonEmptyA`: last seen count
- `updatedAt`: ISO timestamp

## Notification (copy/paste)

**新規回答がありました**
- 増分：+N
- 最新行（要約）：（ここに要約）

## Notes
- Keep sheet URLs / gids out of public repos.
- Use placeholder examples only.
