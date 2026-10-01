# Using F.E.C.H.A. with ChatGPT

F.E.C.H.A. is model-agnostic. ChatGPT is one possible environment.

## Persistent use

Use `instructions/fecha-instructions.md` as persistent instructions in a project or custom assistant when the environment supports them.

Then provide the work you want to review.

Example:

> Apply F.E.C.H.A. to this proposal. Do not change the core idea. Show me where the decision path is still open and propose the smallest useful next step.

## Conversation use

You can also attach the instruction file to a normal conversation.

Provide:

1. `fecha-instructions.md`;
2. the message, plan, artifact, or meeting note;
3. what you want to move forward.

The specific UI may change over time. The durable rule is simple:

> Give the model the canonical F.E.C.H.A. instruction file as persistent instructions or conversation context.
