# Research Craft Skill

Research Craft is an agent skill for turning vague research work into a tight loop:
choose better problems, improve inputs, forecast before experiments, keep logs, inspect failures, and publish useful artifacts.

It is based on Vivek's article ["how to be good at research"](https://x.com/itsreallyvivek/article/2064686372737454155).

## Install

Install everywhere the `skills` CLI can target:

```bash
npx -y skills add nik1t7n/research-craft-skill --all
```

Install only for common coding agents:

```bash
npx -y skills add nik1t7n/research-craft-skill \
  -a codex \
  -a claude-code \
  -a gemini-cli \
  -a antigravity \
  -a opencode \
  -a cursor \
  -y
```

Install for one agent:

```bash
npx -y skills add nik1t7n/research-craft-skill -a codex -y
```

The repository is a root skill bundle, so no subpath is required.

## Use

Ask your agent to use `research-craft` when you are:

- choosing a research direction
- designing ML/AI experiments
- reviewing a research plan
- reading papers and building a source list
- tightening an experiment loop
- creating a research log
- analyzing failures or model outputs

## Structure

```text
.
├── SKILL.md
└── agents/openai.yaml
```

No scripts or assets are included because this skill is a compact workflow, not an automation package.

## Compatibility

The skill uses the open `SKILL.md` format and is installable through the `skills` CLI.

Tested targets:

- Codex: `codex`
- Claude Code: `claude-code`
- Gemini CLI: `gemini-cli`
- Antigravity: `antigravity`
- OpenCode: `opencode`
- Cursor: `cursor`
- universal agent directory: `.agents/skills`

## License

MIT
