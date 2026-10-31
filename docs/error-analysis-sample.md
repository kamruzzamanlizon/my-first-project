# Annotation Error Analysis — Illustrative Sample

> **Sample only:** The scenario and numbers below are fictional examples used to demonstrate an analysis method. They are not client results or personal project metrics.

## Purpose

Turn review findings into clear corrective actions and reduce repeated annotation issues.

## Example review summary

Assume a reviewer checks a sample batch of 100 images and records the following findings:

| Issue category | Illustrative count | Potential impact |
|---|---:|---|
| Incorrect class | 8 | High |
| Missing required object | 6 | High |
| Box placement issue | 12 | Medium |
| Duplicate annotation | 3 | Medium |
| Attribute inconsistency | 4 | Medium |

Counts represent issue instances in this fictional example; one image may contain more than one issue.

## Analysis

1. **Prioritize high-impact errors.** Incorrect classes and missing objects can directly affect dataset labels.
2. **Look for patterns.** Check whether errors cluster around a particular class, guideline section, or task type.
3. **Separate individual and systemic causes.** A repeated misunderstanding across several annotators may indicate unclear instructions or insufficient examples.
4. **Choose a corrective action.** Provide targeted feedback, clarify the guideline, or arrange a short calibration review.
5. **Recheck.** Review a follow-up sample to see whether the same issue continues.

## Corrective action tracker

| Finding | Possible cause to investigate | Action | Follow-up |
|---|---|---|---|
| Incorrect class | Similar class definitions | Share contrasting examples | Review next sample |
| Missing object | Incomplete scan or unclear inclusion rule | Revisit completeness checklist | Targeted recheck |
| Box placement issue | Inconsistent box convention | Share approved placement examples | Compare corrected labels |
| Duplicate annotation | Instance identification issue | Explain duplicate-check step | Review next batch |
| Attribute inconsistency | Attribute definition misunderstood | Clarify attribute rules | Spot-check attributes |

## Reporting template

- Batch / project:
- Review scope:
- Main error patterns:
- Highest-priority risks:
- Likely contributing factors:
- Actions assigned:
- Owner:
- Follow-up date:
- Result of follow-up:

## Quality improvement principle

Use evidence from reviewed work to decide what to coach. Avoid blaming annotators before checking guideline clarity, task setup, and examples.
