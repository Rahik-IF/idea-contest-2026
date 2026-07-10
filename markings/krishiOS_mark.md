# Marking Sheet — KrishiOS

## Project identity

| Field | Detail |
|-------|--------|
| Project | KrishiOS |
| Submitter / team (from materials) | Md Sohanur Rahman Sohan (ETE, Roll 2204041) |
| Evaluation basis | Contest CSV + uploaded Business Model & Project Report (and OCR where PDFs were image-only) |
| Presentation (video) | **Not scored here** — reserved for manual marking |

## Scorecard

| Criterion | Score | Max |
|-----------|-------|-----|
| 1. Innovation & Originality | 4 | 5 |
| 2. Feasibility | 3.5 | 5 |
| 3. Impact & Relevance | 5 | 5 |
| 4. Presentation (Video Quality & Clarity) | 4 | 5 |
| **Subtotal (criteria 1–3)** | **12.5** | **15** |
| **Final total (after video)** | **16.5** | **20** |

## Project snapshot (from submissions)

KrishiOS is an AI + IoT agriculture platform for the full farming lifecycle: disease detection from images, weather and cultivation advice, irrigation/fertilizer guidance, farm analytics, market prices, and an AI assistant. Critically, it also targets farmers without smartphones via IVR/GSM voice and SMS. The technical paper constrains the system to off-grid operation, feature-phone alerts, and a BOM of roughly ৳8,000–12,000, with a lab prototype (ESP32, sensors, 72-hour bench trial).

---

## 1. Innovation & Originality — 4/5

### What was evaluated
Novelty of combining sensing, AI diagnostics, and inclusive access channels versus typical “farming app” submissions.

### Analysis
Agri-tech apps are common; KrishiOS’s materials stand out by binding **three hard constraints** from farmer reality in Bangladesh: unreliable grid, poor rural data connectivity, and dominance of basic handsets. The paper’s requirements—(i) operate without grid/internet, (ii) deliver alerts to a feature phone with no data plan, (iii) keep BOM ~USD 70–110—force an architecture that is more original than “React + Gemini chatbot for farmers.”

The dual interface (web/AI for connected users + GSM voice/SMS for others), IoT soil/environment sensing, CV disease detection (including offline MobileNetV2/EfficientNet-Lite on ESP32-S3 as stated), and aquaculture alongside crops show breadth with a coherent inclusion thesis. Category-wise this is still “smart agriculture,” so it is not a 5 for inventing a new field—but within the contest, the off-grid + IVR packaging is a clear step above app-only peers.

### Why this score
**4/5** — Strong applied originality in access design and constraints; not category-creating, but well above generic agri-AI.

---

## 2. Feasibility — 3.5/5

### What was evaluated
Evidence of a working path (prototype, BOM, stack) versus ambition of the full platform.

### Analysis
**Supporting:** Named stack (React, Supabase, ESP32 sensors, Netlify/Supabase, voice/IVR); lab-assembled v1.0 with DHT11, moisture, etc.; 72-hour bench logging; explicit BOM band; BM that makes **institutions and commercial partners** the payers while farmers remain users—realistic for BD agri digital.

**Limiting:** Full lifecycle (disease CV, irrigation, market, analytics, aquaculture, offline AI on MCU, national IVR) is a multi-year product surface. Bench trial ≠ monsoon field trial. Scaling sensor kits, calibration, and trust with extension services is operationally heavy. Feasibility is good for a constrained MVP; the pitch’s full vision is heavier.

### Why this score
**3.5/5** — Solid prototype and realistic payer model; ambition of the full platform caps the score below 4.

---

## 3. Impact & Relevance — 5/5

### What was evaluated
Alignment with Bangladesh agriculture, smallholder inclusion, and potential livelihood/food-system effects.

### Analysis
Materials cite >87% smallholders, large avoidable water waste, load-shedding, and low rural broadband—core national development constraints. Helping irrigation, disease response, and selling decisions touches income and food loss directly. The IVR/feature-phone path means impact is not limited to smartphone elites. Government/NGO partnership BM matches how agri advisory historically scales.

Among contest entries, few match this combination of **problem severity × population reach × inclusion**.

### Why this score
**5/5** — Highest-tier relevance to BD livelihoods and food systems; inclusive channel design amplifies who can benefit.

---

## 4. Presentation (Video Quality & Clarity) — 4/5

Manual presentation mark from `notes.md`: **4/5**. Final total **16.5/20** (subtotal 12.5 + presentation 4).

---

## Overall note

**Scored subtotal: 12.5/15.** Presentation **4/5**. **Final: 16.5/20.**
