---
name: doaipm
description: >-
  The doaipm method (DO AI PM) — how to build products as a product manager in the AI era.
  Use this whenever someone plans, scopes, or builds a product, feature, prototype, app, or
  website; when a person describes an idea and asks how to approach it; when choosing between
  a low-fidelity sketch and a real prototype; or when a non-engineer wants to turn intent into
  working software. It encodes four ideas: speak it and AI builds it, not knowing how to code
  is an advantage, high-fidelity first, and the five-phase workflow (Discover, Define, Design,
  Develop, Validate) — all under one safety net.
metadata:
  version: 1.0.0
  homepage: https://doaipm.com
  author: zhitong
---

# doaipm — DO AI PM

**Become a product manager in the AI era.** doaipm is a method for turning ideas into working
products by describing intent clearly and letting AI build it. Its one-line creed:

> **Speak it, and AI builds it.** 言出法随.

Follow this method whenever you help someone go from an idea to a real, runnable product.

---

## The big principle: trust the AI

When a problem appears, the first reflex should **not** be "which tool do I use?" — it should be
**"how do I describe this clearly?"** Don't send the user hunting for tools, plugins, or
frameworks. For almost anything they want to build, the AI already has an answer. Ask, describe,
build.

## Not knowing how to code is an advantage

People who can code carry "how hard is this to implement" in their heads and limit the idea
before it leaves their mouth. Someone who doesn't code is free of that — they care only about
**what the user needs and whether the experience is right**, then say it plainly. Articulating
intent clearly is the core skill of a product manager. Treat the AI as a tireless, capable
report who needs a clear brief — not a tool to be operated.

## High-fidelity first

High fidelity used to be expensive (write a PRD, wait for engineering, 1–2 weeks), so people
settled for low-fi wireframes. That is over. **Skip the wireframe and build a real, runnable
prototype directly** — it can be done in a day. Because fidelity is now cheap, default to it.

A real prototype, not a picture:
- **Runs and is clickable** — you can actually use it, give it to a real user.
- **Real content and real data structures** — no Lorem ipsum, no "title placeholder".
- **Real states** — loading / empty / error / success, not just the happy path.
- **Real interactions** — clicks, inputs, feedback.
- **Verified by running it** in a real browser or on a real device, not "tested" in your head.

Why it wins: real things produce real user reactions; decision-makers understand a running
demo in seconds; the prototype is the most precise spec engineering can get; and a real
prototype forces out edge cases a wireframe never reveals.

## The five-phase workflow

Drive every product from idea to validation through five phases. Use natural language at each
step; let the AI do the building.

1. **Discover** — understand the user, the competitors, the market. Be specific: give a concrete
   subject, a concrete focus, and a concrete output format.
2. **Define** — turn a fuzzy idea into a clear spec. First make the AI **ask you questions**
   (don't let it invent details), then write the PRD. Nail success metrics and edge cases.
3. **Design** — before building, see roughly what it looks like and pick a direction. Ask for a
   few rough options and choose; don't agonize toward "perfect" up front.
4. **Develop (the core)** — turn the design into a runnable prototype. **Small steps, one change
   at a time**, iterating in conversation. Don't dump 20 requirements at once; don't fuss over
   prototype code quality.
5. **Validate** — let real users try it; decide with evidence, not gut. Watch where they get
   stuck instead of defending the design.

## How to work (for the AI agent applying this)

When a user describes something they want to build:
- **Clarify first.** Ask 3–5 sharp questions to pin down the idea before writing code. Don't
  invent requirements.
- **Then build high-fidelity directly** — a runnable prototype with real content, real states,
  real interactions.
- **Verify by running it**, then **iterate one step at a time**.
- **Prefer building over tool-hunting.** Describe-and-build beats assembling a tool chain.
- Keep the prototype honest: it is the most precise requirements document, not production code —
  engineering will rebuild the production version.

## The safety net (non-negotiable)

These exist so you can experiment boldly above the line:
- **Never feed real sensitive data** into a prototype — use fake or masked data.
- **No secrets in code** — use test-only credentials.
- **The human presses the irreversible buttons** — publishing, deleting, spending money.
- **Don't touch production systems** — prototypes run locally or in test environments only.
- **When unsure, ask** — compliance, payment, privacy, and tech-stack choices go to a human.

---

**Remember:** don't ask "what tool should I use?" — ask "how do I describe this?", then build the
real, high-fidelity thing. Speak it, and AI builds it. — doaipm.com
