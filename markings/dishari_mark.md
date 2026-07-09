# Marking Sheet — Dishari

## Project identity

| Field | Detail |
|-------|--------|
| Project | Dishari: AI-Powered Smart Navigation System for the Visually Impaired |
| Submitter / team (from materials) | Gourakant (EEE, Roll 2101106) — team also names Md. Shafiqul Islam, Miratul Mariam Rinte; supervisor Md. Nuhi-Alamin |
| Evaluation basis | Contest CSV + uploaded Business Model & Project Report (and OCR where PDFs were image-only) |
| Presentation (video) | **Not scored here** — reserved for manual marking |

## Scorecard

| Criterion | Score | Max |
|-----------|-------|-----|
| 1. Innovation & Originality | 5 | 5 |
| 2. Feasibility | 3.5 | 5 |
| 3. Impact & Relevance | 5 | 5 |
| 4. Presentation (Video Quality & Clarity) | — | 5 |
| **Subtotal (criteria 1–3)** | **13.5** | **15** |
| **Final total (after video)** | **—** | **20** |

## Project snapshot (from submissions)

Dishari is a low-cost, on-device assistive navigation wearable for blind and visually impaired (BVI) users. A Raspberry Pi 4B and Pi Camera run YOLOv5-nano locally; the walking-path ROI is split into a 3×3 grid; each cell drives a servo via PCA9685 to create tactile pop-up feedback—without requiring audio for core obstacle awareness. The business model targets institutional buyers (schools for the blind, NGOs, government rehab, CSR) with a seed ask of $180k–$250k and illustrative retail of $280–$380.

---

## 1. Innovation & Originality — 5/5

### What was evaluated
Originality of the technical architecture, interaction model, and positioning versus existing electronic travel aids (ETAs) and smart canes, based only on the submitted report and investment prospectus.

### Analysis
Most assistive navigation concepts in student contests recycle “camera + voice alert” or “ultrasonic cane tip.” Dishari’s materials instead specify a full pipeline: continuous Pi Camera capture → lightweight on-device YOLOv5-nano / YOLOv5n ONNX → bottom-middle ROI as walking path → **3×3 spatial grid** → binary obstacle flags → **PCA9685-driven servo tactile pop-ups**. That grid-to-tactile mapping is a concrete interaction invention, not a vague “AI for the blind” slogan.

The deliberate **non-dependence on audio** for core feedback is also original in this cohort: it avoids masking environmental sound that BVI users rely on, and it works in noisy streets. The prospectus further frames the product against expensive camera readers and smart canes (hundreds to thousands of USD), arguing commodity SBC hardware can deliver obstacle awareness at a fraction of BOM—an architectural claim, not just a feature list.

Documentation quality supports the innovation score: named team, faculty supervisor, objectives, methodology, and an investor-style BM with canvas and ask. Relative to other entries, this is the clearest “new system design” rather than “known app category with AI bolted on.”

### Why this score
**5/5** — Distinctive end-to-end architecture and tactile UX; strongest originality in the contest set; claims are specific enough to judge as genuine invention rather than buzzwords.

---

## 2. Feasibility — 3.5/5

### What was evaluated
Whether a student team can move from described prototype toward a usable, manufacturable, certifiable product, and whether the commercialization path is realistic.

### Analysis
**Supporting feasibility:** Hardware choices (RPi 4B, Pi Camera, PCA9685, servos) are obtainable; on-device inference with a nano model is a known embedded-CV pattern; objectives include indoor/semi-outdoor evaluation of accuracy, latency, and usability. The BM discusses BOM vs premium ETAs, institutional GTM (schools, NGOs, gov, CSR), and an 18–24 month path from prototype to pilot—showing the team understands lab ≠ product.

**Limiting feasibility:** Outdoor dynamic scenes (vehicles, people, animals, lighting) are hard for YOLOv5-nano on RPi with low latency and acceptable false negatives—safety-critical for mobility aids. Mechanical pop-up reliability, power, wearability, weatherproofing, and medical/assistive **certification** are barely solvable at contest stage. Retail $280–$380 and seed $180k–$250k are labeled illustrative; manufacturing localization and field validation with partner institutions remain ahead. So the idea is *prototype-feasible*, not *near-term product-feasible*.

### Why this score
**3.5/5** — Credible engineering prototype path and thoughtful institutional GTM, but large gaps in field reliability, certification, and manufacturing keep it below a 4.

---

## 3. Impact & Relevance — 5/5

### What was evaluated
Severity of the problem, fit to Bangladesh/LMIC context, and scale of benefit if the solution works as described.

### Analysis
Independent mobility is foundational to dignity, education, and employment for BVI people. The white cane cannot warn of torso-height or approaching dynamic obstacles; premium ETAs are priced out of reach where most vision loss exists (LMICs). Dishari’s form and BM explicitly start in Bangladesh/South Asia and prioritize **institutional procurement**—the channel that actually scales assistive hardware—rather than pure DTC retail.

If the device works on real sidewalks, impact is direct: fewer collisions, more confidence, possible independence gains. WHO-scale vision-impairment figures in the prospectus underscore problem magnitude. Unlike convenience apps, failure modes here are safety-relevant—which raises both impact potential and responsibility—but the *relevance* of the problem is among the highest in the contest.

### Why this score
**5/5** — Life-quality and inclusion problem of the highest order; LMIC affordability + institutional GTM match how impact would actually land.

---

## 4. Presentation (Video Quality & Clarity) — —/5

Left blank intentionally. Judges will mark video quality and clarity manually later. Do not infer a video score from documents alone.

---

## Overall note

**Scored subtotal: 13.5/15.** Final contest total out of 20 depends on the pending Presentation mark.
