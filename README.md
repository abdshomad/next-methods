# NEXT-Method

**Too lazy to juggle BMAD, Spec Kit, OpenSpec, design.md, Karpathy, Pocock, and autonomous-coding-agents — and remember which to use when?**

With NEXT-Method, you only need to type **`n`** — it will route the right framework, invoke the right skills, advance the workflow, ship the next task, and update your docs. Share an idea once, pick a planning style, then keep hitting **`n`**.

Details: [`AGENTS.md`](AGENTS.md) (for your AI) · [`next-method-plan/NEXT-METHOD-PLAN.md`](next-method-plan/NEXT-METHOD-PLAN.md) (if you care how it works).

---

## Setup

```bash
git clone --recurse-submodules https://github.com/abdshomad/next-methods.git
cd next-methods
```

Forgot `--recurse-submodules`? Run `git submodule update --init --recursive` inside the repo.

---

## Go

1. Open in Cursor (or any AI IDE). Point the agent at **`AGENTS.md`**.
2. Tell it your idea. Pick a method when asked (`1`–`5` or `n bmad`, etc.).
3. Type **`n`**. Repeat. **`e`** when you need a fresh task list. **`n3`** if you're feeling ambitious.

## AFK (optional)

After you pick a method: **`/goal Ship the MVP`** — agent keeps running `n` until the goal is done (or type **`stop`**). Empty task list auto-replans — the loop won't quit on its own. Cursor: **`/loop 15m`**. Antigravity: **`/schedule`**.

That's it.
