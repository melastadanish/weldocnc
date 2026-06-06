# Loop Instructions — Auto-Resume Guide

> This file tells a new Claude Code session exactly what to do when it starts.
> It is maintained by the agent — do not edit manually.

---

## Purpose

The user has requested a continuous writing loop:
- Work through all remaining phases in order
- After all phases are complete, do a full content review, then stop
- Each session should pick up from exactly where the previous session stopped
- Sessions restart approximately every 3 hours

---

## How to Resume a Session

1. Read this file (`_system/loop-instructions.md`)
2. Read `_system/execution-plan.md` — find the **first unchecked item** in the current phase
3. Read `_system/WritingSystem.md`, `_system/CLIENT-DATA-MAP.md`, `_system/competitors.md`
4. For the page type, read the relevant template (see CLAUDE.md for the full list)
5. Write the page, commit, push, tick the box in execution-plan.md
6. Continue to the next unchecked item without stopping
7. When a phase is complete: update the Phase Summary in execution-plan.md, update progress.md
8. Move to the next phase and continue
9. When ALL phases are complete: run a final review pass (see "Final Review" below)

---

## Current State — Last Updated 2026-06-06

**Phase 4 is IN PROGRESS.**

### Phase 4 status:

| Group | Pages | Status |
|---|---|---|
| CNC Milling Materials | 11 / 11 | ✅ COMPLETE |
| CNC Turning Materials | 0 / 8 | ⬜ NOT STARTED — **START HERE** |
| 5-Axis Materials | 0 / 6 | ⬜ Not started |
| Custom CNC Metals | 0 / 13 | ⬜ Not started |
| Custom CNC Plastics | 0 / 10 | ⬜ Not started |
| Custom CNC Surface Finishes | 0 / 7 | ⬜ Not started |

### Next page to write:

`Services/CNC Turning Services/Materials/aluminium-cnc-turning-services.md`

**Template to use:** `_system/material-metal-template.md` (for metal pages)
**Template to use:** `_system/material-plastic-template.md` (for plastic pages)

---

## Phase Order (after Phase 4)

| Phase | What | Pages |
|---|---|---|
| 4 | Service material pages (L2) — CURRENT | 50 remaining |
| 5 | Industry sub-pages (part type pages) | 41 |
| 6 | Location pages (USA, Germany, France, UK service sub-pages) | 15+ |
| 7 | Blog pages | 12 |
| 8 | Case studies | BLOCKED — skip until client provides data |

---

## CNC Turning Materials — Writing Order

1. `aluminium-cnc-turning-services.md` — metal template, grades: 6061, 7075, 2024, 5052, 6082
2. `stainless-steel-cnc-turning-services.md` — metal template, grades: 303, 304, 316L, 431, 17-4PH
3. `titanium-cnc-turning-services.md` — metal template, grades: TA1 (Gr.1), TA2 (Gr.2), TC4/Ti-6Al-4V (Gr.5)
4. `brass-cnc-turning-services.md` — metal template, grade: C360/CW614N
5. `copper-cnc-turning-services.md` — metal template, grades: C101, C103, C110, BeCu
6. `peek-cnc-turning-services.md` — plastic template, grades: standard, GF30, CF30
7. `delrin-cnc-turning-services.md` — plastic template, grades: Delrin 150, 500, food-grade
8. `nylon-cnc-turning-services.md` — plastic template, grades: PA6, PA66, PA12, GF30

Key adaptation for turning pages vs milling pages:
- Max turning: Ø200 × 500 mm (not the milling 4000×1500×600 mm envelope)
- Turning-specific processes: 2-axis turning, live tooling, Swiss-type turning, turn-mill
- Turning-specific DFM: concentricity, runout, length-to-diameter ratio (max 4:1 without steady rest), parting, grooving
- AI-quotable para mentions "CNC turning" not "CNC milling"
- Stats bar stat 1 = 100+ machines (same), stat 2 = ±0.005 mm (same)

---

## 5-Axis Materials — Writing Order

1. `aluminium-5-axis-cnc-machining-services.md` — metal template
2. `stainless-steel-5-axis-cnc-machining-services.md` — metal template
3. `titanium-5-axis-cnc-machining-services.md` — metal template
4. `brass-5-axis-cnc-machining-services.md` — metal template
5. `peek-5-axis-cnc-machining-services.md` — plastic template
6. `tool-steel-5-axis-cnc-machining-services.md` — metal template

Key adaptation for 5-axis pages:
- Tolerance: ±0.003 mm (5-axis specific, not ±0.005 mm)
- Max envelope same as milling: 4,000 × 1,500 × 600 mm
- 5-axis specific DFM: undercuts, complex geometry in one setup, fewer setups = less datum error
- Highlight 5-axis benefit for each specific material

---

## Custom CNC Metals — Writing Order

Use `_system/material-metal-template.md`. These are process-agnostic (milling + turning + 5-axis all referenced).

1. `aluminium-6061-cnc-machining-services.md` — grade-specific page, focus on 6061 only
2. `aluminium-7075-cnc-machining-services.md` — grade-specific, focus on 7075 only
3. `stainless-steel-cnc-machining-services.md` — overview of all SS grades
4. `316l-cnc-machining-services.md` — grade-specific, 316L only
5. `303-cnc-machining-services.md` — grade-specific, 303 only
6. `titanium-cnc-machining-services.md` — overview of all Ti grades
7. `titanium-grade-5-cnc-machining-services.md` — Ti-6Al-4V specific
8. `titanium-grade-2-cnc-machining-services.md` — TA2 specific
9. `tool-steel-cnc-machining-services.md` — H13, D2, HSS
10. `steel-alloy-cnc-machining-services.md` — 4140, 4340, 1045
11. `brass-cnc-machining-services.md` — C360/CW614N
12. `copper-cnc-machining-services.md` — C101, C103, C110, BeCu
13. `bronze-cnc-machining-services.md` — tin bronze (note: CLIENT-DATA-MAP says "tin bronze [CLIENT TO CONFIRM grade]" — write with honest disclosure)

---

## Custom CNC Plastics — Writing Order

Use `_system/material-plastic-template.md`.

1. `peek-cnc-machining-services.md`
2. `delrin-cnc-machining-services.md`
3. `nylon-cnc-machining-services.md`
4. `polycarbonate-cnc-machining-services.md`
5. `abs-cnc-machining-services.md`
6. `ptfe-cnc-machining-services.md`
7. `acrylic-cnc-machining-services.md`
8. `hdpe-cnc-machining-services.md`
9. `ultem-cnc-machining-services.md` (PEI — note: not in CLIENT-DATA-MAP as confirmed grade; write with standard disclaimer)
10. `polypropylene-cnc-machining-services.md`

---

## Custom CNC Surface Finishes — Writing Order

Use `_system/surface-finish-template.md`.

1. `anodizing-cnc-machining-services.md`
2. `powder-coating-cnc-machining-services.md`
3. `passivation-cnc-machining-services.md`
4. `nickel-plating-cnc-machining-services.md`
5. `bead-blasting-cnc-machining-services.md`
6. `black-oxide-cnc-machining-services.md`
7. `electropolishing-cnc-machining-services.md`

---

## Final Review (after all phases complete)

When all pages in Phases 4–7 are done:

1. Run `git log --oneline -50` to list all committed pages
2. For each page written in this loop (not previously reviewed in Phase 1): re-read and verify:
   - No banned claims
   - "Weldo CNC" spelling correct everywhere
   - All numbers trace to CLIENT-DATA-MAP
   - Pass log present at top
   - 17 sections present (metal/plastic pages) or correct section count for page type
3. Fix any failures found, commit
4. Update progress.md to reflect all ✅ status
5. Update execution-plan.md Phase Summary
6. Commit and push final state
7. **End the loop** — do not continue past this point

---

## Rules That Must Not Be Broken

- `git push origin main` after every commit — no uncommitted work left at session end
- One page per commit — never batch multiple pages in one commit
- Never write content not in CLIENT-DATA-MAP — if a number isn't confirmed, don't write it
- Never claim certifications Weldo CNC doesn't hold (ISO 13485, IATF 16949, AS9100D, ITAR)
- Banned stats: "20+ Years", "From 3 Days", "From 4 Days", "From 5 Days"
- Stats bar: ALWAYS dark background, ALWAYS: 100+ Machines · ±0.005 mm · 24 hrs · 97.48%
- AI-quotable paragraph: MUST be first paragraph of Section 3 of every page
- Spacing: ±0.005 mm (space before mm), Ra 0.8 µm (space before µm)
- Brand: "Weldo CNC" — two words, capital W, capital C — everywhere

---

## Git State

Branch: `main`
Last push: 2026-06-06 (commit eb43c02 — nylon, ABS, polycarbonate pages)
Remote: `origin/main` — confirmed up to date
