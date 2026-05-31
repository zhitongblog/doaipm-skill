# doaipm — DO AI PM

> **Speak it, and AI builds it.** 言出法随.

The **doaipm** method as a portable AI skill — a default working method you can drop into any
AI coding tool. It teaches an agent (and you) how to turn an idea into a real, runnable product
the way a product manager in the AI era actually works.

🌐 **[doaipm.com](https://doaipm.com)** · MIT licensed · works with Claude Code, Codex CLI,
Gemini CLI, Cursor, and anything that reads an `AGENTS.md`.

---

## The method in one breath

Don't ask *"what tool should I use?"* — ask *"how do I describe this?"*, then build the real,
high-fidelity thing.

- **Trust the AI, don't tool-hunt.** For almost anything, the model already has an answer.
- **Not knowing how to code is an advantage** — focus on what the user needs and say it clearly.
- **High-fidelity first.** Skip wireframes; build a real, runnable prototype directly — real
  content and data, real states (loading / empty / error / success), real interactions.
- **Five phases:** Discover → Define → Design → Develop → Validate.
- **Safety net:** no real secrets/data in prototypes; the human presses irreversible buttons;
  don't touch production; ask when unsure.

Full method: [`SKILL.md`](./SKILL.md).

## Install

| Tool | How |
|------|-----|
| **Claude Code** | `git clone` this repo into `~/.claude/skills/doaipm/` (must contain `SKILL.md`). Auto-discovered. |
| **Codex CLI** | Clone into `~/.codex/skills/doaipm/`, or append `doaipm.method.md` to `~/.codex/AGENTS.md`. |
| **Gemini CLI** | Append `doaipm.method.md` to `~/.gemini/GEMINI.md`. |
| **Cursor** | Copy `doaipm.mdc` into `~/.cursor/rules/` (global) or `.cursor/rules/` (per project). |
| **Any other agent** | Drop `doaipm.method.md` into the project's `AGENTS.md` / `CLAUDE.md`. |

One-liner (Claude Code):

```bash
git clone https://github.com/zhitongblog/doaipm-skill ~/.claude/skills/doaipm
```

## The proof

This method isn't theory. The [doaipm.com](https://doaipm.com) site and a row of real, shipping
products were all built this way, with Claude Code:

- [SoloMD](https://solomd.app) — Markdown editor
- [Unterm](https://unterm.app) — a terminal AI agents can drive
- [unfetch](https://unfetch.org) — download manager for humans & AI
- [StoryAlter](https://storyalter.com) — your AI writing alter-ego
- [Unflick](https://unflick.app) — video player for humans & AI

> The method explains the work; the work proves the method.

## License

MIT © zhitong · [doaipm.com](https://doaipm.com)
