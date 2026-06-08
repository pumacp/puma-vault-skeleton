---
title: "LLM Wiki"
jd: "67.16"
para: Resource
bucket: core
type: methodology
aliases: [LLM Wiki Pattern, Wiki-as-context]
tags: [methodology, core, llm, ai, context]
---

# LLM Wiki

> Keep a personal, well-linked Markdown wiki that an LLM reads directly as context — durable hand-curated knowledge instead of opaque retrieval.

## How it works
Because the vault is plain linked Markdown, it doubles as a knowledge base an AI assistant can be pointed at:

- Atomic notes become reusable **context units** you cite into a prompt.
- Links let you (or the model) traverse from one idea to related ones.
- Updating a note updates the context everywhere it is used — the wiki is the single source of truth.

This is a deliberate alternative to black-box RAG for personal knowledge: you can read, edit, and trust every note the model sees.

## Source
Popularized by Andrej Karpathy's 2026 note on using a personal wiki (Obsidian-style) as durable LLM context; aligns with the long tradition of personal wikis.

## Bridge
- **Zettelkasten** permanent notes *are* the wiki's atomic context units — the graph confirms they are semantically the same pattern. See [[Zettelkasten]], [[Evergreen Notes]].
- Realizes the **Express** phase of CODE: the curated wiki is what you publish and what the AI expresses from. See [[CeReBro (CODE)]].
- Pairs with **Diataxis** to structure the published documentation. See [[Diataxis]].

## Worked examples
- **Example 1 — Drafting with context.** To draft a section, you point an LLM at three permanent notes (`[[...]]`) as context; it writes from *your* curated material rather than guessing, and you keep editorial control.
- **Example 2 — Growing a stub.** A one-line "concept stub" note is enriched over weeks; each time the LLM uses it, it carries the latest, best version — context quality compounds.

## See also
[[Zettelkasten]] · [[Evergreen Notes]] · [[CeReBro (CODE)]] · [[Diataxis]] · [[README-Methodologies]]
