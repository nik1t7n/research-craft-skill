---
name: research-craft
description: >
  Use when planning, reviewing, or improving research work: choosing research
  problems, designing ML/AI experiments, reading papers, building experiment
  loops, analyzing outputs, writing research notes, or turning vague curiosity
  into a disciplined research plan. Emphasizes avoiding absorbed problems,
  upgrading information inputs beyond shared reading lists, and reasoning
  backward from outcomes the researcher genuinely wants to exist.
---

# Research Craft

Use this as a research-quality checklist, not as motivational prose.

Source: https://x.com/itsreallyvivek/article/2064686372737454155

## Core Bias

The default failure mode is looking like a researcher instead of doing research.
Do not optimize for paper-shaped activity, trending topics, or impressive jargon.
Optimize for choosing better problems, getting better inputs, learning faster
from reality, and writing down the reasoning before memory edits it.

Two mistakes deserve special pressure:

1. Absorbed problems.
   - Common mistake: inheriting a problem from an advisor, a famous lab, a viral paper, or a group chat without owning the reasoning.
   - Why it fails: the researcher copies the conclusion but not the causal model. They do not know why the direction matters, what evidence would weaken it, or what would make the original lab abandon it.
   - Cost: fashionable problems are crowded, often compute-heavy, and usually already ahead of the independent researcher.

2. Shared inputs.
   - Common mistake: reading the same arXiv trends, summaries, and social threads as everyone else.
   - Why it fails: shared reading lists produce shared ideas at the same time, which makes the resulting insight low-value.
   - Cost: the agent produces consensus-shaped plans instead of original research paths.

## Workflow

1. Choose the problem instead of absorbing it.
   - Ask what outcome should exist in the world.
   - Reason backward from that outcome to the experiments that would make it real.
   - Name the user's stake: taste, pain, curiosity, product need, scientific confusion, or practical bottleneck.
   - Reject a direction if the only reason for it is "a big lab is working on it" or "it is trending."
   - Before accepting a borrowed problem, reconstruct the reasoning:
     - Why does this direction matter?
     - What result would make it exciting?
     - What result would make it dead?
     - What hidden assumptions does the direction depend on?
     - Why is this user positioned to learn something non-obvious here?

2. Upgrade the inputs before planning.
   - Read the primary source before relying on a thread, abstract, benchmark table, or summary.
   - Inspect appendices, limitations, experimental details, negative results, and baseline choices.
   - Include old foundational material. Older work is often underpriced because the field repeatedly rediscovers old patterns under new names.
   - Prefer source diversity over volume:
     - old papers and lectures
     - adjacent fields
     - systems constraints
     - statistics and measurement
     - raw data and failure examples
     - product or user reality
   - In ML/AI, explicitly check whether the idea depends on compute, memory movement, data quality, benchmark design, or statistical noise.
   - Treat summaries as navigation, not evidence.

3. Use range as a research tool.
   - Pull from neighboring fields when the current field is saturated.
   - For interpretability, consider neuroscience and cognitive science analogies carefully.
   - For evals, consider incentives, mechanism design, measurement design, and adversarial behavior.
   - For architecture work, consider hardware and memory constraints before trusting benchmark wins.
   - For claims of rigor, check whether the statistics actually support the conclusion.

4. Forecast before running.
   - Write the expected result before each experiment.
   - If reading a paper, predict the result from the method before looking at the results section.
   - Afterward, compare forecast vs result and update the user's model of the domain.
   - Treat wrong predictions as training data for taste, not as embarrassment.

5. Keep a research log.
   - Record: hypothesis, setup, expectation, result, surprise, updated belief, next move.
   - Write down evidence against the favorite theory immediately.
   - Explain the idea in words before assuming it is understood.
   - If the written version exposes a missing step, fix the reasoning before adding experiments.

6. Tighten the loop.
   - Make each experiment cheap before making it large.
   - For ML work, overfit a tiny batch or minimal case before scaling.
   - Make run, plot, compare, and reproduce operations one-command boring.
   - Treat engineering as research infrastructure. The person who can build the harness, eval, and data pipeline gets more hypotheses tested.

7. Stare at outputs.
   - Do not accept a descending loss curve or better score as analysis.
   - Inspect raw data, transcripts, failures, and weird tails by hand.
   - Bucket a real sample of failures and attack the biggest bucket first.
   - Do not trust a benchmark until the user has read enough transcripts or examples to know what it measures.

8. Wander on purpose.
   - Try disposable versions of ideas first and let weak ideas die early.
   - Tune baselines hard before claiming gains.
   - Ablate until the component carrying the result is known.
   - Spend time in adjacent subfields before overcommitting to one identity.
   - Use breadth as insurance against saturated subfields.

9. Find people and publish useful artifacts.
   - Share replications, tools, notes, and clear explanations.
   - Float half-formed ideas early enough for correction to still be cheap.
   - Value collaborators who kill weak ideas before they consume months.
   - Treat public writing as both contribution and proof of thought quality.

## Output Standard

When using this skill, produce one of:

- a research plan with the desired outcome, problem rationale, hypotheses, experiments, expected results, and failure-reading plan
- a critique of a research direction that separates owned reasoning from absorbed reasoning
- an input-upgrade plan with primary sources, old foundations, adjacent fields, and concrete artifacts to inspect
- an experiment loop cleanup plan
- a research-log template for the current problem
- a paper/project reading plan that prioritizes primary sources, appendices, limitations, and old foundations

Always include:

- the chosen outcome
- why this problem is not merely copied from the trend cycle
- what inputs must be upgraded before trusting the plan
- the next experiment or reading action
- what result would change the belief

Keep the answer concrete. If the user asks for a research plan and the problem is absorbed, say so and force the reasoning step before planning experiments.
