# 🦽 Swosti Wheelchair — Convertible Wheelchair-Bed with Self-Cleaning Feature

> **Course:** Product Design-II Sessional (IPE 3206)  
> **Department:** Industrial & Production Engineering  
> **Institution:** Rajshahi University of Engineering & Technology (RUET)

---

## 👥 Group Members

| Name | Student ID |
|------|-----------|
| Md. Fardin Islam | 2005037 |
| Idrak Al Rakin | 2005046 |
| Shah Md. Tasrifur Rahim Anik | 2005048 |
| R. Rafiul Haque Ayon | 2005049 |
| Rupok Islam Avi | 2005058 |

---

## 📌 Project Overview

**Swosti Wheelchair** is a multi-functional assistive device designed for individuals with limited mobility. It combines a standard wheelchair with a full reclining bed and an integrated self-cleaning (jet spray) defecation system — addressing critical gaps in comfort, hygiene, and dignity for immobile patients.

The project covers end-to-end product design: from market research and Kano model analysis to SolidWorks stress simulation, material selection, manufacturing process selection, and full cost/break-even analysis.

---

## ✨ Key Features

- **180° Reclining Mechanism** — Converts wheelchair into a flat bed
- **Integrated Defecation (Commode) System** — Removable waste container with cushion-activated mechanism
- **Self-Cleaning Jet Spray** — Built-in water tank (3.5L) and jet spray for post-use hygiene
- **Leg, Arm & Headrests** — Adjustable supports for full-body comfort
- **Dual Brake System** — Manual hand and wheel brake levers for safety
- **Compact & Portable** — Dimensions: 900–1000 mm (L) × 400–500 mm (W) × 1100–1200 mm (H)
- **Max Load Capacity:** 120 kg

---

## 🛠️ Design & Analysis Methodology

### Market & Customer Analysis
- Customer survey with **105+ respondents**
- **Kano Model** (continuous & discrete analysis) to prioritize features
- **Competitor analysis** vs. Smart Foldable Electric Chair, Manual Folding Wheelchair, Commode Wheelchair, Sleeping Wheelchair

### Functional Design
- Black Box model
- Functional Tree & Functional Structure diagrams
- **Quality Function Deployment (QFD)** / House of Quality

### Engineering Analysis (SolidWorks)
Stress analysis performed on critical components:

| Component | Max Von Mises Stress | Min Factor of Safety |
|-----------|---------------------|---------------------|
| Wheelchair Frame | 1.25 × 10⁸ N/m² | 3.13 |
| Commode Seat | 3.024 × 10⁴ N/m² | — |
| Commode (Box) | 2.664 × 10³ N/m² | — |
| Castle Fork | 1.181 × 10⁸ N/m² | — |
| Leg Rest | 5.197 × 10⁶ N/m² | 33.16 |

Frame load range tested: **800 N – 2700 N**

### Material Selection (Digital Logic Method)
Three candidates evaluated across 7 criteria (cost, weight, toughness, elastic modulus, corrosion resistance, fatigue resistance, ultimate strength):

| Material | Performance Index (Σαβ) |
|----------|------------------------|
| Aluminum 6000 Series | 65.29 |
| **Stainless Steel Grade 304** ✅ | **82.27** |
| Carbon Fiber Composite | 65.04 |

→ **Stainless Steel (Grade 304)** selected for the frame.

### Manufacturing Process Selection (Digital Logic Method)
Gas Welding, Arc Welding, and MIG Welding evaluated across 6 criteria.  
→ **Gas Welding** selected (Performance Index: 99.25).

---

## 💰 Cost Analysis

| Item | Value |
|------|-------|
| BOM / Unit Material Cost | ৳ 7,235 |
| Total Unit Production (5 yr) | 4,238 units |
| Total Cost (Fixed + Variable) | ৳ 41,743,279 |
| Per Unit Cost | ৳ 9,849.76 |
| Selling Price | ৳ 12,500 |
| **Break-Even Point** | **~2,105 units** |
| **Projected 5-Year Profit** | **৳ 11,231,721** |

### Bill of Materials

| Component | Material | Qty | Unit Cost (৳) | Total (৳) |
|-----------|----------|-----|--------------|----------|
| Metal Frame | Stainless Steel | 1 | 3,125 | 3,125 |
| Commode | Plastic | 1 | 475 | 475 |
| Footrest | Steel | 2 | 255 | 510 |
| Primary Wheels | Steel | 2 | 895 | 1,790 |
| Front Wheels | Steel | 2 | 322 | 644 |
| Hand Pump | Plastic | 1 | 220 | 220 |
| Water Storage | Plastic | 1 | 471 | 471 |
| **Total** | | | | **7,235** |

---

## 📂 Repository Structure

```
swosti-wheelchair/
│
├── Report/
│   └── Group_11.pdf              # Full project report
│
├── CAD/
│   ├── 3D_Model/                 # SolidWorks 3D model files
│   └── 2D_Drawings/              # Engineering drawings (all parts)
│
├── Stress_Analysis/              # SolidWorks simulation results
│
├── Survey/                       # Customer survey data & charts
│
└── README.md
```

---

## 📊 Kano Model Findings

| Feature | Classification |
|---------|---------------|
| 180° Reclining | Must-Be |
| Defecation System | Must-Be |
| Leg, Arm & Headrest | Must-Be |
| Cleaning System | Must-Be |
| Cup Holder | Indifferent |

---

## 🔬 Tools & Software Used

- **SolidWorks** — 3D modeling & FEA stress analysis
- **MS Excel / Google Sheets** — Kano analysis, QFD, cost calculations
- **Google Forms** — Customer survey (105+ responses)

---

## 📄 License

This project was developed for academic purposes at RUET. All rights reserved by the authors.

---

## 🙏 Acknowledgements

We thank our course supervisors:
- **Dr. Shahed Mahmud** — Associate Professor, IPE, RUET
- **Md. Ariful Haque** — Assistant Professor, IPE, RUET
- **Md. Limonur Rahman Lingkon** — Lecturer, IPE, RUET
