# .github
<div align="center">

<img src="https://bionorthtech.github.io/BioNorth-Main/logo.jpg" alt="BioNorth Logo" width="160"/>

# BioNorth

### Restoring Movement Through Neural Intelligence

[![Website](https://img.shields.io/badge/Website-bionorthtech.github.io-0057FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://bionorthtech.github.io/BioNorth-Main/)
[![Status](https://img.shields.io/badge/Status-Phase%200%20%E2%80%93%20Prototype-00C8FF?style=for-the-badge)](https://bionorthtech.github.io/BioNorth-Main/)
[![Patent](https://img.shields.io/badge/Patent-Pending-0057FF?style=for-the-badge&logo=gov.uk&logoColor=white)]()
[![License](https://img.shields.io/badge/License-Proprietary-grey?style=for-the-badge)]()

</div>

---

## What We're Building

**BioNorth** is developing the **TrueNorth Neural Headset** — a closed-loop, non-invasive brain-computer interface (BCI) that detects and treats **freezing of gait (FOG)** in Parkinson's disease patients in real time.

> Freezing of gait is a sudden, episodic inability to walk despite the brain's full intent to move. It triples fall risk and has **zero FDA-cleared EEG-triggered solutions** on the market today.

---

## The Core Innovation

Every prior BCI-FES system stimulates on **motor intent alone**. TrueNorth stimulates only when a **freeze is confirmed** — and stops the moment muscle response is verified.

```
Motor Cortex → EEG (Cz/FCz/Fz) → ADS1299 ADC → nRF5340 DSP
    → Butterworth Filter → Band Power (θ/μ/β) → State Machine
        → [Intent ✓ + EMG ✗] = FREEZE DETECTED
            → FES Pulses → Tibialis Anterior → EMG Confirms → STIM OFF
```

**The closed loop:**

| Step | Signal | What It Does |
|------|--------|--------------|
| 1 | EEG μ/β desynchronization | Detects motor intent |
| 2 | EMG (tibialis anterior) | Monitors muscle response |
| 3 | Intent ✓ + EMG ✗ | Classifies freeze state |
| 4 | Biphasic FES pulses | Drives dorsiflexion |
| 5 | EMG confirmation | Terminates stimulation |

---

## Why It Matters

| Stat | Impact |
|------|--------|
| 1M+ Americans | Experience freezing of gait |
| ~38% of Parkinson's patients | Report FOG episodes |
| 3× higher fall risk | During a freeze |
| 0 FDA-cleared devices | That use EEG-triggered FES for FOG |

---

## Tech Stack

**Hardware**

![OpenBCI](https://img.shields.io/badge/EEG-ADS1299%20%2F%20OpenBCI-00C8FF?style=flat-square)
![EMG](https://img.shields.io/badge/EMG-AD8221%20InAmp-0057FF?style=flat-square)
![FES](https://img.shields.io/badge/FES-MAX14521E%20%2F%20NeuroStimDuino-00C8FF?style=flat-square)
![MCU](https://img.shields.io/badge/MCU-nRF5340%20Dual--Core-0057FF?style=flat-square)

**Firmware & Signal Processing**

![Python](https://img.shields.io/badge/Python-BrainFlow%20%2F%20LSL-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-Zephyr%20RTOS-00599C?style=flat-square&logo=c&logoColor=white)
![DSP](https://img.shields.io/badge/DSP-Butterworth%20Filters%20%7C%20Band%20Power-grey?style=flat-square)

**Website**

![React](https://img.shields.io/badge/React-Vite-61DAFB?style=flat-square&logo=react&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-222?style=flat-square&logo=githubpages)

---

## Roadmap

```
[●] P0 — Prototype Stabilization · Baseline Dataset · Patent Docs   ← NOW
[ ] P1 — On-Subject Validation · Provisional Patent
[ ] P2 — Custom PCB · Module Integration · Mobile App
[ ] P3 — Clinical Prototype · IRB Pilot (10–20 subjects) · FDA Pre-Sub
[ ] P4 — FDA 510(k) Submission · ISO 13485 · Manufacturing Partner
[ ] P5 — Commercial Launch · Series A
```

28–36 month path to FDA 510(k) clearance.

---

## Projects

| Repo | Description |
|------|-------------|
| [BioNorth-Main](https://github.com/bionorthtech/BioNorth-Main) | Main website & product documentation |
| [AiMetr](https://github.com/bionorthtech/AiMetr) | Multi-provider AI usage monitor with ESP32-S3 hardware companion |

---

## Recognition

**National Innovator Challenge 2025** — Winner · University of San Diego

Built by high school students in Florida.

---

<div align="center">

**📧 biotech@bionorth.us · 🌐 [bionorthtech.github.io/BioNorth-Main](https://bionorthtech.github.io/BioNorth-Main/)**

*Currently seeking clinical partners and early-stage funding.*

</div>
