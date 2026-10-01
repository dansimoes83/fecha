# F.E.C.H.A.

**Turn strong work into movement.**

F.E.C.H.A. is an open, model-agnostic decision and execution framework for turning work into one of three outcomes:

- a decision;
- a pilot or test;
- a clear next step with owner and timing.

It is useful when good work risks staying open, vague, appreciated but unused, or dependent on broad feedback.

F.E.C.H.A. is **not** a full product methodology. It is a behavior and communication protocol for helping work move forward.

## Core principle

> Do not let valuable work end with “What do you think?” when it should end with a recommendation, decision, pilot, or next step.

A meaningful piece of work should leave with one of these:

**Decision made → Pilot defined → Next step assigned**

If none exists, the work is not closed yet.

## The sequence

F.E.C.H.A. keeps its original Portuguese step names:

| Step | Meaning | Core question | Output |
|---|---|---|---|
| **F — Foco** | Focus | What needs to be decided, tested, or moved forward? | Clear objective |
| **E — Enquadramento** | Framing | Why does this matter? | Context and tension |
| **C — Caminho mínimo** | Minimum path | What is the smallest useful test or next move? | Pilot or practical path |
| **H — Handoff de decisão** | Decision handoff | What response is needed from others? | Decision request |
| **A — Amarração** | Closure | What was decided and who does what next? | Closed loop |

The original names are intentional. They preserve the mnemonic and the framework's identity.

## When to use it

F.E.C.H.A. is useful when preparing to:

- share a design direction;
- present a concept;
- send a proposal;
- ask for feedback;
- run or join a meeting;
- align stakeholders;
- request approval;
- move from exploration to execution;
- convert an idea into a test;
- close a conversation;
- turn work into something others can adopt.

It is especially useful when there is a risk of:

- vague feedback;
- silence after sharing;
- endless iteration;
- unclear ownership;
- no decision;
- no adoption;
- too much explanation and not enough movement.

## One framework, multiple environments

F.E.C.H.A. does not depend on a specific AI provider or tool.

You can use it:

1. **Manually**
   - as a pre-share checklist;
   - as a meeting close;
   - as a decision framing tool;
   - as a personal execution protocol.

2. **As persistent AI instructions**
   - AI projects or workspaces;
   - custom assistants;
   - GPT-style assistants;
   - Gemini Gems;
   - other environments that support persistent instructions.

3. **As context in a conversation**
   - attach `instructions/fecha-instructions.md`;
   - provide the work, message, plan, or artifact;
   - ask the assistant to apply F.E.C.H.A.

4. **Inside AI-assisted work environments**
   - Cursor;
   - Codex;
   - other environments that can read project files.

The method is stable. The installation changes.

## Quick start

### Manual

Before sharing important work, answer:

1. What needs to be decided, tested, or moved forward?
2. Why does it matter now?
3. What is the smallest useful next step?
4. What response or decision is needed from others?
5. What was decided, who owns the next step, and by when?

Use `templates/full-check.md` for the full version.

### With an AI assistant

Give the assistant:

- `instructions/fecha-instructions.md`;
- the message, plan, meeting note, artifact, or proposal you want to improve.

Then ask:

> Apply F.E.C.H.A. to this. Keep the original intent, but make the decision path, minimum next step, handoff, and closure explicit.

## Canonical files

The source of truth for the method is:

`framework/fecha.md`

The canonical AI instruction file is:

`instructions/fecha-instructions.md`

Tool-specific guides explain how to load the method. They do not redefine it.

## Repository structure

```text
fecha/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── framework/
│   └── fecha.md
├── instructions/
│   └── fecha-instructions.md
├── guides/
│   ├── chatgpt.md
│   ├── gemini.md
│   ├── conversation.md
│   ├── cursor.md
│   └── codex.md
├── templates/
│   ├── full-check.md
│   └── quick-check.md
├── examples/
│   ├── design-direction.md
│   ├── creative-project.md
│   ├── ai-workflow.md
│   └── meeting-close.md
└── release/
    └── v1.0.0.md
```

## What F.E.C.H.A. does not do

F.E.C.H.A. should not:

- replace a product or design methodology;
- force every conversation into a decision;
- turn exploration into premature commitment;
- hide uncertainty;
- manufacture ownership that has not been agreed;
- use a pilot as an excuse to avoid necessary strategy;
- treat “movement” as speed at any cost.

The goal is not to close everything quickly.

The goal is to make the next meaningful movement explicit.

## License

F.E.C.H.A. is released under **CC BY 4.0**.

You may use, share, and adapt the framework, including commercially, as long as appropriate attribution is provided and changes are indicated.

See `LICENSE`.

## Attribution

Created by **Daniel Simões**.

Suggested attribution:

> F.E.C.H.A., created by Daniel Simões. Licensed under CC BY 4.0.

## Version

**1.0.0**

First public, model-agnostic release.