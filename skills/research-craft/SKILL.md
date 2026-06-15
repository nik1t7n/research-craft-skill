---
name: research-craft
description: >
  Use when planning, reviewing, or improving research work: choosing research
  problems, designing ML/AI experiments, reading papers, building experiment
  loops, analyzing outputs, writing research notes, or turning vague curiosity
  into a disciplined research plan. Based on Vivek's "how to be good at
  research" article.
---

# Research Craft

Use this as a research-quality checklist, not as motivational fluff.

Source: https://x.com/itsreallyvivek/article/2064686372737454155

## Workflow

1. Pick the problem deliberately.
   - Ask what outcome should exist, then reason backward to experiments.
   - Avoid copying fashionable lab directions without knowing why they matter.
   - Prefer problems where the user has taste, pain, or a real reason to care.

2. Upgrade the inputs.
   - Read primary sources, not only summaries or threads.
   - Check appendices, limitations, failed cases, and old foundational work.
   - Pull from neighboring fields when useful: systems, statistics, neuroscience, mechanism design, product reality.

3. Forecast before running.
   - Write the expected result before each experiment.
   - Afterward, compare forecast vs result and update the model of the domain.
   - Treat wrong predictions as training data for taste.

4. Keep a research log.
   - Record: hypothesis, setup, expectation, result, surprise, updated belief, next move.
   - Write down evidence against the favorite theory immediately.
   - If the reasoning feels clear but will not survive writing, it is not clear yet.

5. Tighten the loop.
   - Make each experiment cheap before making it large.
   - For ML work, overfit a tiny batch or minimal case before scaling.
   - Make run, plot, compare, and reproduce operations one-command boring.
   - Treat engineering as part of research, not support work.

6. Stare at outputs.
   - Inspect raw data, transcripts, failures, and weird tails by hand.
   - Bucket a real sample of failures and attack the biggest bucket first.
   - Do not accept a metric improvement until the qualitative behavior makes sense.

7. Wander on purpose.
   - Try disposable versions of ideas first.
   - Tune baselines hard before claiming gains.
   - Ablate until the component carrying the result is known.
   - Spend time in adjacent subfields before overcommitting to one identity.

8. Find people and publish useful artifacts.
   - Share replications, tools, notes, and clear explanations.
   - Float half-formed ideas early enough for correction to still be cheap.
   - Value collaborators who kill weak ideas before they consume months.

## Output Standard

When using this skill, produce one of:

- a research plan with hypotheses, experiments, expected results, and failure-reading plan
- a review of a current research direction with weak assumptions and next tests
- an experiment loop cleanup plan
- a research-log template for the current problem
- a paper/project reading plan that prioritizes primary sources and old foundations

Keep the answer concrete. Name the next experiment, the expected signal, and what would change the belief.
