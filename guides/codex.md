# Using F.E.C.H.A. with Codex

F.E.C.H.A. can be used inside a repository as a decision and execution protocol for plans, proposals, notes, and work artifacts.

## Suggested structure

```text
project/
├── instructions/
│   └── fecha.md
├── inputs/
│   ├── plan.md
│   └── review-notes.md
└── outputs/
```

Place the canonical instructions at:

`instructions/fecha.md`

Example task:

> Read `instructions/fecha.md` first. Apply F.E.C.H.A. to `inputs/plan.md`. Identify missing decision, minimum path, handoff, and closure. Do not modify the input.

For a revised artifact:

> Based on the approved F.E.C.H.A. review, create a revised plan in `outputs/plan-v2.md`. Do not invent owners, dates, or decisions that are not supported.
