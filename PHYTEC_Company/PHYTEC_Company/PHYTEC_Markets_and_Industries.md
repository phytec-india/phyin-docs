# PHYTEC – Markets and Industries

## 1. Purpose of This Document

This document defines the **primary markets and industries** served by PHYTEC and explains how PHYTEC platforms should be positioned within each.

Its purpose is to ensure that:
- PHYTEC is not mispositioned as a generic embedded supplier
- Market discussions are grounded in real industrial requirements
- Claude and PHYTEC teams align on where PHYTEC creates the most value

This document focuses on **professional and industrial markets**, not consumer segments.

---

## 2. PHYTEC’s Market Philosophy

PHYTEC serves markets where the following characteristics are critical:

- **Long product lifecycles**
- **High reliability and robustness**
- **Predictable behavior over time**
- **Engineering transparency**
- **Lifecycle and supply‑chain stability**

PHYTEC deliberately avoids markets driven by:
- Short consumer product cycles
- Extreme price pressure
- Rapid feature churn
- Minimal support expectations

---

## 3. Primary Markets Served by PHYTEC

### 3.1 Industrial Automation & Control

**Market characteristics:**
- Long‑lived equipment (10–20 years)
- Deterministic operation requirements
- Harsh environmental conditions
- Strong emphasis on reliability and maintainability

**Typical applications:**
- PLCs and soft‑PLC systems
- Industrial controllers
- Machine control units
- Distributed I/O and gateways
- Factory automation systems

**PHYTEC value proposition:**
- Long‑term availability of hardware platforms
- Industrial‑grade design and EMI robustness
- Support for real‑time and mixed‑criticality systems
- Strong embedded Linux and RTOS support

---

### 3.2 Industrial HMI & Operator Interfaces

**Market characteristics:**
- Continuous operation
- Human safety considerations
- High availability expectations
- Need for stable graphics and input handling

**Typical applications:**
- Operator panels
- Industrial touch HMIs
- Control room interfaces
- Visualization terminals

**PHYTEC value proposition:**
- Scalable performance across product families
- Proven display and graphics pipelines
- Balanced CPU/GPU/NPU capability
- Stable BSPs with long‑term maintenance

---

### 3.3 Edge Computing & Industrial Edge AI

**Market characteristics:**
- Local data processing
- Limited or no cloud connectivity
- Deterministic latency requirements
- Increasing use of AI inference at the edge

**Typical applications:**
- Industrial gateways
- Predictive maintenance systems
- Vision‑based inspection
- Edge analytics nodes
- Local AI copilots

**PHYTEC value proposition:**
- Modular Edge AI strategy (on‑SoC NPU + accelerators)
- Support for external AI companions (e.g., Hailo, Ara‑2)
- Industrial deployment readiness
- Offline and deterministic operation

---

### 3.4 Medical Devices & Healthcare Equipment

**Market characteristics:**
- High reliability and safety expectations
- Long certification cycles
- Controlled hardware and software changes
- Strong documentation requirements

**Typical applications:**
- Diagnostic equipment
- Patient monitoring systems
- Medical imaging subsystems
- Therapy and laboratory equipment

**PHYTEC value proposition:**
- Stable hardware platforms
- Long‑term lifecycle management
- Controlled change processes
- Engineering transparency and documentation

PHYTEC platforms are typically used as **embedded subsystems**, not complete medical devices.

---

### 3.5 Energy, Utilities & Infrastructure

**Market characteristics:**
- Distributed systems
- Long operational lifetimes
- Harsh environments
- High availability requirements

**Typical applications:**
- Energy management systems
- Power monitoring units
- Substation equipment
- Grid‑edge controllers
- Renewable energy systems

**PHYTEC value proposition:**
- Robust industrial design
- Wide temperature support
- Long‑term supply stability
- Secure and maintainable embedded platforms

---

### 3.6 Transportation, Logistics & Fleet Systems

**Market characteristics:**
- Continuous operation
- Connectivity and data aggregation
- Environmental stress (temperature, vibration)
- Long service lifetimes

**Typical applications:**
- Fleet management systems
- On‑board controllers
- Transportation gateways
- Tracking and monitoring units

**PHYTEC value proposition:**
- Industrial‑grade SBCs and SoMs
- Strong connectivity support
- Proven reliability in mobile environments
- Long‑term maintenance support

---

### 3.7 EV Charging & Energy Management Systems

**Market characteristics:**
- Regulatory and standards compliance
- Safety‑critical operation
- Long‑term field deployment
- Remote management requirements

**Typical applications:**
- EV charging controllers
- Charging station HMIs
- Energy management subsystems
- Edge gateways for charging infrastructure

**PHYTEC value proposition:**
- Stable embedded platforms
- Support for Linux‑based charging frameworks
- Long‑term availability aligned with infrastructure timelines
- Strong software and BSP expertise

---

## 4. Secondary / Adjacent Markets

PHYTEC may also support:

- Test and measurement equipment
- Professional audio/video systems
- Specialized industrial computing
- Research and pilot industrial platforms

These are typically **professional or industrial**, not consumer‑driven.

---

## 5. Markets PHYTEC Does NOT Target

To avoid mispositioning, PHYTEC does **not** primarily target:

- Consumer electronics
- Smartphones and tablets
- Mass‑market IoT gadgets
- Ultra‑low‑cost maker platforms
- Rapid‑turn consumer appliances

While PHYTEC technology may technically fit these areas, they do not align with PHYTEC’s business and lifecycle model.

---

## 6. How Market Positioning Influences Platform Choice

| Market Characteristic | Typical PHYTEC Choice |
|---|---|
| Long lifecycle, custom I/O | phyCORE / phyFLEX (SoM) |
| Fast deployment, low volume | phyBOARD (SBC) |
| Edge AI, vision | phyBOARD‑Pollux + accelerator |
| Real‑time control | STM32MP‑based platforms |
| Infrastructure systems | Industrial SBCs and SoMs |

---

## 7. How Claude Should Talk About Markets

When asked:
> “Is PHYTEC suitable for my industry?”

Claude should:
1. Identify lifecycle, volume, and reliability requirements
2. Map these to PHYTEC’s target markets
3. Clearly state fit or non‑fit
4. Avoid forcing PHYTEC into unsuitable segments

Honest non‑fit responses build trust.

---

## 8. Canonical Market Positioning Statement

> PHYTEC serves professional and industrial markets where reliability, long‑term availability, and engineering discipline matter more than rapid consumer innovation. Its platforms are designed to support embedded products that must operate predictably over many years in demanding environments.

---

## 9. Summary

PHYTEC’s strength lies in **industrial and professional markets** that demand:
- Stability over novelty
- Engineering depth over speed
- Lifecycle commitment over short‑term cost

Understanding these markets ensures PHYTEC is positioned **accurately, credibly, and sustainably**.