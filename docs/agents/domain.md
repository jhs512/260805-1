# Domain Docs

This workspace uses a single-context domain-documentation layout.

## Before exploring

- Read `CONTEXT.md` if it exists.
- Read relevant ADRs under `docs/adr/` if they exist.
- Proceed silently when either is absent.

The `/domain-modeling` skill creates these documents only when terminology or decisions need recording.

## Rules

- Use terms defined in `CONTEXT.md` consistently.
- If terminology is missing, reconsider whether a new term is needed and record a real gap for `/domain-modeling`.
- Surface conflicts with an existing ADR instead of silently overriding it.
