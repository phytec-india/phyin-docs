# PHYTEC – Industrial Edge AI

## 1. Purpose of This Document

This document defines PHYTEC’s **Industrial Edge AI strategy**:  
how PHYTEC enables customers to deploy **intelligent, reliable, and scalable AI solutions at the industrial edge**.

It provides clear guidance on:
- What Industrial Edge AI means in practice
- How PHYTEC platforms support it
- When and why to use Edge AI (and when not to)
- How hardware, software, gateways, and IIoT frameworks fit together

This document is intentionally **engineering‑driven**, not marketing‑driven.

---

## 2. What Industrial Edge AI Means at PHYTEC

At PHYTEC, **Industrial Edge AI** means:

- **Local intelligence** close to machines and sensors  
- **Deterministic latency** and predictable behavior  
- **Operation without permanent cloud dependency**  
- **Integration into OT environments**, not just IT stacks  
- **Long‑term maintainability** over many years  

Industrial Edge AI is not about running the largest models possible.  
It is about **making systems smarter where decisions must happen**.

---

## 3. PHYTEC’s Industrial Edge AI Principles

PHYTEC follows five non‑negotiable principles:

1. **Edge-first by design**  
   Critical decisions stay local.

2. **Modular scalability**  
   AI capability scales with workload, not hype.

3. **Workload-driven architecture**  
   Hardware follows use case, not trends.

4. **Open software ecosystems**  
   Avoid vendor lock‑in at all layers.

5. **Industrial lifecycle focus**  
   Platforms must survive 10–20 year deployments.

PHYTEC does **not** position Edge AI as:
- Cloud replacement
- GPU training platform
- Consumer AI assistant
- One‑chip solution for all AI problems

---

## 4. Hardware Foundation for Industrial Edge AI

PHYTEC enables Industrial Edge AI through a **layered and modular hardware strategy**.

### 4.1 Embedded Computing Platforms

PHYTEC provides the compute foundation via:
- **phyCORE / phyFLEX SoMs** for custom industrial products
- **phyBOARD SBCs** for reference platforms and low‑volume systems

These platforms provide:
- Industrial robustness
- Long‑term availability
- Proven BSPs and software stability

They form the **control and orchestration layer** of Edge AI systems.

---

### 4.2 AI Acceleration Strategy (Scalable by Design)

PHYTEC deliberately separates **embedded control compute** from **AI acceleration**.

AI capability is added as required through:
- **On‑SoC NPUs** (entry‑level AI)
- **External AI accelerators** (serious Edge AI)

This avoids over‑engineering and protects long‑term scalability.

---

## 5. Example: phyBOARD‑Pollux as an Edge AI Reference Platform

### 5.1 Base Capability – On‑SoC NPU

The **phyBOARD‑Pollux** (i.MX 8M Plus) provides:
- Integrated NPU (~2.3 TOPs)
- Camera and multimedia support
- Industrial connectivity

This NPU is suitable for:
- Basic vision tasks
- Image preprocessing
- Lightweight inference

**Positioning rule:**  
> The internal NPU is an **entry point**, not a full Edge AI solution.

---

### 5.2 Scaling with External AI Accelerators

phyBOARD‑Pollux is designed to scale via **companion AI accelerators**:

- **Hailo (~20 TOPs)**  
  - Vision‑centric AI pipelines  
  - Multi‑camera inspection  
  - Real‑time object detection  

- **Ara‑2 (up to ~40 TOPs)**  
  - Advanced inference  
  - Vision‑Language Models (VLMs)  
  - Local AI copilots (7B‑class LLMs)  

This enables customers to:
- Start small
- Scale AI performance without redesign
- Match hardware investment to real workloads

---

## 6. phyGATE – Industrial Edge AI in Deployment

### 6.1 Role of phyGATE in Edge AI Architectures

The **phyGATE product line** represents PHYTEC’s **finished industrial Edge gateway platforms**.

phyGATE devices are:
- Series‑ready OEM products
- Designed for DIN‑rail and industrial environments
- Optimized for IIoT and Edge deployment

In Edge AI systems, phyGATE acts as:
> The **deployment and execution layer** for Industrial Edge AI.

---

### 6.2 Typical phyGATE Edge AI Roles

phyGATE is used for:
- Industrial data aggregation
- Protocol translation (OT ↔ IT)
- Local AI inference and preprocessing
- Secure connectivity to cloud or MES
- Retrofit of existing machines

phyGATE removes the need to design:
- Custom hardware
- Industrial enclosures
- EMC‑qualified systems

---

## 7. ThingEDGE – Accelerating Industrial Edge AI Solutions

### 7.1 What ThingEDGE Provides

**ThingEDGE** is an **open‑source IIoT framework** used by PHYTEC to accelerate Industrial Edge and Edge AI solutions.

It provides:
- Modular software building blocks
- Standardized data handling
- Integration patterns for devices, services, and AI outputs

ThingEDGE addresses the **software integration gap** that often delays Edge AI projects.

---

### 7.2 Why ThingEDGE Matters for Edge AI

In industrial projects:
- AI inference is only one component
- Data orchestration and integration dominate effort

ThingEDGE helps:
- Shorten development cycles
- Reduce custom glue code
- Integrate AI results into real workflows
- Maintain openness and extensibility

It aligns with PHYTEC’s **open, long‑lifecycle philosophy**.

---

## 8. Reference Industrial Edge AI Architecture