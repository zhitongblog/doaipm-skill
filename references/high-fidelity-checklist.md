# High-fidelity verification checklist (the most important page)

"Done" is not the same as "good." Verifying high fidelity isn't looking at a screenshot — it's
**running the real thing and going through it item by item**.

## The checklist

| Check | Ask yourself |
|---|---|
| **Real content** | Real content and real data structures? Any Lorem ipsum, "sample text", fake placeholders? |
| **Four states** | Loading / empty / error / success — all four built? Empty and error get missed most. |
| **Real interaction** | Buttons actually click, forms actually submit, navigation actually navigates? Or does it just "look like" it? |
| **Critical path** | The single most important user flow — does it work end to end? |
| **Cross-device** | Looked at it on phone *and* desktop? At least run through a narrow screen. |
| **Nasty input** | Deliberately enter wrong / empty / oversized / weird characters — does it break? |

## If you built an AI feature, add one more

An AI feature can't pass on a single lucky success. **Run a batch of real, adversarial inputs in a
row** — see if it stays stable, whether it hallucinates, how it falls back when wrong. Have the AI
draft a dozen test inputs and run them. This is what the industry calls an "evaluation loop"
(eval) — and a PM can do it.

## How to use this checklist

Hand it straight to the AI:

> "Go through this checklist item by item, self-check, and run each item for me to see. Fix
> anything that doesn't pass, on the spot."

Let it run the checklist; you just sign off on the result.
