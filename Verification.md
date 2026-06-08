---
title: "Verification"
jd: "00.12"
para: Meta
type: guide
tags: [guide, verification, quality, qa]
---

# ✅ Verification

The skeleton ships as **Markdown only** — no code. Quality is still verifiable: the maintainers run a small local check suite before every release, and you can reproduce the same checks with any tools you like. This note describes *what* is checked and *how to check it yourself*; it intentionally commits **no scripts**.

## What "good" means (acceptance criteria)
1. **0 broken links** — every `[[wikilink]]` and `![[embed]]` resolves.
2. **0 non-English strings** — English only, in **both** file contents and filenames.
3. **No project residue** — no leftover identity tokens from the source project (only the title "PUMA Vault Skeleton" remains).
4. **≥7 core methods, each with ≥2 worked examples** — see [[MOC-Methodologies]].
5. **100% of explanatory notes classified** with Johnny Decimal + PARA.

## How to check, by hand or with your own tools
- **Broken links:** Obsidian shows unresolved links in the graph and the *Unlinked mentions* pane; or grep for `[[ ]]` targets and confirm each file exists. Respect aliases (frontmatter `aliases:`) and ignore attachment embeds.
- **Non-English:** search for inverted Spanish punctuation marks and accented Latin letters across contents and filenames; allow only deliberate typographic characters (em dash, curly quotes).
- **Residue tokens:** search the corpus for the source project's identifiers; expect zero hits outside this skeleton's own title.
- **Core coverage:** open each note under `60 - Resources/67 Methodologies/67.1 Core` and confirm it has *How it works*, *Source*, *Bridge*, and a *Worked examples* section with at least two items.
- **Classification:** confirm each methodology note's frontmatter has `jd:` and `para:` fields.

## Reproducing the maintainers' suite
The maintainers keep a local-only check folder (not shipped) that automates the five checks above against the same rules. Any equivalent linter, a few lines of Python, or your editor's search will reproduce the results — the criteria, not the tooling, are what matter.

## See also
[[Getting-Started]] · [[README-Methodologies]] · [[MOC-Methodologies]]
