# Contributing

Keep the skill small and practical.

## Guidelines

- Put core instructions in `skills/research-craft/SKILL.md`.
- Add `references/` only when the content is too long for `SKILL.md`.
- Do not add scripts unless a repeated command needs deterministic execution.
- Prefer concrete research workflows over motivational prose.
- Keep frontmatter limited to `name` and `description`.

## Checks

Before opening a PR:

```bash
find skills -name SKILL.md -print
skills add . --skill research-craft --copy -y
```
