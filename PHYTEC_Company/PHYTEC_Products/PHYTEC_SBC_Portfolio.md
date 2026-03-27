# PHYTEC – Single Board Computer (SBC) Portfolio

## 1. Purpose of This Document

This document defines the scope, structure, and positioning of PHYTEC’s **Single Board Computer (SBC)** portfolio, marketed under the **phyBOARD®** product family.

It establishes a shared understanding of **why PHYTEC SBCs exist**, how they should be used, and how they differ from both evaluation kits and SoM‑based custom designs.

---

## 2. What a PHYTEC SBC Is

A PHYTEC Single Board Computer (SBC) is a **production‑capable embedded computing platform** that integrates:

- A PHYTEC System on Module (SoM), typically soldered or mounted
- Carrier board functionality on a single PCB
- Industrial‑grade power input, connectors, and interfaces
- Pre‑validated hardware and software configuration

PHYTEC SBCs are **not consumer development boards**.  
They are designed to be used **throughout the product lifecycle**, from early development to deployment.

---

## 3. Core Purpose of PHYTEC SBCs (KEY SECTION)

PHYTEC SBCs serve **three primary and intentional purposes** within customer projects.  
These purposes define how SBCs should be positioned and discussed.

### 3.1 Reference Platform for Custom Carrier Board Design

PHYTEC SBCs act as a **hardware reference implementation** for customers planning to design a **custom carrier board** around a PHYTEC SoM.

In this role, the SBC provides:
- Proven schematics and layout concepts
- Verified power, signal integrity, and interface design
- Known‑good hardware behavior

Customers use the SBC to:
- Validate processor and SoM selection
- Study interface implementation
- Reduce risk during custom carrier board design

In this context, the SBC is a **design reference**, not a disposable evaluation kit.

---

### 3.2 Parallel Software Development Platform

PHYTEC SBCs enable **software development to start immediately**, without waiting for the customer’s custom carrier board to be designed, manufactured, or validated.

Key advantages:
- Software teams can begin BSP customization, application development, and integration early
- Hardware and software development proceed **in parallel**
- Project timelines are shortened and risks are reduced

The SBC represents a **hardware‑stable stand‑in** for the final SoM‑based system.

This is a critical distinction from generic evaluation boards, which may not reflect production‑ready hardware behavior.

---

### 3.3 Low‑Volume Product Deployment (COTS / OEM)

PHYTEC SBCs are intentionally designed so they can be used as:
- **Low‑volume end products**
- **COTS (Commercial Off‑The‑Shelf) platforms**
- **OEM embedded computing solutions**

Typical scenarios include:
- Industrial PCs
- Gateways
- Controllers
- HMI systems
- Specialized or niche industrial equipment

In these cases:
- No custom carrier board is required
- The SBC itself becomes part of the final product
- PHYTEC’s industrial qualification and lifecycle support remain applicable

This differentiates PHYTEC SBCs from:
- Evaluation kits
- Maker boards
- Short‑lifecycle reference designs

---

## 4. Why PHYTEC Offers SBCs

PHYTEC SBCs exist to balance:
- **Speed**
- **Risk reduction**
- **Engineering effort**

They are used when:
- Time‑to‑market is critical
- Hardware customization is not immediately justified
- Production volumes are low to medium
- A stable, well‑supported platform is preferred

SBCs trade **maximum hardware flexibility** for **simplicity and predictability**.

---

## 5. SBC Portfolio Overview (phyBOARD® Family)

All PHYTEC SBCs are marketed under the **phyBOARD®** brand.

Each phyBOARD®:
- Is tightly coupled to a specific processor family
- Reflects a defined industrial use case
- Is designed for long‑term availability and support

The portfolio spans:
- General‑purpose industrial computing
- HMI and multimedia platforms
- Real‑time capable systems
- Control‑oriented industrial boards

---

## 6. Key phyBOARD® Families and Positioning

### 6.1 phyBOARD®‑Lyra (AM62x)

**Positioning:**
- Cost‑optimized industrial SBC
- General‑purpose embedded applications

**Typical use:**
- Reference platform
- Parallel software development
- IoT and gateway products

---

### 6.2 phyBOARD®‑Pollux (i.MX 8M Plus)

**Positioning:**
- Vision‑enabled and edge computing SBC

**Typical use:**
- Camera‑based systems
- Multimedia and ML‑enabled industrial devices
- Edge processing with lightweight AI workloads

---

### 6.3 phyBOARD®‑Polis (i.MX 8M Mini)

**Positioning:**
- Compact, cost‑efficient SBC

**Typical use:**
- Broad industrial applications
- Entry‑level HMI systems
- OEM products with constrained form factor

---

### 6.4 phyBOARD®‑Polaris (i.MX 8M)

**Positioning:**
- Performance‑oriented multimedia SBC

**Typical use:**
- Advanced visualization
- Multi‑display industrial HMIs

---

### 6.5 phyBOARD®‑Sargas (STM32MP15x)

**Positioning:**
- Real‑time capable industrial SBC

**Typical use:**
- Control‑centric systems
- Mixed‑criticality applications
- Real‑time + Linux combinations

---

### 6.6 phyBOARD®‑Segin / Wega / Regor

**Positioning:**
- Low‑power and control‑focused SBCs

**Typical use:**
- Industrial controllers
- DIN‑rail and automation systems
- Long‑lifecycle deployments

---

## 7. SBC vs SoM Positioning (Reinforced)

| Aspect | SBC (phyBOARD®) | SoM (phyCORE / phyFLEX) |
|---|---|---|
| Primary role | Reference / COTS | Core compute module |
| Custom hardware | Not required | Required |
| Time to market | Fast | Medium |
| Software start | Immediate | Depends on carrier |
| Volume suitability | Low–medium | Medium–high |

---

## 8. Software & Lifecycle Support

PHYTEC SBCs receive:
- Industrial BSPs
- Long‑term maintenance
- Controlled updates
- Clear documentation

They are treated as **industrial products**, not temporary tools.

---

## 9. How to Position PHYTEC SBCs

✅ Emphasize:
- Reference platform role
- Parallel development enablement
- Production suitability for low volumes
- Industrial robustness and lifecycle

❌ Avoid:
- Calling them “evaluation boards only”
- Comparing them to hobbyist SBCs
- Suggesting they are throw‑away prototypes

---

## 10. Summary

PHYTEC Single Board Computers exist to **accelerate development, reduce risk, and enable deployment**.  
They are deliberately positioned as **reference platforms, parallel development systems, and low‑volume production solutions**, bridging the gap between early development and fully custom SoM‑based designs.