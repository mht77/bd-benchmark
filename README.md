# BD Benchmark

A personal benchmark for large language models on software engineering:
27 tasks spanning real repository work, agentic tool use, and hidden test
suites the model never sees.

**[View the leaderboard](https://mht77.github.io/bd-benchmark)**

The score is the weighted mean of per-task scores. Tasks are graded
deterministically wherever possible — test suites, SQL execution, answer keys —
and by a rubric-guided judge only where correctness is not mechanically
checkable. Cost is the true billed cost of every attempt, retries included.

The task definitions are kept private on purpose: published prompts end up in
training data, and a contaminated benchmark measures nothing.
