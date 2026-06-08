# Contributing to PUMA Vault Skeleton

Thanks for your interest in improving the skeleton. It is a **Markdown-only, tool-agnostic** knowledge vault, so contributions are mostly notes, structure, and documentation — no build step required.

## Ground rules
- **English only.** Every file, note, comment, and filename must be in English (contents *and* filenames).
- **Markdown only.** The repository ships `.md` content plus standard GitHub files. Please do not add application config (`.obsidian/`), Quartz config, or code/scripts to the repo.
- **Keep it generic.** Notes should be reusable and topic-neutral. Avoid tying content to any specific project; the original project name belongs only in the title.
- **Be kind.** Participation is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How to propose a change
1. Fork the repository and create a branch (`feature/short-description`).
2. Make your change, following the conventions below.
3. Run the quality checks (see [Verification.md](Verification.md)) and make sure they pass.
4. Open a pull request describing **what** changed and **why**.

## Conventions
- **Placement:** put each note in the correct Johnny Decimal area (see `60 - Resources/66 Johnny-Decimal-Index/JD-Master-Index.md`) and PARA category.
- **Frontmatter:** include at least `title`, `jd`, and `para`. Methodology notes additionally need *How it works*, *Source*, and either *Bridge* (core/modular) or *Why not integrated* (reference).
- **Links:** connect new notes with `[[wikilinks]]` and add them to a relevant Map of Content — no orphans.
- **Templates:** start new notes from the matching template in `00 - Meta/Templates`. In templates, show placeholder links as `` `code` `` so they never count as broken links.

## What we especially welcome
- New worked examples that demonstrate a method more clearly.
- Fixes for broken links, non-English strings, or unclassified notes.
- Better, citable explanations in the methodology notes.
- Additional opt-in modules — each must cite a verifiable source and state an explicit bridge to the core, or it belongs in *Further Reading / Non-integrated*.

## Quality bar (the PR should keep these green)
- 0 broken links · 0 non-English strings · methodology notes carry their required fields · no orphan notes.

By contributing, you agree that your contributions are licensed under [CC BY 4.0](LICENSE).
