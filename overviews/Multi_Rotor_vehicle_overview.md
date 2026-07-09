# Submitter Details

| Field | Value |
|-------|-------|
| Full Name | Mushfiq Shabab |
| Phone | (880) 170-8879 |
| Email | hasanmushfiqshabab@gmail.com |
| Department | ECE(Elcetrical and Computer Engineering) |
| Roll | 2510026 |
| Submission Date | Jul 9, 2026 |
| Project Title | Development of an Electronically Stabilized Multi-Rotor Hover-Vehicle for Wheelless All-Terrain Transport |
| Targeted Audience (form) | ​Defence and border security forces (for traversing difficult terrains like marshlands, mud, and sand where wheels fail). ​Emergency disaster response and rescue teams (for navigating flooded or debris-heavy areas). ​Commercial agricultural sector (for large-scale farm surveying and automated spraying without damaging soil/crops). ​Tech-enthusiasts, adventure sports, and the next-generation personal commuting industry |
| Video Link | https://drive.google.com/file/d/1WltCFtPN6-pdyqKoNtx9wZLwdGc37-5p/view?usp=drivesdk |

---

# Project Overview

> Compiled only from the contest CSV submission and the team's uploaded Business Model / Project Report files. No external judgment or invented claims.

## Short Description (from submission form)

This project presents the design and architectural framework of a wheelless, single-person hover-vehicle (Hoverbike) engineered to operate slightly above ground level, eliminating mechanical rolling resistance across diverse terrains like soil, mud, and water.
​From an Electronic and Communication Engineering (ECE) perspective, the core focus centers on the vehicle's automated flight control system and power management circuitry. The system integrates a high-speed microcontroller running a real-time PID (Proportional-Integral-Derivative) optimization algorithm. It utilizes a 6-axis Inertial Measurement Unit (IMU) for active balance stabilization alongside downward-facing LiDAR/Ultrasonic sensors for automated terrain-following capabilities. By dynamically modulating the Pulse Width Modulation (PWM) signals to high-power Brushless DC (BLDC) motor controllers, the vehicle achieves precise, autonomous altitude maintenance and equilibrium. This project bridges the gap between mechatronic automation and next-generation personal mobility solutions.

## Documents on file
| Type | File | Status |
|------|------|--------|
| Business Model | `Multi_Rotor_vehicle_business_model.pdf` | **Wrong file uploaded** — extracts as IPA Workbook sample (englishlikeanative.co.uk), not a hover-vehicle BM |
| Project Report | `Multi_Rotor_vehicle_project_report.pdf` | Present (image PDF; text via OCR) |

## Product (Project Report OCR + form)
**Electronically Stabilized Multi-Rotor Hover-Vehicle** / personal eVTOL hoverbike — flies ~1–2 ft above ground; ECE focus: autonomous flight stabilization & power management.

## Technical (form + report)
- MCU + real-time **PID** → PWM to BLDC/ESC
- 6-axis **IMU**; downward **LiDAR / ultrasonic** terrain following
- Dual MCU redundancy (<2 ms failover stated); dual ultrasonic backup to LiDAR; shrouded props

## Why wheels-off (Project Report)
Eliminate rolling resistance; mud/sand/water; fully electric; ground-effect energy claim (~30% less than high-altitude drones as stated).

## Target sectors (Report + form)
Defense & border patrol; disaster relief / search & rescue; smart agriculture (survey/spraying without soil compaction); form also: tech enthusiasts, adventure sports, personal commuting.

## Business themes **inside Project Report** (BM file unusable)
- Revenue: B2G/B2B manufacturing sales + SaaS flight-software updates
- Cost: modular assembly; sensor calibration (LiDAR/IMU); carbon-composite molds
- Channels: government disaster authorities, research institutions, agricultural cooperatives via pilot leases
- Comparison table vs standard eVTOL drone and mechanical hovercraft (energy, agility, noise, terrain)
