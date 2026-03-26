# 📘 CMOS Schmitt Trigger Design and Analysis (GPDK 90nm)

<p align="center">
  <b>Custom IC Design | Analog Behavior | Hysteresis Analysis</b><br>
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
This project demonstrates the **design and simulation of a CMOS Schmitt Trigger** using **GPDK 90nm technology** in Cadence Virtuoso.

The Schmitt Trigger introduces **hysteresis behavior** using positive feedback, improving **noise immunity** and ensuring stable switching for noisy or slow input signals.

---

## 📂 Project Structure
```
And_Gate/
│── README.md        # Project overview and documentation
│── images/          # Simulation results and layout screenshots
│── files/           # Cadence design files (schematic, layout, testbench)
```

---


---

## 🛠️ Tools & Technology
- **Cadence Virtuoso** (Schematic, ADE)
- **Spectre Simulator**
- **Assura** (DRC, LVS, RCX)
- **PDK:** GPDK 90nm

---

## 📐 Schematic Design

<p align="center">
  <img src="images/Schmitt_Schematic.png" width="650"/>
</p>

- CMOS implementation with **positive feedback**
- Generates **two switching thresholds (hysteresis)**
- Improves noise immunity over conventional inverter

---

## 🔷 Symbol View

<p align="center">
  <img src="images/Schmitt_Symbol.png" width="400"/>
</p>

- Custom symbol designed for hierarchical usage

---

## 🧪 Testbench Setup

<p align="center">
  <img src="images/Schmitt_tb.png" width="650"/>
</p>

- Sinusoidal input applied to observe switching thresholds  
- Output connected with load capacitor  

---

## ⚡ Transient Analysis

<p align="center">
  <img src="images/Schmitt_Transient_response.png" width="650"/>
</p>

### Observations:
- Converts noisy analog input into clean digital output  
- Exhibits clear hysteresis behavior  
- Stable transitions with reduced noise sensitivity  

---

## ⏱️ Delay Analysis

<p align="center">
  <img src="images/Schmitt_Delay.png" width="500"/>
</p>

- Propagation delay measured between input and output  
- **Delay ≈ 3.8 µs**

---

## ⚡ Energy Analysis

<p align="center">
  <img src="images/Schmitt_Energy.png" width="500"/>
</p>

- Switching energy estimated: **~4.705 nJ**  
- Reflects dynamic power during transitions  

---

## 🧩 Layout Design *(In Progress 🚧)*
- Layout implementation using **GPDK 90nm technology**
- Focus on feedback network routing and matching  
- Optimization for compact and stable design  

---

## ✅ Verification (Assura)

### ✔ DRC (Design Rule Check)
- Layout design is currently under implementation  
- Will ensure full compliance with GPDK 90nm rules  

### ✔ LVS (Layout vs Schematic)
- Will verify consistency between schematic and layout  
- Ensures correct functionality  

### ✔ RC Extraction (RCX)
- Parasitic extraction planned after layout completion  
- Enables accurate post-layout simulation  

---

## 📈 Post-Layout Analysis *(Upcoming 🚧)*
- Compare pre-layout vs post-layout results  
- Analyze impact of parasitics on hysteresis and delay  

---

## 📌 Key Learnings
- Hysteresis implementation using positive feedback  
- Noise immunity improvement in CMOS circuits  
- Delay and energy analysis using Cadence ADE  
- Analog-to-digital signal conditioning behavior  

---

## 🎯 Conclusion
The CMOS Schmitt Trigger has been successfully designed and analyzed through simulation.  
Ongoing work includes **layout design and physical verification** to complete the full custom IC design flow.

---

## 👨‍💻 Author

**Poli Prudvi Reddy**  
📧 Email: prudvireddypoli@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/prudvi-poli  

---

## ⭐ Support
If you found this project useful, give it a ⭐ on GitHub and feel free to connect!
