---
title: "Verification"
jd: "00.12"
para: Meta
type: guide
tags: [guide, verification, quality, qa]
---

# ✅ Verification

The skeleton ships as **Markdown only** — no code. Quality is still verifiable by inspection: this note describes the criteria a healthy copy of the vault should meet, and how to check them with any tools you like. It intentionally commits **no scripts**.

## What "good" means (acceptance criteria)
1. **Valid internal links** — every `[[wikilink]]` and `![[embed]]` resolves to an existing note.
2. **Complete methodology coverage** — at least seven core methods, each documenting how it works, its source, and at least two worked examples.
3. **Consistent classification** — every explanatory note carries its Johnny Decimal (`jd:`) and PARA (`para:`) fields.
4. **Coherent structure** — each note sits in the correct area, connects to a relevant Map of Content, and leaves no orphans.

## How to check, by hand or with your own tools
- **Links:** Obsidian shows unresolved links in the graph and the *Unlinked mentions* pane; or list each `[[ ]]` target and confirm the file exists. Respect aliases (frontmatter `aliases:`) and ignore attachment embeds.
- **Coverage:** open each note under `60 - Resources/67 Methodologies/67.1 Core` and confirm it has *How it works*, *Source*, *Bridge*, and a *Worked examples* section with at least two items.
- **Classification:** confirm each methodology note's frontmatter carries `jd:` and `para:` fields.
- **Structure:** confirm each new note is linked from a Map of Content and placed in the correct Johnny Decimal area.

The criteria — not any particular tool — are what matter: any linter, a few lines of script, or your editor's search will reproduce the results.

## See also
[[Getting-Started]] · [[README-Methodologies]] · [[MOC-Methodologies]]
