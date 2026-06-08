---
id: "PT-{{Tool}}-{{UseCase}}"
title: "Prompt: {{Tool}} — {{Use Case}}"
type: prompt-template
jd: ""
para: Resource
tags: [prompt, template, ai]
tool: "{{claude | chatgpt | gemini | ollama | ...}}"
methodology: "{{rcoif | cot | few-shot | ...}}"
tested: false
created: "{{date}}"
updated: "{{date}}"
---

# Prompt: {{Tool}} — {{Use Case}}

> **Purpose:** one sentence describing what this prompt achieves.

## 🎯 When to use
- **Situation:** when this prompt is appropriate.
- **Input required:** what you must have ready.
- **Expected output:** what the model should produce.

## 📋 The prompt (RCOIF structure — see [[EX-Prompt-RCOIF]])
```text
ROLE: {{the model's role}}
CONTEXT: {{background it needs}}
OBJECTIVE: {{the single outcome}}
INSTRUCTIONS:
  1. {{step}}
FORMAT: {{the exact output shape}}; Language: English
```

## 📊 Example interaction
- **Input given:** the input you used.
- **Output received:** the output (truncated).
- **Quality:** was it useful? what would you change?

## 🔧 Refinement history
| Version | Change | Reason | Result |
|---------|--------|--------|--------|
| 1.0 | initial | — | {{outcome}} |

## 🔗 Related prompts
- Similar purpose: `[[PT-OtherTool-SameUseCase]]`
- Next step after this: `[[PT-SameTool-NextStep]]`

## See also
[[EX-Prompt-RCOIF]] · [[EX-Prompt-Chain-of-Thought]] · [[LLM Wiki]]
