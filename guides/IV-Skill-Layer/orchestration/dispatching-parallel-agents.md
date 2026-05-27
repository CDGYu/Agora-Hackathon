# dispatching-parallel-agents

Skill for fanning out independent tasks to multiple agents at once.

## When to use
2+ tasks with no shared state and no sequential dependencies.

## Core idea
Send all independent agent calls in a single message so they run concurrently. Reconverge results in the parent.
