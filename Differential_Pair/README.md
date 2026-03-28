# 📘 CMOS Differential Pair Design & Analysis (GPDK 90nm)

<p align="center">
  <b>Analog IC Design | Differential Amplifier | Small-Signal Analysis</b><br>
  Cadence Virtuoso • Spectre • GPDK 90nm
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Technology-GPDK90nm-blue">
  <img src="https://img.shields.io/badge/Tool-Cadence%20Virtuoso-orange">
  <img src="https://img.shields.io/badge/Analysis-DC%20%7C%20AC%20%7C%20Transient-green">
</p>

---

## 🚀 Overview

This project presents the **design and analysis of a CMOS Differential Pair**, a fundamental building block in analog IC design.

The circuit amplifies the **difference between two input signals** while suppressing common-mode components.

---

## 📂 Project Structure

```
Differential_Pair/
│── README.md
│── images/
│ ├── Differential_Pair_Schematic.png
│ ├── Differential_Pair_DC_Setup.png
│ ├── Differential_Pair_DC_Result.png
│ ├── Differential_Pair_AC_Setup.png
│ ├── Differential_Pair_AC_Result.png
│ ├── Differential_Pair_Transient_Setup.png
│ ├── Differential_Pair_Transient_Result.png
│── files/
```


---

## 🛠️ Tools & Technology

- **Cadence Virtuoso**
- **Spectre Simulator**
- **PDK:** GPDK 90nm

---

## 📐 Schematic Design

<p align="center">
  <img src="Images/Differential_Pair_Schematic.png" width="650"/>
</p>

### Circuit Components:

- NMOS differential pair  
- Resistive loads (R0, R1)  
- Tail current source (Idc = 200 µA)  
- Supply voltage: **VDD = 1.2 V**

---

## ⚙️ Working Principle

### 🔹 Differential Operation

Inputs:
- \( V_{in+} \)
- \( V_{in-} \)

Outputs:
- \( V_{o1} \), \( V_{o2} \)

👉 When:
- \( V_{in+} > V_{in-} \)  
  → Left transistor conducts more  
  → \( V_{o1} ↓ \), \( V_{o2} ↑ \)

- \( V_{in+} < V_{in-} \)  
  → Right transistor conducts more  
  → \( V_{o1} ↑ \), \( V_{o2} ↓ \)

---

### 🔹 Key Concept

\[
V_{diff} = V_{in+} - V_{in-}
\]

The circuit amplifies differential signals while rejecting common-mode noise.

---

# 🧪 DC Analysis

### 🔹 Setup

<p align="center">
  <img src="images/Differential_Pair_DC_Setup.png" width="600"/>
</p>

### 🔹 Result

<p align="center">
  <img src="images/Differential_Pair_DC_Result.png" width="600"/>
</p>

### 🔹 Observations

- Smooth transfer characteristics  
- Symmetric behavior around operating point  
- Proper differential switching  

---

# 📈 AC Analysis

### 🔹 Setup

<p align="center">
  <img src="images/Differential_Pair_AC_Setup.png" width="600"/>
</p>

### 🔹 Result

<p align="center">
  <img src="images/Differential_Pair_AC_Result.png" width="600"/>
</p>

### 🔹 Observations

- Constant gain at low frequencies  
- Gain roll-off at higher frequencies  
- Bandwidth limitation observed  

---

# ⚡ Transient Analysis

### 🔹 Setup

<p align="center">
  <img src="images/Differential_Pair_Transient_Setup.png" width="600"/>
</p>

### 🔹 Result

<p align="center">
  <img src="Images/Differential_Pair_Transient_Result.png" width="650"/>
</p>

### 🔹 Observations

- Complementary outputs  
- Clear differential amplification  
- Stable switching behavior  

---

## 📊 Key Insights

- Tail current controls gain and linearity  
- Device matching is critical  
- Load resistance impacts gain  
- Gain vs bandwidth trade-off  

---

## 📌 Key Learnings

- Differential amplifier fundamentals  
- Biasing and current steering  
- Frequency response analysis  
- Analog design trade-offs  

---

## 🎯 Conclusion

The CMOS Differential Pair demonstrates:

- Accurate differential amplification  
- Symmetric output behavior  
- Expected DC, AC, and transient characteristics  

This forms the foundation for:

- Operational Amplifiers  
- Comparators  
- Analog Front-End Circuits  

---

## 👨‍💻 Author

**Poli Prudvi Reddy**  
📧 prudvireddypoli@gmail.com  
🔗 https://www.linkedin.com/in/prudvi-poli  

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐
