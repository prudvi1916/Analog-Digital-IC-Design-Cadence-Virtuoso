# 📘 CMOS NOR Gate Design and Analysis (GPDK 90nm)

<p align="center">
  <b>Custom IC Design | Digital Logic | Performance Analysis</b><br>
  Cadence Virtuoso • Spectre • Assura • GPDK 90nm
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Technology-GPDK90nm-blue">
  <img src="https://img.shields.io/badge/Tool-Cadence%20Virtuoso-orange">
  <img src="https://img.shields.io/badge/Verification-Assura-orange">
  <img src="https://img.shields.io/badge/Status-Work%20In%20Progress-yellow">
</p>

---

## 🚀 Overview
This project demonstrates the **design and simulation of a CMOS NOR gate** using **GPDK 90nm technology** in Cadence Virtuoso.

The NOR gate is a **fundamental universal logic gate**, widely used in digital systems. This work focuses on **functional verification, delay analysis, and power estimation**.

---

## 📂 Project Structure
```
Nor_Gate/
│── README.md        # Project overview and documentation
│── images/          # Simulation results and layout screenshots
│── files/           # Cadence design files (schematic, layout, testbench)
```

---

## 🛠️ Tools & Technology
- **Cadence Virtuoso** (Schematic, ADE)
- **Spectre Simulator**
- **Assura** (DRC, LVS, RCX)
- **PDK:** GPDK 90nm

---

## 📐 Schematic Design

<p align="center">
  <img src="Images/Nor_Schematic.png" width="650"/>
</p>

- CMOS NOR implementation using:
  - **Series PMOS (pull-up network)**
  - **Parallel NMOS (pull-down network)**
- Output goes HIGH only when both inputs are LOW  

---

## 🔷 Symbol View

<p align="center">
  <img src="Images/Nor_Symbol.png" width="400"/>
</p>

- Custom symbol created for hierarchical design  

---

## 🧪 Testbench Setup

<p align="center">
  <img src="Images/Nor_tb.png" width="650"/>
</p>

- Two pulse inputs applied  
- Covers all input combinations  
- Output connected to capacitive load  

---

## ⚡ Transient Analysis

<p align="center">
  <img src="Images/Nor_Transient response.png" width="650"/>
</p>

### Observations:
- Correct NOR logic behavior verified  
- Output HIGH only when both inputs are LOW  
- Clean transitions with expected switching behavior  

---

## ⏱️ Delay Analysis

<p align="center">
  <img src="Images/Nor_Delay.png" width="500"/>
</p>

- Propagation delay measured between input and output  
- **Delay ≈ 22 ps**

---

## ⚡ Energy Analysis

<p align="center">
  <img src="Images/Nor_Energy.png" width="500"/>
</p>

- Energy consumption observed during switching  
- Indicates efficient CMOS operation  

---

## 🧩 Layout Design

<p align="center">
  <img src="Images/nor_layout.png" width="350"/>
</p>

### Features:
- PMOS placed in **N-well**, NMOS in **P-substrate**
- Series PMOS and parallel NMOS implementation  
- Shared poly gates for inputs  
- Compact routing with proper use of contacts and vias  

---

## ✅ Verification (Assura)

<p align="center">
  <img src="Images/nor_drc.png" width="250"/>
  <img src="Images/nor_lvs.png" width="250"/>
  <img src="Images/nor_rcx.png" width="250"/>
</p>

### ✔ DRC (Design Rule Check)
- No violations found  
- Layout follows all GPDK 90nm rules  

### ✔ LVS (Layout vs Schematic)
- Perfect match between schematic and layout  
- No mismatches  

### ✔ RC Extraction (RCX)
- Parasitics extracted successfully  
- Extracted view generated  

---

## 📈 Post-Layout Simulation

<p align="center">
  <img src="Images/nor_compare.png" width="400"/>
  <img src="Images/nor_extracted.png" width="400"/>
</p>

- Extracted view generated after RCX  
- Ready for post-layout simulation  

---

## 📌 Key Learnings
- CMOS NOR gate design fundamentals  
- Understanding pull-up and pull-down behavior  
- Delay and power analysis using Cadence  
- Digital switching characteristics  

---

## 🎯 Conclusion
The CMOS NOR gate has been successfully designed and verified through simulation.  
Further work includes **layout design and physical verification** to complete the full custom IC design flow.

---

## 👨‍💻 Author

**Poli Prudvi Reddy**  
📧 Email: prudvireddypoli@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/prudvi-poli  

---

## ⭐ Support
If you found this project useful, give it a ⭐ on GitHub and feel free to connect!
