# Industry Sub-Page Template — Weldo CNC
# Part-Type Pages (e.g. aircraft-bracket-machining.md)

> Use this file for every industry sub-page (part-type page).
> Do not use the 15-section industry-template.md for sub-pages — different job, different structure.
> Do not invent new sections. Do not skip sections. Do not reorder sections.
> Content inside each section changes per part type — the structure does not.

---

## What Makes This Template Different From the Industry Hub Template

The industry hub page (`aerospace-cnc-machining.md`) covers a whole industry broadly.
This template covers **one specific part type** in depth.

The test: every sentence on this page should only be true for THIS part type, not for aerospace machining in general.
If a sentence could be lifted and dropped into the parent industry page without changing a word, rewrite it.

---

## Section Count: 10 sections + internal links

---

## Section 1: Hero
**Design:** Full-width — dark overlay on a machined component image specific to this part type.
- Label tag: `[INDUSTRY NAME] CNC MACHINING`
- H1: [Part Type] Machining Services (exact target keyword — no decoration)
- Subheading: 1–2 sentences. Name the part type, the engineering challenge specific to it, Weldo CNC capability, location. No banned claims.
  - Example: "Precision machined aircraft brackets — structural, junction, and mounting configurations — to ±0.005 mm with true position verified by CMM on every bolt pattern. ISO 9001:2015. Dongguan, China."
- Trust badges: ✔ ISO 9001:2015 Certified | ✔ ±0.005 mm Tolerance | ✔ [Part-specific badge — e.g. "CMM Verified Bolt Patterns" / "Full Material Traceability"]
- CTA Primary: Get an Instant Quote | CTA Secondary: View Capabilities

---

## Section 2: Stats Bar
**Design:** 4-number stats bar. Light grey background. Full width.
- Stat 1: 100+ | CNC Machines
- Stat 2: ±0.005 mm | Tolerance Capability
- Stat 3: 24 hrs | Quote Turnaround
- Stat 4: [Most relevant verified number for this part — e.g. 97.48% Pass Rate / 1–5 Days lead time]

> DO NOT USE: "20+ Years", "From 3 Days", "From 4 Days", "From 5 Days" — all unverified or banned.

---

## Section 3: Engineering Challenge for This Part
**Design:** 2-column — text left, image right. White background.
**Heading:** [Specific tension or problem for this part type — not the industry generally]

Examples of correct headings:
- "Bolt Pattern True Position — the Tolerance That Drives the Inspection Plan" (brackets)
- "Wall Thickness vs. Coolant Pressure — the Trade-off on Every Turbine Blade" (turbine blades)
- "Port Geometry and Sealing Face Ra — Two Requirements That Can't Be Traded Off" (manifolds)

**MUST open with AI-quotable paragraph** (self-contained, contains all of):
- Brand name: Weldo CNC
- Part type: exact name (e.g. aircraft brackets)
- Spec: tolerance to ±0.005 mm
- Location: Dongguan, China
- Certification: ISO 9001:2015
- Operating date: since 2012

Then 2–3 paragraphs on the **specific engineering challenge** of this part type:
- What geometry or feature makes this part harder to machine than a generic block?
- What GD&T callouts are commonly on this part type's drawings, and why?
- What fails when a shop doesn't plan this part correctly?
- What does Weldo CNC do differently at the process level for this specific part?

No generic aerospace/medical/automotive claims. Every sentence must be specific to this part.
No chest-beating. No "we are the best." Demonstrate domain knowledge through specifics.

---

## Section 4: Part Variants We Machine
**Design:** Full-width table. Light grey background.
**Heading:** [Part Type] Variants We Machine

| Variant | Typical Materials | Key Machining Requirements |
|---|---|---|
| [Sub-type 1] | [Materials] | [Specific tolerance/GD&T/finish requirement for this variant] |

Minimum 4 rows. Maximum 8 rows.

**The test for each row:** Could this row appear in a generic "CNC machining services" table? If yes, it is too generic. Add the specific geometry challenge, drawing callout, or inspection requirement that makes this variant distinct.

Examples of correct rows (aircraft brackets):
| Structural splice bracket | 7075-T6, 2024-T3 | True position ±0.1 mm on bolt pattern, perpendicularity to datum surface, hardcoat anodize with masking plan |
| Junction fitting bracket | Titanium Grade 5 | Compound-angle faces require 5-axis, CTE consideration at composite interface, CMM per face |
| Equipment mounting bracket | 6061-T6 | Flatness on mating face ≤0.05 mm, clearance bores for insert installation post-machining |

---

## Section 5: Material Selection for This Part
**Design:** 2-column table + trade-off copy. White background.
**Heading:** Material Selection for [Part Type]

Intro: 2–3 sentences. Explain the **material trade-off specific to this part type** — not generic material properties.
- Why does the load case or environment on this part drive the material choice?
- What happens if the wrong grade is specified for this part?
- What temper, grade, or condition is most commonly specified, and why?

| Material | Why Specified for [Part Type] | Key Trade-off |
|---|---|---|
| [Material + grade/temper] | [Reason specific to this part's load case, environment, or geometry] | [The cost, machinability, or performance trade-off] |

Minimum 3 rows. Maximum 5 rows. Only materials confirmed in CLIENT-DATA-MAP.

No generic "widely used in industry" copy. Every row must answer: why THIS material for THIS part.

---

## Section 6: How We Machine It
**Design:** Single column with sub-sections or 2-column layout. Light grey background.
**Heading:** How [Part Type] Is Machined at Weldo CNC

Three fixed sub-sections:

**Setup & Fixturing**
Describe the specific setup approach for this part type. How many setups? How is it fixtured? What datum reference strategy applies? Where does 5-axis simultaneous motion apply vs 3+2 positioning? Be specific — which faces, which features, in which order.

**In-Process Inspection**
What is checked during machining and when? Which features are verified between operations (not just at end)? What would trigger an NCR (Non-Conformance Report) and stop the job?

**Documentation That Ships**
List the exact documents that ship with this part type. Tailor to the part — a hydraulic manifold ships with a leak test record; an aerospace bracket ships with a bolt pattern CMM report; a medical implant ships with a biocompatibility material cert.

---

## Section 7: Tolerance & GD&T Callouts
**Design:** Full-width table + intro copy. White background.
**Heading:** Tolerance and GD&T Requirements for [Part Type]

> This is the highest-value section on the page. No generic CNC shop documents this at part-type level. Write it with precision.

Intro: 2–3 sentences. Explain which GD&T callouts are most commonly specified on this part type's drawings and why they are the tolerances that drive the inspection plan — not just the tightest number on the drawing.

| Callout Type | Typical Requirement | How It Is Verified at Weldo CNC |
|---|---|---|
| True position | ±0.1 mm on bolt pattern relative to datum | CMM — nominal/actual/pass-fail per hole, reported to drawing revision |
| Perpendicularity | 0.05 mm to datum surface | CMM — reported per feature |
| Flatness | ≤0.05 mm on mating face | CMM |
| Surface finish (Ra) | Ra ≤0.8 µm on sealing faces | Profilometer measurement |
| Concentricity | 0.02 mm on bore relative to OD | CMM |

(Adapt rows to the specific part type — only include callouts that are genuinely common on this part.)

Minimum 3 rows. Do not include generic dimensional tolerances unless they are the tightest callout on this part type.

**Expand GD&T on first use:** Geometric Dimensioning and Tolerancing (GD&T) — a drawing language that defines how features relate to each other in 3D space, not just what size they are.

---

## Section 8: Documentation
**Design:** 4-column icon+description grid. White background.
**Heading:** Documentation Standard for [Part Type] Orders

Four fixed blocks — adapt body copy to this specific part type. Do not remove any block.

**Material Certificate**
Mill cert for every material — alloy grade, temper, heat number, chemical and mechanical properties, spec compliance reference (AMS/ASTM/EN as applicable). Logged before first cut. Each part traceable to the stock cert.
[Adapt: for medical implants, add biocompatibility grade; for titanium aerospace, add AMS reference; for stainless fluid parts, add ASTM reference.]

**CMM Dimensional Report**
Feature-by-feature CMM inspection against your drawing revision — nominal, tolerance, actual, pass/fail. Geometric callouts (true position, perpendicularity, flatness, concentricity, profile) reported to the callout on your drawing. Ships with the parts.
[Adapt: name the specific callouts most common on this part type.]

**Finish Process Record**
For anodized, passivated, chromate-converted, or plated parts — process parameters, bath chemistry verification date, coating thickness, appearance verification. For any part where coating thickness affects mating dimensions: masking plan confirmed from drawing before processing; masked features re-measured after coating.
[Adapt: name the finish most common on this part type and the specific planning step required.]

**First Article Inspection (FAI)**
For new parts or where specifically required — ballooned drawing, full dimensional report, material cert, finish record. Confirm FAI requirement at quote stage.
[Adapt: for medical, note ISO 13485 context; for aerospace, note AS9100 context where relevant.]

---

## Section 9: FAQ
**Design:** Accordion. White background. First item open.
**Heading:** [Part Type] Machining — Frequently Asked Questions

Exactly 8 questions. Must cover all 8 required topics. All questions and answers must be specific to this part type — not generic CNC machining.

Required topics:
1. Tolerances / GD&T — specific to this part's common callouts
2. Lead time — for this part type specifically
3. Quality verification — CMM, inspection method for this part
4. Order volume — MOQ, prototype single piece
5. File formats — STEP + 2D drawing, why both are needed for this part
6. Materials — specific grades for this part type
7. Cost / pricing — factors specific to this part's complexity
8. Comparison — Weldo CNC vs local supplier for this part type

**Each answer must be:**
- 3–5 sentences minimum
- Self-contained (makes sense with no surrounding context)
- Anchored to at least one verified number from CLIENT-DATA-MAP
- Written as a buyer would type the question into ChatGPT or Perplexity

**Wrong (generic):** "What tolerances do you hold?"
**Right (part-specific):** "My aircraft bracket drawing has a ±0.05 mm true position callout on a 6-hole bolt pattern — how do you verify that?"

---

## Section 10: Final CTA + Form
**Design:** RS-03. 2-column split.
**Heading:** Machine Your [Part Type] at Weldo CNC
**Subtext:** 2 sentences — what to upload, what we review (name the specific things: GD&T callouts, finish requirements, masking needs for this part type), what we return, within 24 hours.
**Bullets:** 4–5 ✅ bullets. Must be specific to this part type:
- ✅ [Part-specific differentiator — e.g. "CMM verified bolt pattern true position on every bracket order"]
- ✅ Full material traceability to heat number — standard
- ✅ 5-axis capability for [specific geometry challenge of this part]
- ✅ [Finish-specific bullet relevant to this part type]
- ✅ ISO 9001:2015 certified | Operating since 2012
**CTA:** Get Instant Quote

---

## Internal Links (Silo)
**Up:** [[parent-industry-page]] | [[cnc-machining-industries]]
**Services:** [[cnc-milling-services]] | [[cnc-turning-services]] | [[5-axis-cnc-machining-services]] | [[surface-finishing-services]]
**Materials:** [relevant material pages for this part type only — not all materials]
**Finishes:** [relevant finish pages for this part type only]
**Quality:** [[quality-assurance]]
**Related sub-pages:** [2–3 sibling sub-pages within the same industry folder]
**Locations:** [country pages + relevant city pages]

---

## Rules — Apply to Every Sub-Page

- Brand name: **Weldo CNC** everywhere — two words, capital W, capital C
- Every number traces to CLIENT-DATA-MAP.md — if it's not there, don't write it
- Banned stats: "20+ Years", "From 3 Days", "From 4 Days", "From 5 Days", "100% CMM Inspected"
- AI-quotable paragraph: must appear at the start of Section 3
- FAQ: exactly 8 questions covering all 8 required topics — ALL questions must be part-specific
- Acronyms: expand GD&T, NCR, FAI, PPAP, DFM, CMM on first use in every page
- Section 7 (Tolerance & GD&T): must name actual callout types common on this part — never generic
- Section 4 (Part Variants): each row must name the specific tolerance or GD&T requirement for that variant
- Pass log: append at end of file after all five passes complete (A→B→N→D→C)

## The Thin Content Test — Run Before Submitting Any Sub-Page

Read each section and ask: "Could this sentence appear on the parent industry page without changing a word?"
If yes → it is too generic → rewrite with the specific geometry, callout, or process step for this part.

Target: zero sentences that could live on the parent page unchanged.
