---
title: "Example Prompt — RCOIF"
jd: "61.11"
para: Resource
type: prompt-note
tags: [example, prompt, rcoif, ai]
---

# Example Prompt — RCOIF

> A generic, reusable **prompt template** built with the RCOIF frame (Role · Context · Objective · Instructions · Format). Topic-neutral — fill the brackets for your task.

```text
ROLE: You are a {{expert role}}.
CONTEXT: {{the background the model needs}}.
OBJECTIVE: {{the single outcome you want}}.
INSTRUCTIONS:
  1. {{step}}
  2. {{step}}
FORMAT: {{the exact output shape, e.g. a Markdown table}}.
```

## When to use
A first-choice structure for most single-shot tasks. For multi-step reasoning, pair with [[EX-Prompt-Chain-of-Thought]].

## How this note connects
- Indexed by [[MOC Resources]].
- Part of the AI-interaction layer alongside [[LLM Wiki]].

## See also
[[EX-Prompt-Chain-of-Thought]] · [[MOC Resources]] · [[LLM Wiki]]
