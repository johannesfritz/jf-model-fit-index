# JF Model Fit Index

Published results of a personal model benchmark: 15 model arms scored on six classes of real work,
graded mechanically where the deliverable is code and by a blind three-model panel where it is prose.

**[Read the leaderboard](https://johannesfritz.github.io/jf-model-fit-index/)** — the ranked results, the
exact test procedure, and all eleven tasks with per-arm results.

This repository holds the rendered page only. The benchmark itself (the task suite, the full run record,
the runner) lives in a private repository, because the tasks are drawn from real internal work.

## What the numbers mean

Every task is a job actually done in a real repository, defined by the commit before it was done and the
commit that closed it. Agentic tasks are graded by replaying the model's diff against the task's own test
clauses. Document tasks are ranked by a blind panel against a written rubric, with the author's own
committed output included unlabelled as an anchor.

The run's own pre-registered verdict was **objective missed**: the mechanical classes separate the arms,
but only one of the three judged classes discriminates, and both prose classes are *contested* because a
judge ranked its own vendor family top. The leaderboard therefore offers two scorings, one using every
judge and one dropping each arm's own-vendor judge.
