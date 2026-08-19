# Quick Course Starter

This repository is a course project template. Build accessible courses from supplied source material using the pinned Quick Course Kit release. Compose the Kit; do not redesign or recreate it.

## Before implementation

- Inspect `src/config/course.ts`, supplied files in `course/storyboard/`, local media, `course/component-map.md`, and the pinned Kit manifest and guidance.
- Update the component map before implementation, then keep it aligned with the course.
- Confirm the intended scope and flag ambiguity early.

## Source and content

- Supplied course source is authoritative. You may structure it, format it, and make light UI-fit edits, but do not invent facts, policy, SME conclusions, answers, rationale, procedures, or client intent.
- Use ordinary semantic content when it is clearest. Choose a governed Kit component only when it improves the learning purpose.
- Interactive presentation can carry required learning content only when that content remains accessible, discoverable, keyboard-operable, and understandable.
- When no appropriate Kit component exists, use ordinary markup or the closest approved pattern and report the gap. Do not create a near-duplicate component.

## Boundaries

- Use public exports from the pinned Kit package. Do not modify, copy, or import from Kit source, the workbench, or `node_modules` internals.
- Keep course-local code separate from Kit code. Do not create a second design system.
- This repository does not manage Kit lifecycle status, approval data, workboard entries, SCORM packaging, or Kit release generation.

## Quality

- Preserve semantic structure, visible keyboard focus, responsive reflow, readable contrast, and meaningful media alternatives.
- For learner-facing UI changes, inspect the result in a browser before calling it visually complete. A successful build is not visual acceptance.
- Run available checks and report anything that cannot be verified accurately.
