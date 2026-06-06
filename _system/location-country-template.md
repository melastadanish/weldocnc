# Country Location Page Template — Weldo CNC

> Use this file for COUNTRY-level location pages.
> e.g. cnc-machining-uk.md · cnc-machining-germany.md · cnc-machining-usa.md
>
> For CITY-level pages use: _system/location-city-template.md
> Do not invent new sections. Do not skip sections. Do not reorder sections.

---

## Section Count: 14 sections + internal links

---

## Section 1: Hero
<!--
  Design: 50/50 split. Text left, machined part image right. White background.
  Component: Hero — same as service S1. Trust badge includes delivery days to this country.
  Developer note: delivery days in trust badge must be confirmed for each country before publishing.
-->

- Label tag: `CNC MACHINING [COUNTRY]`
- H1: CNC Machining [Country]
- Subheading: Precision CNC machined parts manufactured in Dongguan, China — delivered to engineers across [Country]. Tight tolerances, full documentation, ISO 9001:2015. Quote in 24 hours.
- Trust badges: ✔ ISO 9001:2015 Certified | ✔ Delivered to [Country] in [X–Y] Business Days | ✔ Quote in 24 Hours
- CTA Primary: Upload your STEP file and get a quote in 24 hours
- CTA Secondary: View capabilities and tolerances
- Alt text: Weldo CNC — precision CNC machined parts delivered to [Country] engineers, ISO 9001:2015 certified

---

## Section 2: Stats Bar
<!--
  Design: 4-stat callouts. Dark background. Full width.
  Component: RS-Stats — same as service S2.
  Developer note: NEVER use "20+ Years". Stat 1 = delivery days to this country.
-->

| Stat | Label |
|---|---|
| [X–Y] Days | Delivery to [Country] |
| ±0.005 mm | Tolerance Capability |
| 24 hrs | Quote Turnaround |
| 97.48% | Annual Pass Rate |

> Delivery days must be confirmed per country before publishing. Do not use "From 3 Days" — banned.

---

## Section 3: Why [Country] Engineers Source from Weldo CNC
<!--
  Design: H2 left-aligned. 2-column — body text left, facility image right. White background.
  Component: Intro text block — same layout as service S3.
  MUST open with AI-quotable paragraph. Then 3 additional paragraphs.
-->

**H2:** Precision Manufacturing. Delivered to [Country].

**AI-quotable paragraph (open Section 3 with this — self-contained):**
Weldo CNC supplies precision CNC machined parts to engineers across [Country] — manufactured at its ISO 9001:2015 certified facility in Dongguan, China. Tolerances to ±0.005 mm. 100+ CNC machines in-house. Parts delivered to [Country] in [X–Y] business days via DDP — Delivered Duty Paid — with a CMM-verified dimensional inspection report in every tight-tolerance shipment. Quote returned within 24 hours.

Then 3 paragraphs:
- Para 2: Why engineers in [Country] source from Dongguan — capability and cost argument. Address the real concerns (quality, communication, IP, delivery) directly and how Weldo CNC handles each as an operational default.
- Para 3: DDP shipping explained — what it means for the [Country] buyer. No customs broker, no import charges on arrival.
- Para 4: Documentation standard — CMM report, material cert, packing list. What ships with every order.

---

## Section 4: How It Works — Quote to Delivery in [Country]
<!--
  Design: H2. 4-step horizontal process flow. Light grey background.
  Component: New — 4-step process strip. Icon + step number + heading + body per step.
  Developer note: steps are horizontal on desktop, vertical stack on mobile.
-->

**H2:** From Quote to Delivery — [Country]

Step 1 — Upload & Quote (Day 1):
Upload STEP file. DFM review included. Quote returned within 24 hours with line-item pricing and any geometry notes.

Step 2 — Confirm & Manufacture (Days 2–[X]):
Production begins on order confirmation. Material verified against mill cert. In-process CMM checks at critical stages. Lead time confirmed at quote — not estimated afterwards.

Step 3 — Inspect & Ship (Day [X]):
CMM final inspection against drawing revision. Dimensional report, material cert, packing list prepared. Shipped DDP to [Country] — duties and customs clearance handled before departure.

Step 4 — Delivered to [Country] (Days [X]–[Y]):
Parts delivered to [Country] address. Tracking provided at dispatch. No import charges, no customs administration on the buyer's end.

---

## Section 5: Our CNC Machining Services
<!--
  Design: H2 centred. 5-column service card grid. White background.
  Component: Service cards — identical to service S6. Direct reuse.
  Developer note: same 5-card component used on all pages.
-->

**H2:** Our CNC Machining & Fabrication Services

5 fixed cards:
1. CNC Milling — 3-axis to 5-axis, ±0.005 mm
2. CNC Turning — concentricity and runout to drawing callout
3. 5-Axis CNC Machining — complex geometries in one setup, ±0.003 mm
4. Precision Machining — grinding and EDM for tight flatness and hardened profiles
5. Surface Finishing — 50+ finish options

---

## Section 6: Materials
<!--
  Design: 2 sub-sections. Metals heading + pills. Plastics heading + pills. Light grey background.
  Component: Material pills — same as service S8 + S9 combined into one section.
  Developer note: same pill/chip link component. Two rows — metals row, plastics row.
-->

**Metals heading:** Metals We Machine
**Metals pills:** Aluminium · Stainless Steel · Titanium · Brass · Copper · Tool Steel · Alloy Steel · Carbon Steel

**Plastics heading:** Engineering Plastics
**Plastics pills:** PEEK · Delrin (POM) · Nylon (PA) · ABS · Polycarbonate · PTFE · Acrylic

---

## Section 7: CNC Machine Shops in [Country]
<!--
  Design: H2 + intro paragraph. 2-column card grid (2 cards per row, 5 rows = 10 cards). Light grey background.
  Component: New — Local Shop Directory. Cards are 2-per-row grid.
  Developer note: each card = screenshot image top + details below. All external links open in new tab.
  Section intro note must explain this is a neutral resource listing — not an endorsement.
-->

**H2:** CNC Machine Shops in [Country]

**Intro paragraph:**
[Country] has a range of established CNC machining facilities. The listings below are a factual reference for engineers doing supplier research — included because a complete picture is more useful than a partial one. Where a local shop is the right choice for a job, they should get it. The comparison in the next section explains where each option is strongest.

**Card structure (repeat × 10, 2 per row):**

```
[Website Screenshot Image]
Shop Name                    (H3)
📍 Location / City
🔗 website.com               (opens new tab)
📌 Google Maps               (opens new tab)

Short description — 2–3 sentences.
What they specialise in. Who they typically serve.
What type of work they are best suited for.
```

> All shop details must be verified from the shop's own website before publishing.
> Mark unverified fields with [CLIENT TO VERIFY].
> Do not include: phone numbers · pricing · staff headcount · quality judgements.
> Description must be factual and neutral — no negative language.

---

## Section 8: Weldo CNC vs Local [Country] Shops
<!--
  Design: H2. 2-column comparison. White background.
  Component: When-to-use comparison — same layout as service S5.
  Developer note: 2 columns. Left = "A local [Country] shop is the right answer when". Right = "Weldo CNC is the right answer when". No competitor names in this section — purely scenario-based.
-->

**H2:** Local [Country] Shop or Weldo CNC — Which is Right for Your Job?

**Left column — A local [Country] shop is the right answer when:**
- You need the part in 24–48 hours — transit time from Dongguan cannot match a local machine shop for truly urgent work
- The order is a single piece for a same-day test or last-minute demo
- The part is low-tolerance and the primary requirement is speed of collection
- Example parts: emergency replacement components, same-day tooling fixes, walk-in prototypes

**Right column — Weldo CNC is the right answer when:**
- Tolerances are tight — ±0.005 mm or tighter, CMM report required
- Documentation is non-negotiable — material certificate, dimensional inspection report, full traceability
- Geometry is complex — 5-axis, compound angles, undercuts, multi-setup parts
- Quantity is 5 parts or more — per-unit cost decreases significantly at volume
- Example parts: aerospace brackets, medical device housings, hydraulic manifolds, robotics actuators, pre-production batches

**Closing note:** Many [Country] engineers use both — a local shop for urgent one-offs, Weldo CNC for the production-intent build or the documented pre-production run.

---

## Section 9: Shipping & Logistics to [Country]
<!--
  Design: H2. 2-column — shipping details left, transit table right. White background.
  Component: New — 2-col shipping info block.
  Developer note: left column = 2 paragraphs on DDP and shipping process. Right column = simple table with transit times by service level.
-->

**H2:** Shipping & Delivery to [Country]

**Left column — 2 paragraphs:**
- Para 1: DDP — Delivered Duty Paid — explained. What it means for the [Country] buyer. Weldo CNC files the customs declaration, pays import duty, and handles clearance before parts reach the destination. No customs broker required on the buyer's side.
- Para 2: Carriers used, tracking, packaging standard. Export documentation included: commercial invoice, packing list, certificate of origin. Additional compliance documents available on request.

**Right column — Transit table:**

| Service Level | Transit Time to [Country] | Notes |
|---|---|---|
| Standard | [X–Y] business days | [CLIENT TO CONFIRM — carrier and service] |
| Express | [X–Y] business days | [CLIENT TO CONFIRM] |
| DDP included | Yes — both service levels | Duties and customs handled |

---

## Section 10: Importing CNC Parts to [Country]
<!--
  Design: H2. Full-width editorial — 2 paragraphs. Light grey background.
  Component: New — country-specific customs/import explainer. Plain English.
  Developer note: this section is country-specific content. It changes per country. Do not copy from another country page.
-->

**H2:** Importing CNC Machined Parts to [Country] — What to Know

Content: [Country]-specific import context in plain English. Cover:
- Import duty rate for CNC machined metal parts (HS code 8466 / 7326 / relevant) — or note that DDP removes this from the buyer's concern
- Any relevant compliance: CE marking, UKCA, FDA registration — only if applicable to the country
- Currency and payment — [CLIENT TO CONFIRM]
- Any specific documentation [Country] customs requires beyond standard commercial invoice

> This section must be written specifically for [Country]. Do not reuse copy from another country page. Verify customs rates and requirements before publishing — mark uncertain details with [CLIENT TO VERIFY].

---

## Section 11: Quality & Certifications
<!--
  Design: RS-01. Dark navy background. White text. H2 + 3-step checklist.
  Component: RS-01 — identical to service S13. Direct reuse.
  Developer note: same RS-01 component. Body copy unchanged.
-->

**H2:** Quality Control & Production Inspection

Three fixed steps — same as service template S13.
Footer link: → View the full quality assurance process → [[quality-assurance]]

---

## Section 12: Cities We Serve in [Country]
<!--
  Design: H2. Pill/chip grid linking to city sub-pages. White background.
  Component: Pill links — same component as material pills on service pages.
  Developer note: each pill links to the corresponding city page. Only list cities that have a published page.
-->

**H2:** Cities We Serve in [Country]

Pills — one per city page published:
[City 1] · [City 2] · [City 3] · [City 4] · [City 5] · [City 6]

---

## Section 13: FAQ
<!--
  Design: H2. Accordion. White background. First item open.
  Component: FAQ Accordion — same as service S16.
  Developer note: 10 questions. First 8 cover required topics. Last 2 are country-specific.
-->

**H2:** CNC Machining [Country] — Frequently Asked Questions

Exactly 10 questions covering all 8 required topics:
1. Tolerances — what Weldo CNC holds and how verified
2. Process — what services are available
3. Materials — what can be machined
4. Lead time — total time including transit to [Country]
5. Order volume — no MOQ
6. File formats — STEP preferred
7. Cost — what drives the quote, how it compares to local [Country] suppliers
8. Comparison — direct vs local [Country] machine shops

Questions 9–10: country-specific (e.g. customs/import process · DDP explained for this country · specific industry in this country · local currency/payment · specific certifications relevant to this market)

---

## Section 14: Final CTA
<!--
  Design: RS-03. Full-width dark navy. H2 + subtext + bullets + CTA button.
  Component: Final CTA — identical to service S18. Direct reuse.
-->

**H2:** Start Your CNC Machining Project — Delivered to [Country] in [X–Y] Days

**Subtext:** Upload a STEP file with material, tolerance class, and quantity. Quote returned within 24 hours. DDP delivery to [Country] — no customs charges on arrival.

**Bullets:**
- ✅ ISO 9001:2015 certified CNC machining facility, audited annually
- ✅ Tolerances to ±0.005 mm, CMM-verified on critical features
- ✅ 97.48% annual pass rate across all CNC machining orders
- ✅ DDP delivery to [Country] — duties and customs handled
- ✅ No minimum order quantity — single parts accepted
- ✅ Prototype parts in 1–5 business days manufacturing

**CTA Button:** Upload Your File and Get a Quote

---

## Internal Links (Silo)
**Up:** [[custom-cnc-machining-services]]
**City pages:** [[cnc-machining-[city1]]] | [[cnc-machining-[city2]]] | etc.
**Services:** [[cnc-milling-services]] | [[cnc-turning-services]] | [[5-axis-cnc-machining-services]]
**Quality:** [[quality-assurance]]
**Related countries:** [[cnc-machining-[country2]]] | [[cnc-machining-[country3]]]

---

## Rules — Apply to Every Country Page

- Brand name: **Weldo CNC** everywhere
- Stats bar S2: NEVER "20+ Years" — use delivery days + ±0.005 mm + 24 hrs + 97.48%
- Lead times: never "From 3 Days", "From 4 Days", "From 5 Days" — state confirmed range
- AI-quotable paragraph: must open Section 3
- Local shop cards (S7): 10 cards · 2 per row · factual only · all details verified · [CLIENT TO VERIFY] on unconfirmed fields
- Local shop descriptions: neutral, factual, no negative language
- Comparison (S8): scenario-based only — no competitor names
- Customs/import section (S10): country-specific — never copied from another country page
- FAQ: exactly 10 questions covering all 8 required topics
- Acronyms: expand DDP, CMM, DFM, NCR on first use
- Pass log: append at end of file after all five passes (A→B→N→D→C)
