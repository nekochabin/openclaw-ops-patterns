# Context Files Pattern (about-me / voice / current-projects)

## Goal
Make an agent consistently useful by providing stable, reusable context as files.

This pattern is inspired by the idea that **setup beats prompting**: once the agent can read a small set of “who I am / how I work / what matters right now” files, daily work becomes faster and more consistent.

## Recommended files

### 1) `about-me.md`
Professional identity + constraints.

Include:
- Role/title, main responsibilities
- Timezone + working hours
- Preferred communication style (short/structured, etc.)
- Decision rules (when to ask, when to proceed)

### 2) `brand-voice.md`
Writing style constraints (for content creation).

Include:
- Tone (formal/casual), target audience
- Words/phrases to use vs avoid
- Example sentences (3–10)
- Topics you do / don’t cover

### 3) `current-projects.md`
“Working memory” of what matters this week.

Include:
- Active projects with status
- Key deadlines in the next 7 days
- Blockers / open questions
- Links (keep private in public repos)

## Update cadence
- `about-me.md`: rarely (monthly/quarterly)
- `brand-voice.md`: occasionally (when you refine tone)
- `current-projects.md`: weekly

## Privacy note
If you publish patterns publicly, keep these files **template-only** with synthetic examples. Do not include real names, emails, links, or client data.
