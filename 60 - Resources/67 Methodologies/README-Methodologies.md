---
title: "Methodologies — How This Skeleton Is Built"
jd: "67.00"
para: Resource
bucket: index
type: readme
tags: [methodology, index, core, modular, reference]
---

# 67 Methodologies

This folder documents **every methodology the PUMA Vault Skeleton uses or references**, kept in three physically separated buckets so you never confuse what is *implemented* with what is merely *worth knowing*.

> [!info] Self-documentation principle
> These notes are themselves classified with the vault's own Johnny Decimal + PARA, linked through a [[MOC-Methodologies|Map of Content]], and written as atomic notes — the skeleton explains itself **using its own methods**.

## The three buckets

| Bucket | Folder | Meaning | Contract |
|--------|--------|---------|----------|
| 🟦 **Core** | `67.1 Core/` | The always-on backbone. Implemented and fused. | how it works · source · **bridge** · ≥2 worked examples |
| 🟩 **Modular** | `67.2 Modular/` | Opt-in by user profile. Implemented, not imposed. | how it works · source · **bridge** |
| 🟥 **Reference** | `67.3 Further-Reading-Non-Integrated/` | Mentioned, **not** integrated. | how it works · source · **why not integrated** |

## Core backbone (7)

[[PARA]] · [[Johnny Decimal]] · [[Zettelkasten]] · [[Map of Content (MOC)]] · [[GTD]] · [[LLM Wiki]] · [[CeReBro (CODE)]]

The seven fuse into one loop. **CeReBro/CODE** is the orchestration layer:

```
Capture   ← GTD            (10 - Inbox)
Organize  ← PARA + Johnny Decimal   (40/50/60/70)
Distill   ← Zettelkasten + MOC      (30 - Permanent, 80 - MOC)
Express   ← LLM Wiki + permanent notes + publishing
```

## Modular (opt-in, 6 new + the research/dev/prompting modules)

[[Evergreen Notes]] · [[Progressive Summarization]] · [[Feynman Technique]] · [[SQ3R]] · [[Spaced Repetition]] · [[Diataxis]] — plus the research-flow (Keshav, MIT WP316, PRISMA/SLR, DSR), development (SDD, OpenSpec, BMAD, CDD) and prompting (RCOIF, CoT, Contextual Anchoring) notes documented elsewhere in the vault.

## Reference only (not implemented)

[[LATCH]] · [[DIKW]] — described, with the specific reason each does **not** fuse with the core.

## See also
[[MOC-Methodologies]] · [[Johnny Decimal]] · [[PARA]]
