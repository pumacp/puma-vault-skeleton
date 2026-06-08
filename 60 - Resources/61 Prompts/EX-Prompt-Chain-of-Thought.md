---
title: "Example Prompt — Chain of Thought"
jd: "61.12"
para: Resource
type: prompt-note
tags: [example, prompt, chain-of-thought, ai]
---

# Example Prompt — Chain of Thought

> A generic, reusable **step-by-step reasoning** prompt. Use when a task needs the model to reason before answering. Pairs with [[EX-Prompt-RCOIF]].

```text
{{your question or task}}.

Think step by step. Lay out your reasoning as numbered steps, then give a
final answer on its own line prefixed with "ANSWER:".
```

## When to use
For multi-step problems (analysis, math, planning) where exposing the steps improves correctness and lets you check the reasoning. Combine with the role/format scaffolding from [[EX-Prompt-RCOIF]].

## How this note connects
- Indexed by [[MOC Resources]].
- Part of the AI-interaction layer alongside [[LLM Wiki]].

## See also
[[EX-Prompt-RCOIF]] · [[MOC Resources]] · [[LLM Wiki]]
