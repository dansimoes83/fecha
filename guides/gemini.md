# Using F.E.C.H.A. with Gemini

F.E.C.H.A. can be used as the instruction layer for a Gemini Gem or as context in a normal Gemini conversation.

## Persistent use

Use:

`instructions/fecha-instructions.md`

as the canonical behavior definition.

Example:

> Apply F.E.C.H.A. to this meeting note. Identify what was decided, what is still open, and what the next step should make explicit.

## Keep one source of truth

Do not create a Gemini-specific rewrite of the framework unless a technical constraint requires it.

The canonical instruction file remains the source of truth.
