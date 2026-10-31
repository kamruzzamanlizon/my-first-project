# AI Annotation QA Checklist

This checklist is a reusable portfolio sample. Always adapt it to the client’s task-specific instructions and acceptance criteria.

## 1. Before reviewing

- [ ] Confirm the correct project, task, and guideline version.
- [ ] Confirm the required annotation type and output format.
- [ ] Review edge cases and class definitions.
- [ ] Confirm whether uncertain or partially visible objects should be labeled, skipped, or escalated.

## 2. Label correctness

- [ ] Correct class/category selected.
- [ ] All required visible objects considered.
- [ ] No unsupported or speculative labels added.
- [ ] Attributes and tags match the instructions.
- [ ] Duplicate labels avoided.

## 3. Geometry and placement

- [ ] Bounding boxes or polygons fit the target object according to project rules.
- [ ] Labels do not unintentionally include unrelated objects.
- [ ] Overlapping objects are handled according to the guideline.
- [ ] Truncated or occluded objects follow the project’s visibility rules.

## 4. Completeness and consistency

- [ ] No required objects are missed.
- [ ] Similar cases are labeled consistently.
- [ ] Class naming and attribute usage are consistent.
- [ ] Special cases are documented or escalated.

## 5. Final review

- [ ] Corrections are applied and rechecked.
- [ ] Required files and formats are present.
- [ ] No obvious export or submission issues remain.
- [ ] Review outcome and unresolved questions are recorded.

## Suggested review outcomes

- **Pass:** Meets the project’s acceptance criteria.
- **Minor correction:** Limited issues that can be corrected quickly.
- **Rework required:** Multiple or significant issues; return with specific feedback.
- **Escalate:** Guideline ambiguity or an issue requiring a project lead/client decision.

## Review record template

| Field | Entry |
|---|---|
| Project / batch | |
| Guideline version | |
| Annotator / reviewer | |
| Items reviewed | |
| Issues found | |
| Outcome | |
| Corrective action | |
| Follow-up required | |

**Reminder:** A QA decision must be based on the project’s actual guidelines, not personal preference.
