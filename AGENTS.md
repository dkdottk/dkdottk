# Agent instructions

This repository (and related project work) follows **Spec-Driven Development (SDD)**.

## Rule

Do not start implementation from a vague chat request alone.

1. Write or update a **spec** under `specs/`.
2. Get agreement on the spec (or treat an explicit user-approved spec as the source of truth).
3. Derive a short **implementation plan** from the spec.
4. Implement only what the spec requires.
5. Verify against the spec (tests, checks, acceptance criteria).

If behavior must change, **update the spec first**, then the code.

## Spec location

- Active feature specs: `specs/<feature-name>/`
- Process details: `docs/spec-driven-development.md`

## Required artifacts per feature

| Artifact | Path | Purpose |
|----------|------|---------|
| Spec | `specs/<feature>/spec.md` | Intent, scope, behavior, constraints, acceptance criteria |
| Plan | `specs/<feature>/plan.md` | Implementation steps mapped to the spec |
| Notes (optional) | `specs/<feature>/notes.md` | Open questions, decisions, out-of-scope items |

## Working style

- One job per change: match the active spec section.
- Prefer small, reviewable diffs tied to acceptance criteria.
- Do not invent product requirements that are not in the spec; ask or record them in the spec instead.
- Keep the profile README (`README.md`) as the public GitHub profile page unless a task explicitly changes it.
