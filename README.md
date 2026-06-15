# Research Craft Skill

Research Craft is an agent skill for turning vague research work into a tight loop:
choose better problems, improve inputs, forecast before experiments, keep logs, inspect failures, and publish useful artifacts.

It is based on Vivek's article ["how to be good at research"](https://x.com/itsreallyvivek/article/2064686372737454155).

## Install

```bash
skills add nik1t7n/research-craft-skill/skills/research-craft
```

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
skills/research-craft/
├── SKILL.md
└── agents/openai.yaml
```

No scripts or assets are included because this skill is a compact workflow, not an automation package.

## License

MIT
