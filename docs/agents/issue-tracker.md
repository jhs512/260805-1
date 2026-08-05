# Issue tracker: Local Markdown

Issues and specs for this workspace live as Markdown files in `.scratch/`.

## Conventions

- One feature per directory: `.scratch/<feature-slug>/`
- The spec is `.scratch/<feature-slug>/spec.md`
- Implementation issues are one file per ticket at `.scratch/<feature-slug>/issues/<NN>-<slug>.md`, numbered from `01`
- Triage state is recorded as a `Status:` line near the top of each issue file
- Comments and conversation history append under a `## Comments` heading

## When a skill says "publish to the issue tracker"

Create a file under `.scratch/<feature-slug>/`, creating the directory if needed.

## When a skill says "fetch the relevant ticket"

Read the referenced file. The user will normally provide its path or issue number.

## Wayfinding operations

- Map: `.scratch/<effort>/map.md`
- Child ticket: `.scratch/<effort>/issues/NN-<slug>.md`
- Use `Type:` for `research`, `prototype`, `grilling`, or `task`.
- Use `Status:` for `claimed` or `resolved`.
- Use `Blocked by:` for prerequisite ticket numbers.
- Claim a ticket before work; add an `## Answer` section when resolving it.
