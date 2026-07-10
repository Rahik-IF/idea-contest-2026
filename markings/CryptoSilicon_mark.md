# Marking Sheet — CryptoSilicon

## Project identity

| Field | Detail |
|-------|--------|
| Project | CryptoSilicon: Thermal-Transient Hardware Fingerprinting |
| Submitter / team (from materials) | Sreeja Ghosh (ETE, Roll 2304045) |
| Evaluation basis | Contest CSV + uploaded Business Model & Project Report (and OCR where PDFs were image-only) |
| Presentation (video) | **Not scored here** — reserved for manual marking |

## Scorecard

| Criterion | Score | Max |
|-----------|-------|-----|
| 1. Innovation & Originality | 5 | 5 |
| 2. Feasibility | 2 | 5 |
| 3. Impact & Relevance | 4 | 5 |
| 4. Presentation (Video Quality & Clarity) | 3.5 | 5 |
| **Subtotal (criteria 1–3)** | **11** | **15** |
| **Final total (after video)** | **14.5** | **20** |

## Project snapshot (from submissions)

CryptoSilicon proposes a hardware root of trust using thermal-transient fingerprinting (PUF-style): a thermal pulse and wavelet processing yield a chip-unique key generated on demand (not stored at rest), claimed tamper-evident under physical probing. Business model is asset-light IP licensing and per-unit royalties (0.05–0.50), plus calibration subscriptions and design-in consulting—ARM-like, not a fab operator.

---

## 1. Innovation & Originality — 5/5

### What was evaluated
Scientific/engineering originality relative to typical contest software ideas.

### Analysis
This is the most research-forward submission: exploiting fabrication randomness via thermal transients, on-the-fly keys, and molecular-level tamper evidence. The BM correctly chooses IP licensing rather than pretending a student team will run a fab. Versus app clones, originality is maximal. Report is image-heavy but OCR recovers a coherent threat model (counterfeit/recycled/cloned silicon) and pipeline narrative.

### Why this score
**5/5** — Highest technical originality in the set; IP framing matches the invention type.

---

## 2. Feasibility — 2/5

### What was evaluated
Near-term executability by a student team toward the claimed commercial path.

### Analysis
Real PUF/thermal characterization, GDSII hard macros, EDA library design-in, and fabless royalty deals require years, labs, and industry relationships. A contest can present the concept; it cannot ship production silicon security IP quickly. Feasibility for *idea exploration* exists; feasibility for *stated commercialization* in contest horizon is low.

### Why this score
**2/5** — Conceptually serious, practically distant; lowest shippability among high-innovation entries.

---

## 3. Impact & Relevance — 4/5

### What was evaluated
Importance of hardware security / anti-counterfeit if the IP were adopted.

### Analysis
Counterfeit and tampered chips threaten avionics, medical, defense, and IoT supply chains—high stakes globally. Impact is large but **indirect and long-horizon**, mediated by chip vendors, not immediate BD citizen services. Relevance is real; immediacy is lower than agri/health/assistive entries.

### Why this score
**4/5** — High strategic importance; delayed and B2B/IP-mediated delivery of impact.

---

## 4. Presentation (Video Quality & Clarity) — 3.5/5

Manual presentation mark from `notes.md`: **3.5/5**. Final total **14.5/20** (subtotal 11 + presentation 3.5).

---

## Overall note

**Scored subtotal: 11/15.** Presentation **3.5/5**. **Final: 14.5/20.**
