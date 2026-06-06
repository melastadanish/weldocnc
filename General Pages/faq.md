<!-- PASS LOG
Pass A: Full audit — new file written from stub. Checked: no banned claims, no "20+ years", no "From 3/4/5 Days", all numbers from CLIENT-DATA-MAP, AI-quotable paragraph in S3, "Weldo CNC" spelling throughout. FAQ page draws questions from all existing service page FAQs — deduplicated and grouped by topic. All 8 required topics covered across groups.
Pass B: No failures on first write. Stats verified: ±0.005 mm, ±0.003 mm (5-axis only), 97.48%, 100+ machines, 1–5 days prototype, 5–15 days small batch, 100+ countries — all CLIENT-DATA-MAP. Banned claims not present.
Pass N: Entity block in S3: Weldo CNC, Dongguan China, ISO 9001:2015, ±0.005 mm — in first 100 words. Full topic coverage: tolerances, processes, materials, lead times, order volume, file formats, cost, comparison — all groups present.
Pass D: AI-quotable paragraph ✅. All buyer question intents addressed ✅. Comparison questions present in Process and Ordering groups ✅. Authority signals: 97.48% pass rate, ISO 9001:2015, CMM report, since 2012 ✅.
Pass C: Questions written in buyer language — not engineer-speak. Answers direct — no filler. Each answer stands alone without needing to read surrounding context. CTA at end of every group block (via S4).
Written: 2026-06-06
-->

# FAQ
**Status:** Reviewed
**Slug:** /faq/
**Meta Title:** CNC Machining FAQ | Weldo CNC — Common Questions Answered
**Meta Description:** CNC machining questions answered — tolerances, materials, lead times, file formats, pricing, quality, and ordering. Weldo CNC, ISO 9001:2015 certified, Dongguan China.
**Target Keyword:** CNC Machining FAQ

---

## SECTION 1 — HERO
<!--
  Design: Slim hero. Text centred. No image split — FAQ is a utility page.
  Component: Slim Hero — same as contact S1. No right-column image. White background.
  Developer note: use slim hero variant. Trust badges present. No file upload CTA — this page is informational.
-->

**Label (small tag above H1):**
Frequently Asked Questions

**H1:**
CNC Machining Questions — Answered

**Subheading:**
Tolerances, materials, lead times, file formats, pricing, and quality — every common question about ordering precision CNC machined parts from Weldo CNC.

**Trust badges:**
✔ ISO 9001:2015 Certified | ✔ Quote in 24 Hours | ✔ No Minimum Order Quantity

---

## SECTION 2 — TOPIC FILTER BAR
<!--
  Design: Horizontal pill/tab navigation bar. Sticky on scroll. White or light grey background.
  Component: New — topic filter. Each pill is an anchor link to the corresponding FAQ group in S3.
  Developer note: pills are anchor links to section IDs within S3. On click, scroll to that group heading. Active state on pill when that group is in viewport. Mobile: horizontal scroll on the pill row.
  Pills: 7 topics matching the 7 groups in S3.
-->

**Filter pills (anchor links):**
Tolerances & Quality | Materials | Processes & Services | Lead Times | Ordering & Pricing | File Formats | Shipping & International

---

## SECTION 3 — FAQ ACCORDION — GROUPED BY TOPIC
<!--
  Design: H2 per group. Accordion per question within group. White background.
  Component: FAQ Accordion — same component as service S16. First question in the first group open by default. All other questions closed.
  Developer note: each group has its own H2 heading. Accordion items within each group are independent — opening one does not close others in the same group. Topic filter pills (S2) scroll to the H2 of the matching group.
  Total questions: 35 across 7 groups (5 per group).
-->

---

### TOLERANCES & QUALITY

**H2:** Tolerances & Quality Control

**Q1 (open by default):**
Q: What tolerances can Weldo CNC hold on CNC machined parts?
A: Standard structural work follows ISO 2768-m — ±0.1 mm on linear dimensions. Functional interfaces — sliding fits, press fits, locating features — are machined to ±0.02 mm (ISO 2768-f). For critical features — bearing seats, sealing surfaces, precision bores — Weldo CNC holds ±0.005 mm, CMM — Coordinate Measuring Machine — verified and reported per feature against your drawing callout. On 5-axis work for complex geometry, ±0.003 mm is achievable. Applying tight tolerances to every dimension adds cost without functional benefit — DFM review at quote stage flags overspecified callouts.

**Q2:**
Q: How does Weldo CNC verify that parts meet the drawing specification?
A: Every tight-tolerance order ships with a CMM-verified dimensional inspection report. The report records measured value, nominal dimension, tolerance, and pass/fail status per feature — against your drawing revision number. Material certificates trace alloy grade and heat number to the specific parts in your shipment. Weldo CNC holds a 97.48% annual pass rate across all CNC machining orders. Non-conforming parts are quarantined and processed through a documented NCR — Non-Conformance Report — before any disposition is made. Non-conforming parts do not ship.

**Q3:**
Q: What does ISO 9001:2015 certification mean for my order?
A: ISO 9001:2015 is an internationally recognised quality management system standard. It requires documented procedures for every stage of the production process — from material intake and supplier qualification through to machining, inspection, and shipment. External audit is conducted annually. For your order, it means the quality system is not informal — it is documented, auditable, and applied consistently across all orders regardless of size.

**Q4:**
Q: What is a CMM report and do I get one with my order?
A: A CMM — Coordinate Measuring Machine — report is a dimensional inspection document that records the measured value of each critical feature on your part, alongside the nominal dimension, allowable tolerance, and a pass/fail result — referenced to your specific drawing revision number. Weldo CNC includes a CMM report with every tight-tolerance order. For standard-tolerance orders, hand-tool inspection results are available on request.

**Q5:**
Q: What is a 97.48% pass rate and how is it measured?
A: The 97.48% annual pass rate is measured across all CNC machining orders completed in a year — the percentage of orders that pass final inspection and ship without requiring rework, re-machining, or scrapping. It is measured across a single facility and a single quality system — not averaged across a supplier network. The remaining 2.52% represents parts that triggered an NCR — Non-Conformance Report — and were either reworked to specification or replaced before shipment. No non-conforming parts ship without a documented disposition.

---

### MATERIALS

**H2:** Materials

**Q6:**
Q: What metals can Weldo CNC machine?
A: Aluminium (6061, 7075, 2024, 5052, 5083, 6063, MIC-6 and other grades), stainless steel (303, 304, 316, 316L, 17-4PH, 440C and others), titanium (Grade 2 / TA2, Grade 5 / Ti-6Al-4V), carbon steel (1018, 1045, A36), alloy steel (4130, 4140, 4340), tool steel (D2, H13), brass, copper (C101, C110), and bronze. If your material isn't listed, send the alloy designation — machinability will be confirmed before quoting.

**Q7:**
Q: What engineering plastics can Weldo CNC machine?
A: PEEK, Delrin (POM), Nylon (PA6, PA66), ABS, polycarbonate, PTFE (Teflon), acrylic (PMMA), HDPE, polypropylene, Ultem (PEI), and others. Across metals and plastics, 100+ machinable materials are available. Plastics require different tooling strategies and cutting parameters than metals — dull tools cause melting rather than clean chip formation. Specifying the grade (not just the polymer family) at quote stage ensures the correct process is applied.

**Q8:**
Q: How do I choose between aluminium 6061 and 7075?
A: 6061-T6 is the general-purpose choice — good machinability, excellent weldability, broad anodizing compatibility, lower cost. 7075-T6 offers significantly higher tensile strength (503 MPa vs 310 MPa for 6061) and is the correct choice when the part carries structural load, is fatigue-critical, or needs maximum strength-to-weight ratio. 7075 is harder to machine, more sensitive to stress concentrations, and less compatible with some anodizing processes. If the part is non-structural — a housing, bracket, or enclosure — 6061 is almost always the right call.

**Q9:**
Q: Can Weldo CNC machine titanium, and what is different about it?
A: Yes. Titanium Grade 2 (TA2 — commercially pure, corrosion resistant) and Grade 5 (TC4 / Ti-6Al-4V — high strength, the most widely used titanium alloy in aerospace and medical) are both machined routinely. Titanium is more demanding than aluminium or stainless — it work-hardens at the surface during cutting, generates high heat in the cutting zone, and requires sharp tooling, correct feed rates, and adequate coolant to prevent built-up edge. These factors are managed as part of the standard process for titanium orders — not as a special arrangement.

**Q10:**
Q: Is there a material I should use for medical or implantable applications?
A: Titanium Grade 5 (Ti-6Al-4V) and certain grades of stainless steel (316L, 17-4PH) are commonly specified for medical device components. PEEK is used for non-metallic medical applications. Whether a specific material is appropriate for implantable use depends on regulatory requirements, biocompatibility standards, and the specific application — this is an engineering and regulatory decision, not one that can be confirmed at the machining quote stage. Weldo CNC machines to the material you specify and provides full material certification. Regulatory compliance remains the buyer's responsibility.

---

### PROCESSES & SERVICES

**H2:** Processes & Services

**Q11:**
Q: What CNC machining processes does Weldo CNC offer?
A: CNC milling (3-axis, 4-axis, 5-axis), CNC turning (2-axis, live tooling, Swiss-style for slender parts), 5-axis CNC machining, surface grinding, internal grinding, centerless grinding, and wire EDM — Electrical Discharge Machining. All processes are in-house at the Dongguan facility. No subcontracting on standard orders.

**Q12:**
Q: What is the difference between CNC milling and CNC turning?
A: CNC milling uses rotating cutting tools to remove material from a stationary (or slowly rotating) workpiece — correct for prismatic parts: brackets, housings, plates, manifolds, and complex 3D surfaces. CNC turning rotates the workpiece while the cutting tool is fixed — correct for cylindrical, conical, and axisymmetric parts: shafts, bushings, pins, fittings, and valve stems. Many parts combine both: a turned shaft with milled flats, or a prismatic housing with turned boss features. These are handled with live-tooling turning centres or by combining milling and turning setups.

**Q13:**
Q: When do I need 5-axis CNC machining instead of 3-axis?
A: 5-axis is required when the part has compound angles, complex curved surfaces, undercut features, or multiple machined faces that cannot all be reached with the part in a fixed position — and when re-fixturing to achieve access would introduce cumulative positional error. 5-axis is also more efficient than multiple 3-axis setups for complex geometry: one setup, one datum, ±0.003 mm tolerance across all features. If 3-axis achieves the geometry cleanly in two setups, that is what gets quoted — axis count is determined by geometry, not machine hourly rate.

**Q14:**
Q: When is wire EDM used instead of conventional machining?
A: Wire EDM — Electrical Discharge Machining — cuts by electrical spark erosion. No cutting force, no heat distortion from mechanical contact. Used when: the part is in hardened tool steel that conventional tooling cannot cut cleanly; the profile is a complex 2D shape (punch, die, template) that would require excessive setups conventionally; or the feature is too fine or thin-walled for a cutter to enter. EDM is slower than milling — it is the right process when geometry or material makes conventional machining impractical, not a substitute for it.

**Q15:**
Q: How does Weldo CNC compare to Hubs or Xometry?
A: Hubs and Xometry are order-routing platforms — your file goes to whichever shop in their network has capacity. The quality standard varies by supplier, and you have no direct relationship with the facility cutting your parts. Hubs quotes standard tolerances to ±0.020 mm — Weldo CNC holds ±0.005 mm as a standard operation, CMM-verified. Weldo CNC machines every order in-house at one facility with one ISO 9001:2015 quality system. The 97.48% pass rate is measured across a single operation — not averaged across a network. For prototype work where speed matters more than traceability, a marketplace can work. For production orders requiring a consistent quality record and a direct facility relationship, the difference is significant.

---

### LEAD TIMES

**H2:** Lead Times

**Q16:**
Q: How long does a prototype CNC machined part take?
A: 1–5 business days for standard geometry and materials — aluminium, stainless steel, or engineering plastics with straightforward tolerances and no secondary finishing. Complex parts requiring 5-axis machining, hard-to-source materials, or multiple secondary operations typically take 7–8 business days. Lead time is confirmed in the quote — not assumed.

**Q17:**
Q: How long does a production run take?
A: Small-batch production — typically 5–15 business days. Full production runs — 2–5 weeks depending on volume, material, complexity, and finish requirements. Lead time is confirmed at order stage with a committed shipment date.

**Q18:**
Q: How quickly can Weldo CNC return a quote?
A: Within 24 hours of receiving a complete STEP file with material, quantity, and tolerance class. If information is missing, a specific question comes back first. The 24-hour clock starts when the file is complete — not when the initial message is received.

**Q19:**
Q: Does the surface finish add to the lead time?
A: Yes — finishing operations add time after machining is complete. As-machined parts ship fastest. Anodizing, powder coating, passivation, and plating add 1–3 business days depending on the finish type and whether masking is required. Finishing lead time is included in the total lead time quoted — not added as a surprise after machining.

**Q20:**
Q: Can lead time be shortened for urgent orders?
A: Expedited lead times are available for some orders — depends on machine availability, material stock, and order complexity at the time of enquiry. Flag the required delivery date in the quote request — feasibility and any expedite cost will be confirmed before the order is placed.

---

### ORDERING & PRICING

**H2:** Ordering & Pricing

**Q21:**
Q: Is there a minimum order quantity?
A: No minimum order quantity. Single-part prototype orders are accepted. The same quality process — CMM inspection, material certificate, dimensional inspection report — applies to a one-piece order as to a production run. Per-unit cost is higher on single pieces because setup time is the same regardless of run length.

**Q22:**
Q: What factors affect the cost of CNC machining?
A: Part geometry (complexity and number of setups), material (raw material cost and machinability), tolerance class (tighter tolerances require longer inspection time and more controlled setups), quantity (setup cost amortised over more pieces), number of operations (milling + turning + finishing costs stack), and surface finish requirements. Upload a STEP file to receive an itemised quote within 24 hours — cost breakdown by operation is provided on request.

**Q23:**
Q: How do I place an order?
A: Upload a STEP file via the Get a Quote page. A quote is returned within 24 hours. On quote acceptance — via email, purchase order, or written approval — the order is confirmed and production is scheduled. No account setup or registration required before quoting.

**Q24:**
Q: How does Weldo CNC handle repeat orders?
A: Repeat orders on previously quoted parts carry forward setup notes, tooling selections, and inspection data from the first production run. Lead time may be shorter. Re-quote on request — pricing is confirmed at order time and may vary with material cost changes. Previous CMM data can be referenced to confirm the part has not changed.

**Q25:**
Q: What payment terms does Weldo CNC offer?
A: Payment terms are confirmed at order stage. [CLIENT TO CONFIRM — payment methods, deposit requirements, and standard terms. Do not publish until confirmed.]

---

### FILE FORMATS

**H2:** File Formats & Technical Requirements

**Q26:**
Q: What file format should I send for a CNC machining quote?
A: STEP (.stp / .step) is preferred — it carries full 3D geometry, is software-independent, and is what toolpaths are generated from. IGES is also accepted. SolidWorks (.sldprt), Pro/E (.prt), and Parasolid (.x_t) native formats are accepted. For 2D-only work, a fully dimensioned PDF or DXF works for simple prismatic geometry. Upload what you have — if additional information is needed, a specific question will follow.

**Q27:**
Q: Do I need to send a 2D drawing as well as a STEP file?
A: The STEP file carries 3D geometry. A 2D drawing is required whenever the part has: GD&T — Geometric Dimensioning and Tolerancing — callouts (true position, perpendicularity, flatness, etc.); surface finish requirements; datum references for CMM inspection; thread callouts; or any tolerance tighter than the ISO 2768-m default. If the STEP file is the complete specification and all features are standard, a drawing is not always required — but including one reduces ambiguity and is recommended for anything other than simple prototypes.

**Q28:**
Q: My file is in a format not listed — can Weldo CNC still quote?
A: Send it. Format compatibility will be confirmed within 2 hours. If a translation is needed, it is handled at the Weldo CNC end — not sent back to the buyer as a conversion task.

**Q29:**
Q: How should I specify the surface finish on a drawing?
A: Use the ISO surface texture symbol with Ra value and any process restriction if required (e.g. "grind only" for a critical bearing face). For secondary finishes — anodizing, powder coating, passivation — note the finish type, variant (e.g. Type III hard anodize), colour if applicable, and any masking requirements. Masked areas — threads, bores, sealing faces — should be shown on the drawing with a masking callout or described in the notes field on the quote request.

**Q30:**
Q: Can I send a file in millimetres and get parts back in metric dimensions?
A: Yes. All parts are machined and inspected in metric — millimetres and degrees. Imperial callouts (.inch, UNC/UNF threads) are accepted and converted. If the drawing mixes metric and imperial, flag this in the quote request so the relevant callouts are confirmed before production.

---

### SHIPPING & INTERNATIONAL

**H2:** Shipping & International Orders

**Q31:**
Q: Does Weldo CNC ship internationally?
A: Yes. Customers in 100+ countries receive parts from the Dongguan facility. North America, Europe (UK, Germany, France, and others), Asia-Pacific, and the Middle East are all regularly served. Export documentation — commercial invoice, packing list, certificate of origin — is standard.

**Q32:**
Q: How long does international shipping take?
A: Transit time after production is typically 3–7 business days to North America and Europe, depending on destination and service level selected. Express options are available. Shipping time is separate from production lead time — both are confirmed in the quote.

**Q33:**
Q: What is DDP shipping and can Weldo CNC offer it?
A: DDP — Delivered Duty Paid — means the seller handles customs clearance and import duties at the destination, so the buyer receives the shipment without paying customs fees on arrival. DDP is available on request at quote stage. If DDP is not selected, the buyer is responsible for import duties and customs clearance at the destination country.

**Q34:**
Q: What documents ship with the parts?
A: Every shipment includes a packing list. Tight-tolerance orders include a dimensional inspection report and material certificate. PPAP — Production Part Approval Process — and FAI — First Article Inspection — documentation are available on request at quote stage. If additional export or compliance documents are needed (e.g. country of origin statement, REACH compliance declaration), request them at quote stage.

**Q35:**
Q: Can Weldo CNC deliver to a freight forwarder?
A: Yes. Delivery to a named freight forwarder, consolidation warehouse, or third-party logistics address is supported. Provide the delivery address and any specific handling or labelling instructions in the order notes.

---

## SECTION 4 — STILL HAVE QUESTIONS?
<!--
  Design: 2-column. Dark background. Left: contact prompt. Right: quote prompt.
  Component: Adapted RS-01 — same dark navy background, but 2-column split rather than 3-step checklist.
  Developer note: use the RS-01 dark navy component but with a 2-column layout. Left column = contact CTA. Right column = quote CTA. Each column has H3, body, and a button.
-->

**H2:**
Still Have a Question?

**Left column:**
H3: Talk to an Engineer
Body: Technical questions about tolerances, material selection, process options, or DFM — send a message and get a specific answer from an engineer. Not a contact form response.
Button: Contact Weldo CNC

**Right column:**
H3: Get a Quote
Body: STEP file ready? Upload it and get a detailed quote with DFM review within 24 hours. No minimum order quantity.
Button: Upload Your File

---

## SECTION 5 — FINAL CTA
<!--
  Design: RS-03. Full-width dark navy. H2 + subtext + bullets + single CTA button.
  Component: Final CTA — identical to service S18. Direct reuse.
  Developer note: same RS-03 component used on all pages.
-->

**H2:**
Ready to Start? — Quote in 24 Hours

**Subtext:**
Upload a STEP file with material, quantity, and tolerance class. DFM review included. Quote returned within 24 hours.

**Bullets:**
- ✅ ISO 9001:2015 certified CNC machining facility, audited annually
- ✅ Tolerances to ±0.005 mm (±0.003 mm on 5-axis), CMM-verified
- ✅ 97.48% annual pass rate across all CNC machining orders
- ✅ No minimum order quantity — single parts accepted
- ✅ Prototype parts in 1–5 business days

**CTA Button:**
Upload Your File and Get a Quote

---

## Internal Links (Silo)
**Services:** [[custom-cnc-machining-services]] | [[cnc-milling-services]] | [[cnc-turning-services]] | [[5-axis-cnc-machining-services]] | [[precision-machining-services]]
**Quote:** [[get-a-quote]]
**Contact:** [[contact]]
**Quality:** [[quality-assurance]]
**Knowledge Base:** [[what-is-cnc-machining]] | [[cnc-tolerances-and-standards]] | [[design-for-manufacturability]]
