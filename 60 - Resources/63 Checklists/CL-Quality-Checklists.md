---
id: CL-Quality-Checklists
title: "Quality Checklists"
type: checklist
jd: "63.01"
para: Resource
tags: [checklist, quality, reproducibility, ai-validation, verification]
created: "{{date}}"
---

# ✅ Quality Checklists

Three reusable, generic checklists. Copy the relevant one when assessing a source, running a reproducible experiment, or validating AI output.

---

## 1. Source quality assessment
Score each criterion 1 (poor) – 3 (good). Useful for a literature review or any structured reading.

- **Question clarity** — is the research question clear, specific, and answerable?
- **Design appropriateness** — does the method fit the question?
- **Data transparency** — is the data described and, ideally, public (DOI/URL)?
- **Metric appropriateness** — are the measures justified?
- **Baseline comparison** — is there a clear, reproducible baseline?
- **Rigour** — is the analysis complete (effect sizes, uncertainty)?
- **Reproducibility** — are code, data, and instructions available?
- **Threats to validity** — are internal/external/construct threats discussed?

**Decision:** include as primary evidence · include as secondary (note limits) · exclude.

---

## 2. Experiment reproducibility
Complete before and after any experiment you want others (or future-you) to reproduce.

- [ ] Environment recorded (language/tool versions, pinned dependencies)
- [ ] Inputs loaded from the original source (not a modified copy)
- [ ] Randomness controlled (fixed seed) and configuration logged
- [ ] Raw outputs saved, not only the processed result
- [ ] Results saved with a timestamp and committed to version control
- [ ] Analysis recorded in a note linked to the source data

---

## 3. AI output validation (primary-source verification)
> Apply whenever AI-generated output is being considered for incorporation into your work. This is the skeleton's **primary-source-verification** discipline: never trust a generated claim you have not traced to a real source.

**Before using AI output**
- [ ] I have a clear objective and gave sufficient context (see [[EX-Prompt-RCOIF]]).
- [ ] I understand what the model cannot know or verify.

**Factual claims (numbers, citations, statistics)**
- [ ] Every specific claim is traced to a primary source.
- [ ] Every citation is verified in the source itself (the DOI/URL resolves to the right work).
- [ ] Any claim that cannot be verified is discarded or clearly flagged.

**Analytical output (synthesis, argument)**
- [ ] I read the primary sources myself rather than relying on the summary.
- [ ] The output is rewritten in my own words before incorporation.

**Code output**
- [ ] I understand every line and can explain what it does.
- [ ] It is tested, with edge cases considered.

## See also
[[LLM Wiki]] · [[Verification]] · [[MOC Resources]]
