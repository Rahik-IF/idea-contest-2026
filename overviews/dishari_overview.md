# Submitter Details

| Field | Value |
|-------|-------|
| Full Name | Gourakant Gourakant |
| Phone | (015) 900-7128 |
| Email | gouraroy542@gmail.com |
| Department | EEE |
| Roll | 2101106 |
| Submission Date | Jul 9, 2026 |
| Project Title | Dishari: AI-Powered Smart Navigation System for the Visually Impaired |
| Targeted Audience (form) | Primary end users — Blind and severely visually impaired individuals, especially in low- and middle-income regions (starting with Bangladesh/South Asia), who need an affordable alternative or add-on to the traditional white cane. Primary buyers/channels (who actually purchase at scale):  Schools for the blind and disability welfare NGOs Government social-welfare and rehabilitation programs CSR/grant-funded procurement initiatives Assistive-technology distributors  Secondary/future audience — Direct-to-consumer BVI buyers and their families, and eventually other mobility-aid manufacturers as a licensing customer. The strategy leans institutional-first (NGOs/schools/government) rather than pure retail, since that's a faster, more price-tolerant path to scale than individual consumer sales. |
| Video Link | https://drive.google.com/file/d/1_axgYm4DJcSiXjx52WuSRupkINpaJTg3/view?usp=drive_link |

---

# Project Overview

> Compiled only from the contest CSV submission and the team's uploaded Business Model / Project Report files. No external judgment or invented claims.

## Short Description (from submission form)

Independent navigation remains a major challenge for visually impaired individuals, particularly in outdoor environments filled with moving people, vehicles, and other obstacles. This project offers a real time vision-based assistive system for the visually impaired using Raspy PI 4B, where images of what lies ahead is captured continuously from a Pi camera and an extremely lightweight deep learning model ( YOLOv5-nano) detects meaningful high-priority obstacles (such as people, vehicles animals and objects commonly found at side-walks- beds / shrubbery also nonobstructive elements can be ignored in background). To spatially localize obstacles, the bottom-middle ROI (which represents user walking path) is further divided into a 3 × 3 grid. Each grid segment generates a binary output indicating obstacle presence, which directly controls a corresponding servo motor via a PCA9685 driver. The servo motion is mechanically converted into a tactile pop-up feedback system, enabling intuitive, real-time obstacle awareness without audio dependency. The system operates fully on-device, offering low latency, portability, and suitability for real-world assistive navigation applications.

## Documents on file
| Type | File | Status |
|------|------|--------|
| Business Model | `dishari_business_model.pdf` | Business Model & Investment Prospectus |
| Project Report | `dishari_project_report.pdf` | Present |

## Team named in documents
- Report: **Md. Shafiqul Islam (2101089), Gourakant (2101106), Miratul Mariam Rinte (2101116)** — EEE, RUET
- Business model: **Gourakant • Md. Shafiqul Islam**; Supervisor: **Md. Nuhi-Alamin**, Asst. Professor, EEE, RUET

## Product
**Dishari** — low-cost AI wearable navigation aid for blind/visually impaired (BVI): on-device obstacle detection with tactile pop-up feedback (no audio dependency for core feedback).

## Technical approach (Report + BM)
- Raspberry Pi 4B + Pi Camera
- YOLOv5-nano / YOLOv5n ONNX on-device
- Bottom-middle ROI → **3×3 grid**; binary obstacle per cell
- PCA9685 → 9 servo-driven tactile pop-ups
- Fully on-device; no cloud required for core safety

## Objectives (Project Report)
Low-cost portable real-time detection; prioritize walking-path critical regions; tactile/auditory feedback; low power; evaluate accuracy/response/usability; increase independent navigation confidence.

## Problem & market (Business Model)
White cane limited to ground-level/arm’s reach; electronic travel aids often $hundreds–$thousands; WHO figures cited (≥2.2B vision impairment; blindness rising). Near-term revenue expected heavily from **institutional buyers** (schools for blind, NGOs, gov rehab, CSR procurement).

## Commercialization (Business Model)
- Seed ask: **$180,000–$250,000** (prototype → certified pilot; South Asia launch 18–24 months; figures labeled illustrative)
- BOM positioned below premium ETAs (camera readers >$4,000; smart canes from hundreds USD)
- Proposed streams: direct hardware B2C retail target **$280–$380**/unit; institutional bulk sales; (further canvas details in PDF)
