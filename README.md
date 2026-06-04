# WeldoCNC — Project Rules
> Load `WritingSystem.md` + `CLIENT-DATA-MAP.md` before writing any page.

## Core Files
| File | Purpose |
|---|---|
| `_system/WritingSystem.md` | Brand voice, banned words, quality checks, SEO, GEO/AI SEO, E-E-A-T |
| `_system/CLIENT-DATA-MAP.md` | All verified specs, numbers, and approved authority claims |
| `_system/design.md` | Component library and page templates |
| `_system/sitemap.md` | Master URL and silo map |
| `_system/reusablesections.md` | Reusable section library — check before every new page |

## Workflow
1. **Brief** — target keyword, buyer segment, key specs from `CLIENT-DATA-MAP.md`, objections to answer
2. **Outline** — section list with keyword slot map. Wait for approval.
3. **Write section by section** — after each section run all 5 Tier 1 checks (`WritingSystem.md §7`), then present to user
4. **Confirm before file edit** — do not update any `.md` file until user confirms ("confirm" / "yes")
5. **Compile full page** — run four-pass system (`WritingSystem.md §7 Tier 2`)
6. **Present final** — user approves, then save to file and update `sitemap.md`

## File Rules
- Every page: Status + Meta block at top · section checklist · section content
- Naming: kebab-case (`cnc-milling-services.md`)
- H1: pure exact keyword — no decoration
- After each page: note reusable sections in `reusablesections.md`

## Folder = Custom Post Type
| Folder | Type |
|---|---|
| General Pages | Static pages |
| Services | Service pages |
| Blogs | Blog posts |
| Locations | Location pages |
| Industries | Industry silo pages |
| Case Studies | Case study pages |
