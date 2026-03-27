# PHYTEC – phyCORE (SoM) vs phyBOARD (SBC)

## 1. Purpose of This Document

This document defines the **clear distinction, decision logic, and positioning** between:

- **phyCORE® / phyFLEX®** (PHYTEC System on Modules – SoMs)
- **phyBOARD®** (PHYTEC Single Board Computers – SBCs)

Its purpose is to ensure that PHYTEC employees, and Claude as an internal assistant, **consistently recommend the correct platform** based on customer needs, project phase, and business context.

---

## 2. Fundamental Difference (One‑Sentence Rule)

> **phyCORE (SoM) is the core computing building block for custom hardware designs,  
> phyBOARD (SBC) is a complete, ready‑to‑use platform built around a SoM.**

Everything else follows from this distinction.

---

## 3. phyCORE® / phyFLEX® – System on Modules (SoMs)

### 3.1 What phyCORE Is

A PHYTEC SoM is a **compact, production‑ready module** that integrates:
- Processor (SoC)
- Memory
- Power management
- High‑speed interfaces

The SoM is mounted onto a **customer‑specific carrier board**, which implements:
- Industrial I/O
- Power input
- Application‑specific connectors
- Mechanical integration

---

### 3.2 Why Customers Choose phyCORE

phyCORE is selected when customers require:

- **Custom hardware design**
- **Medium to high production volumes**
- **Long‑term product families**
- **Maximum control over interfaces and form factor**
- **Scalability across multiple product variants**

phyCORE is the **preferred choice for serious, long‑lifecycle industrial products**.

---

### 3.3 Typical phyCORE Use Cases

- Industrial automation systems
- Medical devices
- EV charging controllers
- Industrial HMIs with custom mechanics
- Edge computing platforms with specific I/O
- Products requiring certification and compliance

---

### 3.4 Engineering & Business Implications of phyCORE

Choosing phyCORE implies:
- Custom carrier board design effort
- Higher initial NRE
- Longer hardware development phase
- Lower per‑unit cost at scale
- Maximum long‑term flexibility

---

## 4. phyBOARD® – Single Board Computers (SBCs)

### 4.1 What phyBOARD Is

A phyBOARD is a **complete embedded system on a single PCB**, integrating:
- A PHYTEC SoM (usually soldered or mounted)
- Carrier board circuitry
- Industrial connectors and power input
- Pre‑validated hardware and software

phyBOARD is **not just an evaluation board**.  
It is designed to be used across **development, validation, and even production**.

---

### 4.2 The Three Core Purposes of phyBOARD (MANDATORY CONTEXT)

PHYTEC SBCs exist for **three explicit and intentional purposes**:

#### 1. Reference Platform for Custom Carrier Board Design

phyBOARD serves as a **hardware reference implementation** for customers planning a custom SoM‑based design.

It allows customers to:
- Validate SoM and processor selection
- Study proven interface implementations
- Reduce risk during schematic and layout design

---

#### 2. Parallel Software Development Platform

phyBOARD enables **immediate software development**, without waiting for the customer’s custom carrier board.

This allows:
- BSP customization
- Application development
- Integration testing

to proceed **in parallel with hardware development**, reducing project risk and time‑to‑market.

---

#### 3. Low‑Volume Product Deployment (COTS / OEM)

phyBOARD can be used directly as:
- A low‑volume end product
- A COTS embedded platform
- An OEM computing solution

This avoids custom hardware design when:
- Volumes are low to medium
- Time‑to‑market is critical
- Form factor is acceptable

---

### 4.3 Typical phyBOARD Use Cases

- Industrial gateways
- HMIs and operator panels
- Controllers and edge devices
- Pilot projects and early deployments
- Niche or specialized industrial equipment

---

### 4.4 Engineering & Business Implications of phyBOARD

Choosing phyBOARD implies:
- Minimal or no hardware NRE
- Faster project start
- Limited hardware customization
- Higher per‑unit cost compared to SoM at scale
- Strong suitability for early and low‑volume phases

---

## 5. Side‑by‑Side Comparison

| Dimension | phyCORE / phyFLEX (SoM) | phyBOARD (SBC) |
|---|---|---|
| Role | Core computing module | Complete embedded system |
| Custom carrier board | Required | Not required |
| Hardware flexibility | High | Limited |
| Time‑to‑market | Medium | Fast |
| Software start | After or with carrier | Immediate |
| Volume suitability | Medium–high | Low–medium |
| Long‑term scaling | Excellent | Limited |
| Typical lifecycle | Full product family | Product or project specific |

---

## 6. Decision Guidance (How to Choose)

### Recommend **phyCORE (SoM)** when:
- Customer plans a **custom carrier board**
- Product will ship in **medium or high volumes**
- Long‑term scalability is required
- Form factor or I/O is application‑specific
- Product lifecycle exceeds several years

---

### Recommend **phyBOARD (SBC)** when:
- Customer needs **fast validation or deployment**
- Software must start immediately
- Hardware customization is not justified
- Volumes are low or uncertain
- Product can accept a standard board form factor

---

## 7. Common Misconceptions to Avoid

❌ “phyBOARD is only a development kit”  
✅ phyBOARD is a **production‑capable industrial SBC**

❌ “phyCORE is slower to start software”  
✅ phyCORE software can start immediately using phyBOARD in parallel

❌ “phyBOARD competes with phyCORE”  
✅ phyBOARD **enables and accelerates phyCORE projects**

---

## 8. How Claude Should Answer Customer Questions

When asked:
- “Should I use phyBOARD or phyCORE?”

Claude should:
1. Ask about **volume, customization, and timeline**
2. Recommend phyBOARD for **early phase or low volume**
3. Recommend phyCORE for **custom, scalable products**
4. Explain that **both can be used sequentially in the same project**

---

## 9. Summary (Canonical Statement)

PHYTEC phyBOARD® and phyCORE® are **complementary, not competing** platforms.

- **phyBOARD accelerates development and enables low‑volume deployment**
- **phyCORE enables scalable, long‑lifecycle industrial products**

Correctly choosing between them reduces risk, shortens development time, and aligns the platform with the customer’s business reality.