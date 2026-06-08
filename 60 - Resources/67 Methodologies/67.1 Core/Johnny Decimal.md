---
title: "Johnny Decimal"
jd: "67.12"
para: Resource
bucket: core
type: methodology
aliases: [Johnny Decimal System, JD, AC.ID]
tags: [methodology, core, johnny-decimal, addressing]
---

# Johnny Decimal

> Give every item a short, unique numeric address — `AC.ID` — so you can find anything by number instead of hunting through folders.

## How it works
The system caps complexity on purpose:

- **Areas** are numbered in tens: `10–19`, `20–29` … up to ten areas.
- **Categories** are the digits inside an area: `40 Projects`, `41`, `42` …
- **IDs** are the decimal: `41.3`, `61.2`. Conceptually ≤10 of each level.

Every note therefore has a stable address (e.g. this note is `67.12`). Addresses do not change when titles do, which makes them ideal anchors for links and citations.

This vault uses a JD-master root: `00 Meta · 10 Inbox · 20 Literature · 30 Permanent · 40 Projects · 50 Areas · 60 Resources · 70 Archive · 80 MOC · 90 GTD`.

## Source
Johnny Noble, "The Johnny.Decimal system" (johnnydecimal.com). It is an organizational *addressing* layer, not a note-taking method.

## Bridge
- **PARA** supplies the *meaning* of the ranges; JD supplies the *address*. Together: `40` = Projects, `50` = Areas… See [[PARA]].
- **Zettelkasten** notes and **MOCs** get permanent JD addresses, so links survive renames. See [[Zettelkasten]], [[Map of Content (MOC)]].
- Underpins the **self-documentation** invariant: every explanatory note is citable by number.

## Worked examples
- **Example 1 — Filing a new method note.** A new "Grounded Theory" note needs a home. It is a research *method*, so it goes under `30 - Permanent/32 Methods` and is assigned the next free ID, e.g. `32.05`. You can now cite it as `32.05` from anywhere.
- **Example 2 — Resolving a collision.** Two notes both want `61.2`. JD's rule (≤10 items per category) forces a decision: either one becomes `61.3`, or the category is split (`61 Prompts` → `61.1 LLM`, `61.2 Research`), keeping every address unique and meaningful.

## See also
[[PARA]] · [[Zettelkasten]] · [[Map of Content (MOC)]] · [[README-Methodologies]]
