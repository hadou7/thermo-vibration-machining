# Thermally and Vibrationally Enhanced Machining (FYP)

**Final Year MEng Project – University of Bath (2025)**  
*Shortlisted for the Geoff Herrington Innovation Award*  
📎 [Project Report (PDF)](link-to-report) | 🖼️ [Poster Presentation](link-to-poster)

This project models, simulates, and experimentally validates **hybrid machining** techniques combining laser/plasma heating and ultrasonic vibration to enhance performance when cutting aerospace alloys like **Ti-6Al-4V** and **Inconel 718**.

The goal: model change in tool wear, improved surface finish, and machine tool life through thermal and vibrational enhancements.

---

## 🔬 Core Objectives

- Develop a **validated Abaqus/Explicit FEA model** for thermally-assisted and vibration-assisted cutting
- Investigate performance improvements using:
  - Laser-like thermal enhancement
  - 1D and 2D elliptical ultrasonic vibration
- Conduct experimental validation using **DMG MORI CNC machine**
- Explore tool wear, chip morphology, cutting forces, and surface integrity

---

## ⚙️ Methods & Tools

| Technique | Tools Used |
|----------|------------|
| Thermal FEA | Abaqus Explicit Dynamics (custom Gaussian-esque heat source logic) |
| Vibration Modelling | Elliptical vibration via boundary condition control |
| Experimental Validation | Ultrasonic toolpaths on DMG MORI DMU 50, aluminium + titanium |
| Data Analysis | Python (NumPy, Matplotlib), MATLAB |
| Design | Inventor, PDF report authoring in LaTeX |

---

## 📊 Key Results

- 20+ hybrid machining simulations completed  
- Clear reduction in cutting forces and chip length with laser + vibration
- Modal analysis conducted to ensure true ultrasonic behaviour without resonance amplification  
- Identified **optimal frequency range** for surface finish improvement  
- Designed a retrofit enhancement system to allow **legacy CNC machines** to perform hybrid machining

<Insert charts or summary visuals/screenshots here if available>

---

## 🧠 Highlights

- Cross-domain R&D: FEA + acoustics + thermofluids + embedded systems + CNC machining
- Real-world application: reduced coolant dependency and tool change rates
- Project recognised as PhD-level work by internal examiners and industry sponsors

---

