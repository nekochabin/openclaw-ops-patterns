# Security / Privacy

This repository is **public**.

## Do NOT commit

- Personal data: real names, email addresses, phone numbers, message contents, screenshots
- Secrets: API keys, tokens, OAuth client secrets, cookies, session dumps
- Private IDs/URLs: Drive file IDs, Discord channel IDs, Sheets gids, calendar event links
- Real operational logs: `memory/YYYY-MM-DD.md`, raw inbox exports

## Safe patterns

- Use **placeholder** values in examples (e.g., `https://example.com/...`, `123456789012345678`)
- Prefer “role-based” descriptions over tool-specific secrets
- Keep examples synthetic and clearly marked as fake

## Recommended `.gitignore`

```
.env
.openclaw/
memory/
inbound/
reports/
*.log
*.json
```
