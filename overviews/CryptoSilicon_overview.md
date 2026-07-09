# Submitter Details

| Field | Value |
|-------|-------|
| Full Name | Sreeja Ghosh |
| Phone | (017) 416-2169 |
| Email | ghoshsreeja212456@gmail.com |
| Department | ETE |
| Roll | 2304045 |
| Submission Date | Jul 8, 2026 |
| Project Title | CryptoSilicon: Thermal-Transient Hardware Fingerprinting. |
| Targeted Audience (form) | Here are professional answers you can fill into those form fields for your CryptoSilicon project:  Targeted Audience Semiconductor manufacturing companies, hardware security firms, IoT device developers, telecommunication network providers, and government/aerospace defense agencie |
| Video Link | https://drive.google.com/file/d/1MZGNDCVs7p4sX_ZG0DTi-joM4BG6ICcf/view?usp=drivesdk |

---

# Project Overview

> Compiled only from the contest CSV submission and the team's uploaded Business Model / Project Report files. No external judgment or invented claims.

## Short Description (from submission form)

CryptoSilicon is a hardware security project that protects silicon chips from hacking and physical attacks. Instead of storing vulnerable, permanent keys in memory, it analyzes how a chip naturally handles heat over time. Because of tiny, random imperfections from the factory, every chip heats up and cools down differently. This creates a completely unique, un-copyable "silicon fingerprint" that generates security keys only when needed and destroys them instantly if anyone tries to physically tamper with the chip.

## Documents on file
| Type | File | Status |
|------|------|--------|
| Business Model | `CryptoSilicon_business_model.docx` | Present |
| Project Report | `CryptoSilicon_project_report.pdf` | Present (image PDF; OCR) |

## Presenter (Business Model)
**Sreeja Ghosh**, Department of ETE, RUET

## Product
**CryptoSilicon: Thermal-Transient Hardware Fingerprinting** — PUF-style hardware root of trust from chip thermal-transient behavior; keys generated on demand, not stored at rest.

## Value claims (Business Model)
- Zero static footprint (key vanishes on power-down; cold-boot resistance claimed)
- Zero extra silicon cost (native thermal properties; no eFuse/EEPROM secure memory)
- Tamper-evident (probing alters thermal mass/signature → key destroyed)
- High uniqueness (Hamming distance ~50% between chips claimed)

## Revenue model (Business Model) — asset-light IP licensing (ARM-like)
1. Upfront IP licensing to fabless/chip design firms (GDSII hard macros + crypto wrappers in EDA libraries)
2. Per-unit royalties (**0.05–0.50** per chip by volume/sector as stated)
3. Annual maintenance & calibration subscription (~10-year lifecycle firmware/calibration)
4. Design-in consultation fees for custom wrappers/layouts

## Project Report themes (OCR)
Counterfeit silicon (recycled/cloned/compromised); limits of software keys & NVM; fabrication randomness as entropy; pipeline: thermal pulse → frequency transduction → wavelet decomposition → 128/256-bit fingerprint; FIB micro-probe → key destroyed / access denied.
