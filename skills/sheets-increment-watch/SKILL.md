# Skill: sheets-increment-watch (skeleton)

## Purpose
Monitor a Google Sheets tab (e.g., form responses) by exporting CSV and detecting new entries.

## Inputs
- `csv_export_url` (string) — keep private if it contains sensitive IDs
- `key_column_index` (int, default 0) — usually column A
- `state_path` (string) — local file path (not in public repo)

## Output
- If increased: a short alert + summary of new rows
- If not increased: either silent (NO_REPLY) or “no changes” depending on policy

## Procedure
1. Fetch CSV
2. Count non-empty cells in key column
3. Compare with state
4. If delta>0: parse and summarize new rows
5. Update state atomically

## Failure modes
- Fetch blocked/auth required → fall back to manual check
- CSV schema changed → detect header mismatch and alert

## Examples
See `examples/` (synthetic only).
