# PHYTEC – System on Module (SoM) Portfolio

## 1. Purpose of This Document

This document defines how PHYTEC’s **System on Module (SoM) portfolio** should be understood, described, and positioned internally and externally.

It serves as a **reference context** for business development, marketing, pre‑sales, and strategic discussions.  
It is intentionally factual and avoids marketing exaggeration.

---

## 2. What a PHYTEC SoM Is

A PHYTEC System on Module (SoM) is a **compact, production‑ready computing module** that integrates:

- Application processor (SoC)
- Volatile and non‑volatile memory
- Power management
- High‑speed interfaces required by the processor
- Defined electrical and mechanical interfaces to a carrier board

The SoM acts as the **core computing element** of an embedded system, while application‑specific functionality is implemented on a **custom carrier board**.

---

## 3. Why PHYTEC Uses a SoM Architecture

PHYTEC’s SoM strategy is based on reducing **technical risk and lifecycle complexity** for customers.

Key benefits include:

- **Separation of concerns**  
  Processor complexity is isolated on the SoM; application‑specific hardware remains on the carrier board.

- **Lifecycle stability**  
  SoMs enable long‑term product maintenance even when SoCs evolve or become obsolete.

- **Scalability**  
  Customers can reuse the same carrier board design across multiple performance variants within a SoM family.

- **Faster development**  
  Proven SoM designs reduce bring‑up time and validation effort.

PHYTEC prioritizes **engineering robustness and predictability** over minimal component count.

---

## 4. Portfolio Structure (High Level)

PHYTEC’s SoM portfolio is organized around **processor families and performance classes**, not around a single universal module.

At a high level, the portfolio spans:

- Entry‑level industrial embedded processing
- Mid‑range application processing for HMI and control
- High‑performance embedded computing for edge and AI‑enabled systems

Within each class, PHYTEC typically offers **multiple SoM variants** differing in:
- Processor SKU
- Memory configuration
- Temperature grade
- Long‑term availability guarantees

---

## 5. SoM Families and Positioning

### 5.1 Industrial Application SoMs

These SoMs are optimized for:
- Industrial automation
- HMI systems
- Control and monitoring devices
- Long‑lifecycle embedded products

Typical characteristics:
- Moderate CPU performance
- Emphasis on reliability and deterministic behavior
- Broad industrial I/O support via carrier board
- Long availability commitments

These SoMs are **not optimized for high‑end AI workloads**, but may support lightweight inference.

---

### 5.2 Performance & HMI SoMs

These SoMs target:
- Advanced HMIs
- Multimedia‑enabled industrial devices
- Connectivity‑rich embedded systems

Typical characteristics:
- Higher CPU and GPU capability
- Support for multiple displays
- Strong multimedia pipelines
- Balance between performance and power consumption

They are often used where **user interaction and visualization** are critical.

---

### 5.3 Edge Computing & AI‑Capable SoMs

These SoMs are positioned for:
- Edge computing
- Industrial data aggregation
- AI‑enabled systems requiring acceleration

Key principles:
- Heterogeneous compute (CPU + GPU + NPU where applicable)
- Designed to work with **external accelerators** when needed
- Not positioned as AI model platforms themselves

PHYTEC’s strategy favors **modular AI scalability**, rather than forcing all AI workloads onto the main SoC.

---

## 6. Memory & Configuration Philosophy

PHYTEC offers multiple memory configurations per SoM to address different use cases.

Guiding principles:
- Memory configurations are **explicitly defined**, not abstracted
- Industrial‑grade memory components are preferred
- Configurations are selected to balance:
  - Cost
  - Reliability
  - Long‑term availability

PHYTEC does not dynamically alter memory configurations without formal product updates.

---

## 7. Carrier Board Relationship

PHYTEC SoMs are designed to be used with:
- PHYTEC reference carrier boards (for evaluation and prototyping)
- Customer‑specific carrier boards (for production)

The SoM‑carrier interface is:
- Electrically well‑defined
- Documented
- Intended to remain stable across SoM revisions within a family

This allows customers to:
- Reuse carrier board designs
- Scale product variants with minimal redesign

---

## 8. Software Support Expectations

PHYTEC SoMs are supported by:
- Board Support Packages (BSPs)
- Reference software stacks
- Documentation for bring‑up and integration

Software support is focused on:
- Stability
- Maintainability
- Industrial suitability

PHYTEC does not promise feature parity with consumer software ecosystems.

---

## 9. Lifecycle & Availability Positioning

Lifecycle management is a **core differentiator** of PHYTEC SoMs.

Typical expectations:
- Long‑term availability (often 10+ years, depending on SoC)
- Controlled product change notifications
- Clear roadmap communication

PHYTEC avoids frequent hardware revisions unless driven by:
- Component obsolescence
- Formal product improvements
- Customer‑relevant changes

---

## 10. How to Position PHYTEC SoMs

When discussing PHYTEC SoMs:

✅ Emphasize:
- Reliability
- Long‑term support
- Engineering clarity
- Modular scalability

❌ Avoid:
- Comparing purely on clock speed or core count
- Presenting SoMs as consumer‑grade boards
- Over‑promising AI performance without system context

PHYTEC SoMs should be positioned as **building blocks for serious embedded products**, not as generic compute modules.

---

## 11. What PHYTEC SoMs Are NOT

PHYTEC SoMs are **not**:
- Hobbyist or maker modules
- Short‑lifecycle consumer boards
- Drop‑in PC replacements
- AI accelerator cards
- Cloud or SaaS products

---

## 12. Summary

PHYTEC’s SoM portfolio provides **industrial‑grade computing foundations** designed to reduce risk, extend product lifecycles, and enable scalable embedded system development. The value of PHYTEC SoMs lies in **engineering discipline, predictability, and long‑term partnership**, not in raw benchmark numbers.