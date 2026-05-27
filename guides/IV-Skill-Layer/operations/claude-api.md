# claude-api

Skill: build with the Anthropic SDK / Claude API.

## When to use
Code that imports `anthropic` or `@anthropic-ai/sdk`; adding caching, tool use, streaming, batch, files, or model upgrades.

## Core idea
Default to the latest model. Enable prompt caching. Stream where UX benefits. Use structured tool definitions over freeform prompts whenever the task has discrete actions.
