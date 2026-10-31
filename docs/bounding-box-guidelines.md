# Bounding Box Annotation — Review Guide

This document is a general work sample. The project’s own class definitions, visibility rules, and box-placement conventions always take priority.

## Review dimensions

### 1. Class accuracy
- Confirm that the selected class matches the object definition.
- Check visually similar classes against the project’s taxonomy.
- Do not infer a class when the evidence is insufficient; follow the project's uncertainty procedure.

### 2. Box placement
- Check that the box encloses the intended object.
- Avoid including unrelated background or neighboring objects unless the guideline explicitly requires it.
- Check that the box is not unnecessarily loose or excessively tight.
- Follow the project's convention for partially visible objects and image boundaries.

### 3. Multiple and overlapping objects
- Check whether each required instance has its own annotation.
- Verify that overlapping objects are not incorrectly merged into one box.
- Apply occlusion and visibility rules consistently.

### 4. Missing and duplicate annotations
- Look for required objects that have not been labeled.
- Check for duplicate boxes around the same instance.
- Confirm that excluded objects are not annotated.

### 5. Attributes and export
- Verify required attributes, IDs, and class names.
- Check the requested export format and naming conventions.
- Confirm that the exported annotations correspond to the reviewed images.

## Common review findings

| Finding | QA action |
|---|---|
| Incorrect class | Correct or return for correction with the expected class |
| Missing object | Add/return for the missing required instance |
| Duplicate box | Remove duplicate according to workflow |
| Poor box fit | Request geometry correction |
| Inconsistent occlusion handling | Refer to the guideline and align similar cases |
| Unclear guideline case | Escalate; do not invent a rule |

## CVAT workflow familiarity

My hands-on platform experience includes CVAT. The exact steps and project configuration can vary, so this guide focuses on review principles rather than claiming a particular client setup.
