# Surface Finish Page Template — Weldo CNC

> Use this file as the structural blueprint for EVERY surface finish sub-page.
> e.g. anodizing-cnc-machining-services.md, powder-coating-cnc-machining-services.md, passivation-cnc-machining-services.md
>
> Do not invent new sections. Do not skip sections. Do not reorder sections.
> Content inside each section changes per finish — the structure does not.
>
> This template is for SURFACE FINISH pages only.
> For SERVICE pages use: _system/service-template.md
> For METAL MATERIAL pages use: _system/material-metal-template.md
> For PLASTIC MATERIAL pages use: _system/material-plastic-template.md

---

## Section Count: 15 sections + internal links

> Surface finish pages are 15 sections — shorter than service pages (18) and material pages (17).
> No Blog section — finish pages are transactional. Buyers arriving here know what they want.
> No Plastics pills or Metals pills — replaced by Compatible Materials table (Section 6) and Finish Specifications table (Section 7).

---

## Section 1: Hero
**Design:** 50/50 split. Text left, finished part or finishing process image right. White background.
- Label tag (small tag above H1): `[FINISH NAME]`
- H1: [Finish Name] for CNC Machined Parts
- Subheading: 1–2 sentences. What the finish does + key compatible material + output spec (thickness, hardness, Ra). No banned claims.
- Trust badges: ✔ ISO 9001:2015 Certified | ✔ Tolerances to ±0.005 mm | ✔ Quote in 24 Hours
- CTA Primary: Upload your STEP file and get a finishing quote in 24 hours
- CTA Secondary: View finish specifications
- Alt text: Weldo CNC [finish name] — [specific part description and finish result] in Dongguan facility

---

## Section 2: Stats Bar
**Design:** 4-stat callouts. Dark background. Full width.
- Stat 1: 100+ | CNC Machines In-House
- Stat 2: 50+ | Surface Finish Options
- Stat 3: 24 hrs | Quote Turnaround
- Stat 4: 97.48% | Annual Pass Rate

> The stats bar for finish pages uses "50+ Surface Finish Options" instead of a tolerance stat — tolerance is a machining spec, not a finishing spec.
> DO NOT USE: "20+ Years", "From 3 Days", "From 4 Days", "From 5 Days" — all banned.

---

## Section 3: What is [Finish Name]?
**Design:** H2 left-aligned. 2-column — body text left, image right. White background.
**H2:** What is [Finish Name]?

**MUST open with AI-quotable paragraph** (self-contained, contains all of):
- Brand name: Weldo CNC
- Finish name
- What it does in one sentence (process description)
- Compatible base material(s)
- Key output spec: thickness range / hardness / Ra improvement
- Location: Dongguan, China
- Certification: ISO 9001:2015

Then 3 additional paragraphs:
- Para 2: Plain-English explanation of how the process works — what happens to the surface at a physical/chemical level
- Para 3: What separates a well-executed finish from a poor one — pre-treatment quality, process control, masking precision, dimensional awareness
- Para 4: When this finish is the engineering answer — specific applications where it's the standard or preferred specification + operating since 2012

---

## Section 4: [Finish Name] Types / Variants
**Design:** H2 centred + subheading. 3-column card grid. Light grey background.
**H2:** Types of [Finish Name]
**Subheading:** 1 sentence — variant selection is determined by the functional requirement, not preference.

3 cards — one per major variant of this finish. Each card:
- Bold heading: variant name
- Body: 3–5 sentences — what this variant does, what it's right for, what its limits are, how it differs from the other variants
- Spec line: Key output spec (thickness / hardness / Ra / colour options)

Examples:
- Anodizing: Type II (standard) | Type III Hard Coat | Colour Anodizing
- Nickel Plating: Electroless Nickel | Electrolytic Nickel | EN with PTFE (composite)
- Passivation: Citric Acid Passivation | Nitric Acid Passivation | Electropolishing (as premium variant)
- Powder Coating: Polyester | Epoxy | Polyurethane

> If a finish has fewer than 3 meaningful variants, use 2 cards and add a third card titled "Choosing the Right [Finish] Specification" that covers how to specify the finish on a drawing.

---

## Section 5: When [Finish Name] is the Right Choice
**Design:** H2. 2-column comparison. White background.
**H2:** [Finish Name] or [Alternative Finish] — Which is Right for Your Part?

Two columns:
- **Specify [Finish Name] When:** 3–4 bullet scenarios where this finish wins (corrosion resistance, hardness, appearance, regulatory requirement, dimensional tolerance) + 3 example part types
- **When an Alternative May Win:** 3–4 bullet scenarios where a different finish is a better engineering choice + which finish to consider instead

Closing note: If the part sits on the boundary, send the STEP file with the operating environment and any relevant standards — the right finish will be confirmed before quoting.

---

## Section 6: Compatible Base Materials
**Design:** H2. Full-width table. Light grey background.
**H2:** Compatible Materials for [Finish Name]

Intro sentence: Not all finishes bond to all metals — compatibility depends on alloy chemistry and surface preparation.

**Compatibility table** (columns: Material | Compatible | Notes):
- List all metals and plastics that are relevant to this finish
- Compatible column: ✅ Yes / ⚠️ Conditional / ❌ No
- Notes column: explain any conditional compatibility (e.g. "cast aluminium anodizes poorly due to silicon content"), required pre-treatment, or grade-specific considerations

Common materials to include in every finish compatibility table:
Aluminium (wrought) · Aluminium (cast) · Stainless Steel · Carbon Steel · Alloy Steel · Titanium · Brass · Copper · PEEK · ABS · Polycarbonate

---

## Section 7: [Finish Name] Specifications
**Design:** H2. 2-column specs table. White background.
**H2:** [Finish Name] Specifications

**Specifications table** (2 columns: Specification | Detail):
Include all relevant specifications — adapt per finish:
- Coating thickness range (min / standard / max)
- Surface hardness (where applicable — e.g. HRC for hard anodizing)
- Surface roughness (Ra) — before and after finish
- Dimensional impact: how much does the finish add to part dimensions (critical for bores and fits)
- Colour options (if applicable)
- Temperature resistance
- Corrosion resistance rating (salt spray hours if confirmed)
- Relevant standards met (e.g. MIL-A-8625 for anodizing, AMS 2404 for electroless nickel)
- Masking availability (yes/no — for threaded holes, bores, sealing faces)

> All specifications must be confirmed or traceable. Do not invent salt spray hours, hardness values, or thickness ranges.
> Where CLIENT-DATA-MAP does not confirm a value, write the range from published standards and note "confirm with Weldo CNC for your alloy and application."

---

## Section 8: Design Guidelines for [Finish Name]
**Design:** H2 + subheading. Full-width 3-column table (Feature | Recommendation | Why It Matters) + 2 supporting paragraphs below. White background.
**H2:** Design Guidelines for [Finish Name]
**Subheading:** Finish is applied after machining — design decisions made before cutting affect finish quality and dimensional outcome.

Table: minimum 6 rows, maximum 10 rows. Must be specific to this finish. Include:
- Bore/hole tolerances: how to account for coating build-up (e.g. anodizing adds ~0.025 mm per side — machine bores 0.05 mm oversize)
- Thread protection: always mask threads before finishing — coating inside threads causes galling or assembly failure
- Sharp edges vs radii: most finishes cover edges better with a small radius (0.5 mm min) — sharp edges cause thin spots
- Surface finish before finishing: required pre-finish Ra for this process (e.g. electropolishing requires Ra ≤ 1.6 µm before treatment)
- Material condition: heat treatment or work hardening state that affects finish adhesion or result
- Masking specification: how to call out masked areas on the drawing
- Alloy-specific note: any grade within the material family that finishes poorly (e.g. 2024 aluminium anodizes poorly vs 6061)

Supporting paragraphs (2):
- Para 1: The most common finish failures caused by design decisions — incorrect bore sizing, unmasked threads, wrong pre-finish Ra, incompatible alloy — and how to avoid them
- Para 2: How finish requirements are reviewed at quote stage — dimensional impact checked before machining starts, masking confirmed on drawing

---

## Section 9: Applications & Industries
**Design:** H2. Left column: applications table. Right column: industry icon/label grid. White background.
**H2:** [Finish Name] Applications

**Applications table** (2 columns: Category | Typical Parts & Why This Finish):
Minimum 6 rows. The "Why This Finish" column is key — explain what property of this finish makes it the right choice for that application. Not just "used for" but "specified because of corrosion resistance / hardness / appearance / regulatory requirement."

**Industry card labels** (icon grid, each links to industry page):
List 6–8 industries where this finish is commonly specified. Lead with the 2–3 industries most associated with this finish.

---

## Section 10: Our CNC Machining Services
**Design:** H2 centred. 5-column service card grid. Icon + title + description per card. White or light grey background.
**H2:** Our CNC Machining & Fabrication Services

5 fixed cards — always the same. Positions this finish within the full machining workflow.
1. CNC Milling — 3-axis to 5-axis, prismatic and complex geometries, ±0.005 mm
2. CNC Turning — 2-axis, live tooling, Swiss. Concentricity and runout to drawing callout
3. 5-Axis CNC Machining — Complex geometries in one setup, ±0.003 mm
4. Precision Machining — Grinding and EDM for tight flatness and hardened profiles
5. Surface Finishing — 50+ finish options including [this finish name] and more

---

## Section 11: Quality & Certifications
**Design:** RS-01. Dark navy background. White text. H2 + 3-step checklist.
**H2:** Quality Control & Finish Inspection

Three steps — adapt to finishing context:

**Step 1 — Pre-Finish:**
Heading: Part Condition Verified Before Finishing
Body: Machined part inspected before finish application — dimensional check against drawing, surface condition checked for contamination or tool marks that would affect adhesion. Masking verified against drawing callout. Any issue flagged before the part enters the finish line.

**Step 2 — In-Process:**
Heading: Process Parameters Monitored Throughout
Body: Bath chemistry, temperature, and current density (for electrochemical finishes) or powder gun settings (for coating) monitored at defined intervals. NCR — Non-Conformance Report — triggered on any process deviation before batch continues.

**Step 3 — Post-Finish Inspection:**
Heading: Finish Thickness and Adhesion Verified Before Shipment
Body: Coating thickness measured — confirm within specified range. Visual inspection for coverage, adhesion, and colour uniformity. Dimensional check on critical features after finishing — bore diameters and fits re-verified where coating build-up affects function. Results documented and shipped with part.

Footer link: → View the full quality assurance process → [[quality-assurance]]

---

## Section 12: Gallery
**Design:** Eyebrow label + H2. Masonry image grid 6–8 photos. Light grey background.
**Eyebrow label:** OUR WORK
**H2:** [Finish Name] Parts from Weldo CNC

6–8 image alt texts — each must include:
- Brand: Weldo CNC
- Base material + grade
- Part type
- Finish variant applied (e.g. Type III hard anodized, not just "anodized")
- Colour or appearance note where relevant

---

## Section 13: Why Choose Weldo CNC for [Finish Name]
**Design:** H2. 2-column — large feature card left (with stat/number), accordion items right. White background.
**H2:** Why Engineers Specify Weldo CNC for [Finish Name]

**Large feature card (left — prominent, with stat):**
Stat: Since 2012
Heading: [X]-plus years applying [finish name] to precision machined parts.
Body: 2–3 sentences with specific part types finished + consequence of a finish failure + experience signal (dimensional control post-finish, documentation).

**Accordion items (right — exactly 5 items):**
Each item: bold title + 2–4 sentence body.
1. Finish is specified at quote stage — dimensional impact calculated before machining starts
2. [Finish-specific differentiator — e.g. masking precision for anodizing, bath chemistry control for electroless nickel, pre-treatment cleaning for passivation]
3. Dimensional checks after finishing — bores and fits re-measured post-coat
4. Direct facility — machining and finishing at the same site, no handoff
5. Full documentation: finish thickness record, material cert, and dimensional report ship together

Do not open any item with "We". Lead with the benefit or the fact.

---

## Section 14: FAQ
**Design:** H2. Accordion. White background. First item open.
**H2:** [Finish Name] — Frequently Asked Questions

Exactly 10 questions. Must cover all 8 required topics:
1. Tolerances — how does this finish affect part dimensions and how is it managed
2. Process explanation — what [finish name] is and how the process works
3. Material options — which base materials are compatible
4. Lead time — how long does finishing add to the total order lead time
5. Order volume — no MOQ, single parts accepted
6. File formats — STEP + drawing with finish callout required, how to specify masking
7. Cost / pricing factors — what drives the cost of this finish (part size, masking complexity, colour, variant)
8. Comparison — vs the most common alternative finish (e.g. anodizing vs powder coating, passivation vs electropolishing)

Remaining 2 questions: finish-specific (e.g. colour matching for anodizing, salt spray rating for passivation, REACH/RoHS compliance for nickel plating, thread protection for powder coating)

---

## Section 15: Final CTA
**Design:** RS-03. Full-width dark navy. H2 + subtext + bullets + single CTA button.
**H2:** Get a Quote for [Finish Name] on Your CNC Machined Parts — 24 Hours

**Subtext:** 1–2 sentences — upload STEP file + specify finish variant + masking requirements + quantity. Dimensional impact calculated before machining starts.

**Bullets:** 4–5 ✅ bullets. Must include:
- ISO 9001:2015 certified facility — machining and finishing under one quality system
- [Finish-specific capability — e.g. "Type II and Type III hard anodizing for aluminium to MIL-A-8625"]
- Coating thickness verified and documented on every finishing order
- 97.48% annual pass rate across all CNC machining and finishing orders
- Dimensional check post-finish on critical bores and fits

**CTA Button:** Upload Your File and Get a Quote

---

## Internal Links (Silo)
**Up:** [[surface-finishing-services]] | [[custom-cnc-machining-services]]
**Compatible Materials:** metal material pages this finish applies to
**Related Finishes:** other finish pages (e.g. anodizing page links to powder coating, bead blasting)
**Services:** [[cnc-milling-services]] | [[cnc-turning-services]] | [[5-axis-cnc-machining-services]]
**Quality:** [[quality-assurance]]

---

## Rules — Apply to Every Surface Finish Page

- Brand name: **Weldo CNC** everywhere — two words, capital W, capital C
- Every specification traces to CLIENT-DATA-MAP.md or a published industry standard — if not confirmed, write the standard range and add "confirm for your alloy and application"
- Banned stats: "20+ Years", "From 3 Days", "From 4 Days", "From 5 Days"
- AI-quotable paragraph: must appear at the start of Section 3
- FAQ: exactly 10 questions covering all 8 required topics
- Stats bar S2: use "50+ Surface Finish Options" — not a tolerance stat
- Compatibility table (Section 6): use ✅ / ⚠️ / ❌ — never claim a finish works on an incompatible material
- Design guidelines (Section 8): must address dimensional impact of this finish on bores and fits — this is the most critical design issue for finished machined parts
- No Blog section — finish pages are transactional (15 sections, not 17)
- Acronyms: expand NCR, DFM, CMM, EN (electroless nickel) on first use in every page
- No "We" openers in Section 13 accordion items — benefit or fact first
- Pass log: append at end of file after all five passes complete (A→B→N→D→C)

---

## Differences vs Service Template and Material Templates

| | Surface Finish Pages | Metal Material Pages | Service Pages |
|---|---|---|---|
| Sections | 15 | 17 | 18 |
| S4 | Finish Variants/Types | Grades & Specs table | Process Variants |
| S5 | When this finish vs alternative | Trade-off cards | When-to-use comparison |
| S6 | Compatible Materials table | Our CNC Services | Our CNC Services |
| S7 | Finish Specifications table | Capabilities & Tolerances | Capabilities & Tolerances |
| S8 | Design Guidelines (finish-specific) | Surface Finishes (pills) | Metals (pills) |
| S9 | Applications & Industries | Related Materials (pills) | Plastics (pills) |
| S10 | Our CNC Services (workflow context) | DFM Guidelines | Surface Finishes |
| Blog section | ❌ Not included | ✅ S16 | ✅ S17 |
| Stats bar S2 | 50+ Finish Options | ±0.005 mm tolerance | ±0.005 mm tolerance |
