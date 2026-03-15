# openclaw-ops-patterns

This repository contains **public, privacy-safe operational patterns and skill templates** for OpenClaw.

- **No personal data** (names, emails, message contents)
- **No secrets** (API keys, tokens)
- **No IDs/URLs** that point to private resources (Drive file IDs, Discord channel IDs, Sheets gids)
- **No real logs** (daily memory files)

日本語：このリポジトリは OpenClaw の運用・自動化を行うための **概念／設計パターン／テンプレ／Skill雛形**を、個人情報を含めずに公開共有するものです。

## Contents

### Included (current)

- **Gmail A1 triage**
  - Template: `templates/gmail_a1_triage.md`
  - Skill skeleton: `skills/gmail-a1-triage/`
- **Google Sheets increment watch** (form responses)
  - Template: `templates/sheets_increment_watch.md`
  - Skill skeleton: `skills/sheets-increment-watch/`
- Patterns
  - `docs/patterns/safety-gate.md`
  - `docs/patterns/memory-to-skill.md`

### Folders

- `docs/patterns/` — operational patterns (privacy, safety gate, monitoring)
- `templates/` — copy-paste templates (sanitized)
- `skills/` — skill skeletons (SKILL.md + examples)

## Quick Start (Concept)

1. Capture raw work privately (not in this repo)
2. Abstract it into a reusable template
3. Package it as a skill (inputs/outputs, procedure, failure handling)
4. Iterate

## Roadmap (ideas)

- Calendar: upcoming events → concise briefing template
- Monitoring patterns: “notify only on change”, debouncing, state files
- Sharing patterns: safe link sharing + permission safety gate
- More skill skeletons (still privacy-safe)

## License

MIT (recommended) — add your preferred license.
