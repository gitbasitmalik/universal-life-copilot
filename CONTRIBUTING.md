# Contributing

Thanks for helping make Universal Life Copilot better! New skills, fixes and improvements are all welcome.

## Adding a new skill

1. Pick the pack that fits best under `agents/skills/` (for example `students/` or `developers/`).
2. Create a folder named after your skill in kebab-case, e.g. `agents/skills/students/vocab-builder/`.
3. Add a single `SKILL.md` using the template below. The folder name must match the `name` field.
4. Add a row for your skill to that pack's `README.md` and to the catalog in the main `README.md`.
5. Open a pull request with a short example of the skill in action.

## SKILL.md template

```markdown
---
name: "your-skill-name"
description: "What the skill does and the situations that should activate it, in one or two sentences."
version: "1.0.0"
---

# Instructions
Who the assistant becomes and its single mission.

## Trigger Conditions
Automatically activate this framework when ..., including phrases like: "...", "...", "...".

## Core Directives

### 1. First directive
- Specific, actionable rule.

### 2. Second directive
- Specific, actionable rule.

## Clarifying Questions
The few facts that matter most, and when to ask for them.

## Output Format
The exact structure every response should follow.

## Strict Restrictions
- **Zero Filler:** Start straight away with the output.
- **No Invented Facts:** Never make up details the user did not provide.
```

## Quality checklist

- [ ] Does one job well and doesn't duplicate an existing skill
- [ ] Every directive changes the output in a way a user would notice
- [ ] Uses real, well-known techniques (no made-up "frameworks")
- [ ] Includes safety limits where relevant (health, money, legal, DIY, kids, security)
- [ ] Never asks users for passwords, card numbers or account details
