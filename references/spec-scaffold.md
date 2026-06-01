# One-sentence spec — say what you want clearly

This is **not a form to fill in**. It's the scaffold you should have in your head (or hand to the
AI to fill in for you) when you describe what to build. Speak it; let the AI build it.

## The scaffold

```
I want to help [who] solve [what problem].
With the result, the user can [the single most important action].
It's done right when [one visible, observable outcome].
This round explicitly excludes [non-goals — draw the boundary].
Known risks / assumptions: [...].
```

Hand this to the AI with one key instruction:

> "Before you build, restate what I want in your own words, then ask me the 3–5 most important
> questions. I'll answer, then you start."

The output of this step is not a document — it's **shared understanding**. If the AI's restatement
is right and its questions hit the real unknowns, it has understood, and the high-fidelity
prototype it builds next won't drift.

## If you can't even state it — borrow a discovery structure

When you don't know what to ask, pick one classic structure and let the AI run it with you:

- **JTBD (the job the user hires this for):** "In what situation does the user want this to get
  what job done? How do they cope today?"
- **Opportunity Solution Tree:** "What outcome do we want? What pain-point opportunities exist?
  What solutions could serve each?"
- **Working Backwards:** "Assume it already shipped — write the line a happy user would say about
  it, and work backward to what we must build."

Don't learn all three. Pick the one that fits, let the AI ask using its structure, then come back
to the one-sentence spec.
