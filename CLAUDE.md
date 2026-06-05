# CLAUDE.md — WeldoCNC Content Repository

## What This Repository Is

This is a **Markdown-only content repository** for the WeldoCNC website.
All files are `.md` content pages intended for the WeldoCNC website.

**Do not write HTML, CSS, JavaScript, or any code.**
**Do not scaffold frameworks, build components, or install packages.**
**If asked to build or code anything, decline and redirect to content writing.**

---

## Start of Every Session — Ask This First

Before doing anything else, ask the user:

> **"Agent mode or manual mode?"**
>
> - **Agent mode** — I read `_system/execution-plan.md`, pick the first unchecked item, complete it, check the box, update `_system/progress.md`, commit and push, then stop. Run me again to do the next item.
> - **Manual mode** — I wait for your instructions and work on whatever you specify.

Do not start any work until the user answers. Do not assume a mode.

---

## System Files — Read Before Writing Any Page

Always read these before working on any content page:

| File | Purpose |
|---|---|
| `_system/WritingSystem.md` | Brand voice, copy rules, banned words, five-pass quality system (A→B→N→D→C), SEO, GEO/AI SEO, E-E-A-T |
| `_system/CLIENT-DATA-MAP.md` | Single source of truth for all verified numbers, specs, and claims |
| `_system/competitors.md` | Competitor intelligence — verified specs for comparison content |
| `_system/execution-plan.md` | Ordered task list — used in agent mode |
| `_system/progress.md` | Page status tracker — update to ✅ when a page is done |

---

## Agent Mode — How It Works

1. Read `_system/execution-plan.md`
2. Find the first unchecked item `- [ ]`
3. Check whether it is `[REVIEW]` or `[WRITE]`:
   - **`[REVIEW]`** — file has existing content; run all five passes (A→B→N→D→C) and fix every failure
   - **`[WRITE]`** — file is a stub or empty; write the full page from scratch, then run all five passes
4. Complete the page fully (see Definition of Done below)
5. Check the box in `execution-plan.md`: `- [ ]` → `- [x]`
6. Update `_system/progress.md`: change the page status to ✅
7. Commit with format: `[REVIEW] quality-assurance.md — five-pass complete` or `[WRITE] medical-cnc-machining.md — full page written and five-pass complete`
8. Push to branch `claude/intelligent-goldberg-nLhvz`
9. **Stop.** Do not move to the next item automatically. The user will run the agent again.

---

## Definition of Done (Every Page)

A page is done when ALL of the following are true:

- All five passes run (A → B → N → D → C) and all failures resolved
- No banned claims (check `CLIENT-DATA-MAP.md` → "Claims — DO NOT USE")
- Brand name is "WeldoCNC" everywhere — not "Weldo CNC", not "Weldo"
- Every number traces to `CLIENT-DATA-MAP.md`
- Pass log added to the top of the file
- `_system/execution-plan.md` checkbox ticked
- `_system/progress.md` updated to ✅
- Changes committed and pushed

---

## Git

- Branch: `claude/intelligent-goldberg-nLhvz`
- Always push to this branch
- One page per commit — never batch multiple pages in one commit
- Push command: `git push -u origin claude/intelligent-goldberg-nLhvz`
