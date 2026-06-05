# WeldoCNC — Website Content Repository

Markdown content for the WeldoCNC website. No code lives here — `.md` files only.

## Structure
`General Pages/` · `Services/` · `Industries/` · `Locations/` · `Alternatives/` · `Blogs/` · `Case Studies/`

## System Files
| File | Purpose |
|---|---|
| `_system/WritingSystem.md` | Brand voice, copy rules, five-pass quality system |
| `_system/CLIENT-DATA-MAP.md` | All verified specs and approved claims — single source of truth |
| `_system/competitors.md` | Competitor intelligence for comparison content |
| `_system/execution-plan.md` | Ordered task list — 170+ pages, phased by priority |
| `_system/progress.md` | Page status tracker (✅ done / 📝 needs review / ⬜ not started) |

## Working With Claude
Claude reads `CLAUDE.md` automatically. At session start it will ask: **agent mode or manual mode?**
Agent mode auto-picks the next page from `execution-plan.md`, completes it, and commits.
Manual mode waits for your instructions.
