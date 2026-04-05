# Antenna-Design-3.5GHZ-RMPA
Design and simulation of a 3.5 GHz Rectangular Microstrip Patch Antenna (RMPA) using Ansys HFSS. Includes theoretical calculations, HFSS modeling, and analysis of return loss, VSWR, gain, and radiation patterns for 5G and wireless applications.
# Rectangular Microstrip Patch Antenna (RMPA) – 3.5 GHz

##  Project Overview
This project focuses on the **design, simulation, and analysis** of a **Rectangular Microstrip Patch Antenna (RMPA)** operating at **3.5 GHz** for modern wireless communication systems.

The antenna is designed using an **FR-4 substrate** and simulated using Ansys HFSS to evaluate key performance parameters such as return loss, VSWR, bandwidth, and radiation characteristics.

---

##  Objectives
- Design a rectangular microstrip patch antenna for **3.5 GHz**
- Perform **theoretical calculations** for antenna dimensions
- Model the antenna using **HFSS**
- Achieve:
  - Return Loss < -10 dB  
  - VSWR ≈ 1  
- Analyze:
  - Bandwidth  
  - Gain and Directivity  
  - Radiation Pattern  

---

##  Tools & Technologies
- Ansys HFSS (High Frequency Structure Simulator)
- Ansys Electronics Desktop (AEDT)

---

##  Design Specifications

| Parameter | Value |
|----------|------|
| Frequency | 3.5 GHz |
| Substrate | FR-4 |
| Dielectric Constant (εr) | 4.4 |
| Substrate Thickness | 1.6 mm |
| Patch Width | 30 mm |
| Patch Length | 19.13 mm |
| Feed Technique | Microstrip / Coaxial Feed |

---

##  Methodology

### 1. Theoretical Design
- Calculated patch dimensions using standard antenna equations
- Considered fringing effects and effective dielectric constant

### 2. HFSS Modeling
- Created 3D structure including:
  - Ground plane
  - Substrate
  - Patch
  - Feed line / coaxial feed

### 3. Simulation Setup
- Applied boundary conditions:
  - Perfect Electric Conductor (PEC)
  - Radiation boundary (air box)
- Defined excitation using lumped port
- Performed frequency sweep (3 GHz – 4 GHz)

### 4. Performance Analysis
- Return Loss (S11)
- Voltage Standing Wave Ratio (VSWR)
- Bandwidth
- Gain and Directivity
- Radiation Pattern

---

##  Results

-  Resonant frequency achieved at **3.5 GHz**
-  Return Loss below **-10 dB**
-  VSWR close to **1**
-  Suitable bandwidth for wireless applications
-  Good radiation pattern and gain






