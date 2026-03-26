# 📘 CMOS NAND Gate Design and Analysis (GPDK 90nm)

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
This project demonstrates the **design and simulation of a CMOS NAND gate** using **GPDK 90nm technology** in Cadence Virtuoso.

The NAND gate is a **universal logic gate**, forming the foundation for complex digital circuits. This work focuses on **functional verification, delay analysis, and power estimation**.

---

## 📂 Project Structure
```
Inverter/
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
  <img src="Images/Nand_Schematic.png" width="650"/>
</p>

- CMOS NAND implementation using:
  - **Parallel PMOS (pull-up network)**
  - **Series NMOS (pull-down network)**
- Output goes LOW only when both inputs are HIGH  

---

## 🔷 Symbol View

<p align="center">
  <img src="Images/Nand_Symbol.png" width="400"/>
</p>

- Custom symbol created for hierarchical design integration  

---

## 🧪 Testbench Setup

<p align="center">
  <img src="Images/Nand_tb.png" width="650"/>
</p>

- Two pulse inputs applied to verify all input combinations  
- Output connected with load capacitor  

---

## ⚡ Transient Analysis

<p align="center">
  <img src="Images/Nand_Transient_response.png" width="650"/>
</p>

### Observations:
- Correct NAND logic behavior verified  
- Output transitions LOW only when both inputs are HIGH  
- Clean switching with expected delay characteristics  

---

## ⏱️ Delay Analysis

<p align="center">
  <img src="Images/Nand_Delay.png" width="500"/>
</p>

- Propagation delay measured between input and output  
- **Delay ≈ 5.91 ps**

---

## ⚡ Energy Analysis

<p align="center">
  <img src="Images/Nand_Energy.png" width="500"/>
</p>

- Switching energy estimated: **~1.711 fJ**  
- Indicates low dynamic power consumption  

---

## 🧩 Layout Design *(In Progress 🚧)*
- Layout implementation using **GPDK 90nm rules**
- Focus on:
  - Proper transistor placement  
  - Efficient routing  
  - Minimizing parasitics  

---

## ✅ Verification (Assura)

### ✔ DRC (Design Rule Check)
- Layout design is currently under implementation  
- Will ensure compliance with GPDK 90nm rules  

### ✔ LVS (Layout vs Schematic)
- Will verify equivalence between schematic and layout  
- Ensures correct connectivity and functionality  

### ✔ RC Extraction (RCX)
- Parasitic extraction planned after layout completion  
- Enables accurate post-layout simulation  

---

## 📈 Post-Layout Analysis *(Upcoming 🚧)*
- Compare pre-layout vs post-layout performance  
- Analyze delay and power variations due to parasitics  

---

## 📌 Key Learnings
- CMOS NAND gate design using pull-up and pull-down networks  
- Timing analysis and delay estimation  
- Power estimation using Cadence ADE  
- Understanding switching behavior in digital circuits  

---

## 🎯 Conclusion
The CMOS NAND gate has been successfully designed and verified through simulation.  
Further work includes **layout design and physical verification** to complete the full custom IC design flow.

---

## 👨‍💻 Author

**Poli Prudvi Reddy**  
📧 Email: prudvireddypoli@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/prudvi-poli  

---

## ⭐ Support
If you found this project useful, give it a ⭐ on GitHub and feel free to connect!
