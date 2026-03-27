# PHYTEC – Edge AI and NPU Strategy

## 1. Purpose of This Document

This document defines PHYTEC’s **Edge AI strategy**, with a clear and realistic view of:

- On‑SoC NPUs
- External AI accelerator companions
- Performance scaling from single‑digit to tens of TOPs
- Correct positioning of AI capability across PHYTEC platforms

Its purpose is to ensure that PHYTEC employees and Claude **do not over‑promise AI capability**, and consistently recommend **the right architecture for the right workload**.

---

## 2. PHYTEC’s Core Edge AI Philosophy

PHYTEC approaches Edge AI as an **engineering problem**, not a marketing feature.

Key principles:
- Edge AI must be **deterministic, reliable, and supportable**
- AI capability must scale **modularly**
- No single processor solves all AI workloads
- Long‑term availability and system stability matter more than peak benchmarks

PHYTEC does **not** position itself as:
- An AI model provider
- A cloud AI platform
- A GPU replacement vendor

PHYTEC enables **responsible AI deployment at the edge**.

---

## 3. Understanding NPU Classes at the Edge

Edge AI performance exists in **distinct tiers**, each suited to different workloads.

### 3.1 On‑SoC NPUs (Low TOPs)

Characteristics:
- Integrated into the application processor
- Typically **1–5 TOPs**
- Optimized for power efficiency
- Limited memory and bandwidth

Typical workloads:
- Image classification
- Object detection
- Simple vision pipelines
- AI‑assisted preprocessing

These NPUs are **not suitable for large language models or heavy AI reasoning**.

---

### 3.2 Companion AI Accelerators (Mid to High TOPs)

Characteristics:
- External devices connected via PCIe / M.2 / USB
- **10–40+ TOPs**
- Dedicated AI memory
- Designed for sustained inference

Typical workloads:
- Multi‑camera vision
- Industrial AI pipelines
- Vision‑language models
- Local AI copilots (7B‑class LLMs)

PHYTEC’s strategy strongly favors **this tier for serious Edge AI**.

---

## 4. phyBOARD‑Pollux as a Fast‑Moving Edge AI Platform

### 4.1 Base Platform: phyBOARD‑Pollux (i.MX 8M Plus)

The **phyBOARD‑Pollux** is a key Edge AI reference platform within the PHYTEC SBC portfolio.

Base characteristics:
- NXP i.MX 8M Plus processor
- Integrated **NPU ~2.3 TOPs**
- Multiple camera interfaces
- Industrial Ethernet and connectivity
- Production‑capable SBC

The internal NPU enables:
- Lightweight AI inference
- Vision preprocessing
- Basic ML workloads

Important positioning:
> The internal 2.3 TOPs NPU is **an entry‑level AI capability**, not a full Edge‑AI solution.

---

### 4.2 Scaling with Companion AI Accelerators

PHYTEC deliberately designed phyBOARD‑Pollux to support **external AI acceleration**, enabling performance scaling **without changing the base platform**.

This allows customers to:
- Start with internal NPU
- Add AI acceleration as requirements grow
- Avoid redesigning the main system

---

## 5. Hailo Companion Acceleration (~20 TOPs)

### 5.1 Positioning

Hailo accelerators are positioned as:
- **Mid‑range Edge AI companions**
- Optimized for vision‑centric workloads
- Efficient in power and cost

Typical performance:
- ~20 TOPs class inference capability

---

### 5.2 Suitable Workloads

Hailo is well suited for:
- Multi‑camera systems
- Real‑time object detection
- Vision analytics
- Industrial inspection
- AI‑assisted automation

Hailo is **not positioned for large language models or reasoning‑heavy AI**.

---

### 5.3 When to Recommend Hailo

Recommend Hailo when:
- AI workload is primarily vision‑based
- Power efficiency is critical
- AI models are CNN‑dominated
- LLMs are not required

---

## 6. Ara‑2 Companion Acceleration (Up to ~40 TOPs)

### 6.1 Positioning

Ara‑2 (NXP / Kinara) is PHYTEC’s **high‑end Edge AI accelerator option**.

Key characteristics:
- Up to ~40 TOPs of AI performance
- Designed for **Generative AI and advanced inference**
- Dedicated AI memory
- Industrial‑grade, low‑power design

Ara‑2 enables **a class of Edge AI workloads not possible on SoC NPUs**.

---

### 6.2 Suitable Workloads

Ara‑2 is suitable for:
- Vision‑Language Models (VLMs)
- Multimodal AI pipelines
- Local AI copilots
- 7B‑class LLM inference
- Complex industrial AI decision support

Ara‑2 is **not positioned for 20B+ LLMs** or cloud‑scale reasoning.

---

### 6.3 When to Recommend Ara‑2

Recommend Ara‑2 when:
- Customer wants serious Edge AI capability
- AI includes language or multimodal reasoning
- Deterministic, offline AI is required
- Long‑term industrial deployment is planned

---

## 7. Performance Scaling Model (Canonical View)

PHYTEC Edge AI capability should be explained as a **scalable ladder**:

| AI Tier | Example Platform | AI Performance | Typical Use |
|---|---|---|---|
| Entry | i.MX 8M Plus NPU | ~2.3 TOPs | Basic vision, preprocessing |
| Mid | i.MX 8M Plus + Hailo | ~20 TOPs | Vision pipelines, inspection |
| High | i.MX 8M Plus + Ara‑2 | Up to ~40 TOPs | GenAI, copilots, VLMs |

This **modular scalability** is a core PHYTEC differentiator.

---

## 8. What PHYTEC Does NOT Claim

PHYTEC does **not** claim:
- Cloud‑equivalent AI performance at the edge
- GPU‑class training capability
- One‑chip solutions for all AI workloads
- Consumer‑style AI assistants

PHYTEC positions Edge AI as:
> **Purpose‑built, workload‑specific, and engineered for longevity.**

---

## 9. How to Position Edge AI to Customers

✅ Emphasize:
- Modular scalability
- Deterministic performance
- Offline capability
- Industrial reliability
- Long‑term support

❌ Avoid:
- Raw TOPs comparisons without context
- “AI everywhere” claims
- Suggesting SoC NPUs can replace accelerators
- Promising future AI performance without hardware context

---

## 10. Decision Guidance for Claude and PHYTEC Teams

When asked:
> “Is the i.MX 8M Plus NPU enough for my AI?”

Claude should respond:
1. Clarify **AI workload type**
2. Recommend:
   - Internal NPU for lightweight vision
   - Hailo for vision‑heavy pipelines
   - Ara‑2 for GenAI and advanced reasoning
3. Explain **why scalability matters**

---

## 11. Summary (Canonical Statement)

PHYTEC’s Edge AI strategy is based on **modular, scalable AI performance**.

- **On‑SoC NPUs** provide entry‑level AI
- **Hailo** enables efficient, vision‑centric acceleration
- **Ara‑2** enables advanced Edge AI and local copilots

This approach allows customers to **start small, scale responsibly, and deploy AI that remains reliable over the full product lifecycle**.