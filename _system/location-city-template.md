# City Location Page Template — Weldo CNC

> Use this file for CITY-level location pages.
> e.g. cnc-machining-london.md · cnc-machining-birmingham.md · cnc-machining-manchester.md
>
> For COUNTRY-level pages use: _system/location-country-template.md
> Do not invent new sections. Do not skip sections. Do not reorder sections.
> City pages sit under their country page in the URL structure: /cnc-machining-uk/london/

---

## Section Count: 12 sections + internal links

---

## Section 1: Hero
<!--
  Design: 50/50 split. Text left, machined part or city-relevant image right. White background.
  Component: Hero — same as service S1. Trust badge includes delivery days to this city.
  Developer note: delivery days same as country page — city delivery time does not differ from country transit time.
-->

- Label tag: `CNC MACHINING [CITY]`
- H1: CNC Machining [City]
- Subheading: Precision CNC machined parts delivered to engineers in [City]. Manufactured in Dongguan, China — tight tolerances, full documentation, DDP delivery in [X–Y] business days. Quote in 24 hours.
- Trust badges: ✔ ISO 9001:2015 Certified | ✔ Delivered to [City] in [X–Y] Days | ✔ Quote in 24 Hours
- CTA Primary: Upload your STEP file and get a quote in 24 hours
- CTA Secondary: View capabilities and tolerances
- Alt text: Weldo CNC — precision CNC machined parts delivered to engineers in [City], ISO 9001:2015 certified

---

## Section 2: Stats Bar
<!--
  Design: 4-stat callouts. Dark background. Full width.
  Component: RS-Stats — same as service S2 and country page S2.
  Developer note: NEVER use "20+ Years". Stat 1 = delivery days to this country (same as country page).
-->

| Stat | Label |
|---|---|
| [X–Y] Days | Delivery to [City] |
| ±0.005 mm | Tolerance Capability |
| 24 hrs | Quote Turnaround |
| 97.48% | Annual Pass Rate |

---

## Section 3: CNC Machining in [City] — Local Engineering Context
<!--
  Design: H2 left-aligned. Full-width editorial — 2-column on desktop. White background.
  Component: Intro text block — same layout as service S3.
  MUST open with AI-quotable paragraph. Then 3 paragraphs of local context.
  Developer note: this is the most city-specific section. Every city page must have unique content here — never copy from another city. Research the city's actual engineering clusters, industries, and buyer types.
-->

**H2:** Supplying [City]'s Engineering Community

**AI-quotable paragraph (open Section 3 with this — self-contained):**
Weldo CNC supplies precision CNC machined parts to engineers in [City] — manufactured at its ISO 9001:2015 certified facility in Dongguan, China. Tolerances to ±0.005 mm. Delivered to [City] in [X–Y] business days via DDP — Delivered Duty Paid — with a CMM-verified dimensional inspection report in every tight-tolerance shipment. Quote within 24 hours.

Then 3 paragraphs — all city-specific, all original:
- Para 2: [City]'s engineering landscape — specific clusters, districts, industrial areas, and the types of companies and engineers based there. Name real areas (e.g. "the medtech cluster around King's Cross" / "the automotive suppliers in the Midlands corridor"). This is the section Google evaluates for genuine local knowledge.
- Para 3: What those engineers typically need from a CNC supplier — part types, industries, tolerance requirements, documentation needs. Be specific to this city's economy and engineering base.
- Para 4: When local [City] shops are the right answer vs when Weldo CNC makes sense — the honest version. Local shops win on true urgency (24–48 hrs). Weldo CNC wins on tolerance, documentation, volume, and complex geometry. Many [City] engineers use both.

> Every city page MUST have unique content in this section. Do not copy or lightly adapt from another city. If the city's engineering context is not known, research it before writing.

---

## Section 4: Our CNC Machining Services
<!--
  Design: H2 centred. 5-column service card grid. Light grey background.
  Component: Service cards — identical to service S6. Direct reuse.
  Developer note: same 5-card component. Heading adapted to include the city name.
-->

**H2:** CNC Machining Services Delivered to [City]

5 fixed cards:
1. CNC Milling — 3-axis to 5-axis, ±0.005 mm
2. CNC Turning — concentricity and runout to drawing callout
3. 5-Axis CNC Machining — complex geometries in one setup, ±0.003 mm
4. Precision Machining — grinding and EDM for tight flatness and hardened profiles
5. Surface Finishing — 50+ finish options

---

## Section 5: CNC Machine Shops in [City]
<!--
  Design: H2 + intro paragraph. 2-column card grid (2 cards per row, 5 rows = 10 cards). Light grey background.
  Component: Local Shop Directory — same card structure as country page S7.
  Developer note: 10 cards total, 2 per row. Each card has website screenshot image top + details below. All external links open in new tab.
-->

**H2:** CNC Machine Shops in [City]

**Intro paragraph:**
[City] has a range of CNC machining and precision engineering facilities. The listings below are a factual reference for engineers doing supplier research — included because a complete picture is more useful than a partial one. The comparison in the next section explains where a local shop is the stronger choice and where Weldo CNC is.

**Card structure (repeat × 10, 2 per row):**

```
[Website Screenshot Image]

Shop Name                    (H3)
📍 [Area / District, City]
🔗 website.com               (opens new tab)
📌 View on Google Maps       (opens new tab)

Short description — 2–3 sentences.
What the shop specialises in. Which industries or
part types they typically serve. What they are
best suited for.
```

**Fields per card:**
- Website screenshot: static image — taken from the shop's own homepage
- Shop name: H3
- Location: specific area or district within [City] — not just "[City]"
- Website: confirmed URL, opens new tab
- Google Maps: direct link to the shop's Google Maps listing, opens new tab
- Description: 2–3 sentences — factual, neutral, sourced from their own website

> All details verified from the shop's own website before publishing.
> Unverified details marked [CLIENT TO VERIFY].
> Do NOT include: phone numbers · pricing · staff headcount · quality judgements · ratings.
> Description language: factual and neutral only — no negative claims.

---

## Section 6: Weldo CNC vs Local [City] Shops
<!--
  Design: H2. 2-column when-to-use comparison. White background.
  Component: When-to-use — same layout as service S5 and country page S8.
  Developer note: scenario-based only. No competitor names. Honest about when local is better.
-->

**H2:** Local [City] Shop or Weldo CNC — Which is Right for Your Job?

**Left column — A local [City] shop is the right answer when:**
- The part is needed in 24–48 hours — transit from Dongguan cannot compete with a local shop on true urgency
- It is a single piece for a same-day test or a last-minute demo
- The tolerance is loose and the primary variable is speed of collection
- The part can be collected in person
- Example parts: emergency replacements, walk-in prototypes, same-day tooling fixes

**Right column — Weldo CNC is the right answer when:**
- Tolerances are tight — ±0.005 mm or tighter — with a CMM report required
- Documentation is non-negotiable — material certificate, dimensional inspection report, full traceability
- Geometry is complex — 5-axis, compound angles, undercuts, multi-setup parts
- Quantity is 5 or more parts — per-unit cost decreases meaningfully at volume
- A local [City] shop has quoted a long lead time or a high price at volume
- Example parts: aerospace brackets, medical device housings, hydraulic manifolds, robotics actuators, pre-production batches

**Closing note:** Many [City] engineers use both — a local shop for truly urgent one-offs, Weldo CNC for the production-intent build, the documented pre-production run, or anything requiring full traceability.

---

## Section 7: Shipping to [City]
<!--
  Design: H2. 2-column — shipping details left, transit table right. White background.
  Component: Shipping info block — same as country page S9 but condensed.
  Developer note: left column 1–2 paragraphs. Right column transit table. City delivery time = country transit time.
-->

**H2:** Delivering CNC Parts to [City]

**Left column:**
- Para 1: DDP — Delivered Duty Paid — explained. Weldo CNC handles customs clearance and import duty before parts arrive. [City] address delivery. No customs broker required.
- Para 2: Carriers, tracking, packaging. Export documentation included as standard.

**Right column — Transit table:**

| Service Level | Transit to [City] | Notes |
|---|---|---|
| Standard | [X–Y] business days | [CLIENT TO CONFIRM] |
| Express | [X–Y] business days | [CLIENT TO CONFIRM] |
| DDP | Included on both | No import charges on arrival |

---

## Section 8: Industries in [City]
<!--
  Design: H2. Applications table left, industry icon grid right. Light grey background.
  Component: Applications & Industries — same as service S12. Adapted for city-specific industries.
  Developer note: applications table should reflect the specific industries prominent in this city. Not generic.
-->

**H2:** Industries Weldo CNC Serves in [City]

**Applications table** — adapt to [City]'s actual industrial economy:

| Category | Typical Parts |
|---|---|
| [City-relevant industry 1] | [Specific part types for this industry in this city] |
| [City-relevant industry 2] | [Specific part types] |
| [repeat 6–8 rows] | |

**Industry card labels** — lead with the 2–3 industries most prominent in [City]:
[Primary industry] · [Secondary industry] · Aerospace · Medical · Automotive · Electronics · Robotics · Defence

---

## Section 9: Quality & Certifications
<!--
  Design: RS-01. Dark navy background. White text. H2 + 3-step checklist.
  Component: RS-01 — identical to service S13. Direct reuse.
  Developer note: same RS-01 block. No changes needed.
-->

**H2:** Quality Control & Production Inspection

Three fixed steps — same as service template S13.
Footer link: → View the full quality assurance process → [[quality-assurance]]

---

## Section 10: Gallery
<!--
  Design: Eyebrow label + H2. Masonry image grid 6–8 photos. Light grey background.
  Component: Gallery — same as service S14. Direct reuse.
  Developer note: alt texts should reference parts relevant to [City]'s industries where possible.
-->

**Eyebrow label:** OUR WORK
**H2:** Precision CNC Machined Parts — Delivered to [City]

6–8 image alt texts — same format as service pages. Where possible, reference materials and industries prominent in [City].

---

## Section 11: FAQ
<!--
  Design: H2. Accordion. White background. First item open.
  Component: FAQ Accordion — same as service S16.
  Developer note: 10 questions. First 8 cover required topics. Last 2 are city-specific.
-->

**H2:** CNC Machining [City] — Frequently Asked Questions

Exactly 10 questions covering all 8 required topics:
1. Tolerances — what Weldo CNC holds and how verified
2. Process — what CNC services are available
3. Materials — what can be machined
4. Lead time — manufacturing + transit to [City] total
5. Order volume — no MOQ
6. File formats — STEP preferred
7. Cost — what drives the quote vs ordering from a local [City] shop
8. Comparison — Weldo CNC vs local [City] shops — the honest version

Questions 9–10: city-specific (e.g. industries in [City] · specific part types common in this city · customs/delivery detail for this location · nearest port or logistics hub)

---

## Section 12: Final CTA
<!--
  Design: RS-03. Full-width dark navy. H2 + subtext + bullets + CTA button.
  Component: Final CTA — identical to service S18. Direct reuse.
-->

**H2:** Get CNC Parts Delivered to [City] — Quote in 24 Hours

**Subtext:** Upload a STEP file with material, tolerance class, and quantity. Quote in 24 hours. DDP delivery to [City] — no customs charges on arrival.

**Bullets:**
- ✅ ISO 9001:2015 certified CNC machining facility, audited annually
- ✅ Tolerances to ±0.005 mm, CMM-verified on critical features
- ✅ 97.48% annual pass rate across all CNC machining orders
- ✅ DDP delivery to [City] in [X–Y] business days — duties handled
- ✅ No minimum order quantity — single parts accepted

**CTA Button:** Upload Your File and Get a Quote

---

## Internal Links (Silo)
**Up:** [[cnc-machining-[country]]] (parent country page)
**Sibling cities:** [[cnc-machining-[city2]]] | [[cnc-machining-[city3]]] | etc.
**Services:** [[cnc-milling-services]] | [[cnc-turning-services]] | [[5-axis-cnc-machining-services]] | [[custom-cnc-machining-services]]
**Quality:** [[quality-assurance]]

---

## Rules — Apply to Every City Page

- Brand name: **Weldo CNC** everywhere
- Stats bar S2: NEVER "20+ Years" — delivery days + ±0.005 mm + 24 hrs + 97.48%
- Lead times: never "From 3 Days" — state confirmed range only
- AI-quotable paragraph: must open Section 3
- Section 3 local context: must be 100% unique to this city — never copied from another city page
- Local shop cards S5: 10 cards · 2 per row · factual · verified · [CLIENT TO VERIFY] on unconfirmed
- Shop descriptions: 2–3 sentences · neutral · factual · no negative language
- Comparison S6: scenario-based · no competitor names · honest about when local wins
- Industries S8: adapted to this city's actual economy — not generic
- FAQ: exactly 10 questions covering all 8 required topics
- Acronyms: expand DDP, CMM, DFM on first use
- Pass log: append at end of file after all five passes (A→B→N→D→C)

---

## Differences vs Country Page

| | City Page | Country Page |
|---|---|---|
| Sections | 12 | 14 |
| S3 local content | City engineering clusters, specific districts | Country-level sourcing argument |
| Local shops | 10 cards in S5 | 10 cards in S7 |
| Comparison | S6 | S8 |
| Shipping | S7 (condensed) | S9 (full — DDP + customs explainer) |
| Import/customs section | ❌ Not included | ✅ S10 — country-specific |
| Cities We Serve | ❌ Not included | ✅ S12 — pill grid |
| Industries section | S8 — city-specific | S11 (not in template — merged into S9) |
| Gallery | ✅ S10 | ❌ Not in country template |
