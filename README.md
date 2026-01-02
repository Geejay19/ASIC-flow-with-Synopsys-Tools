---

# 🧩 ASIC Flow Implementation Using Synopsys Tools  
![Status](https://img.shields.io/badge/Status-Completed-2ecc71?style=for-the-badge)  
![Project](https://img.shields.io/badge/Project-ASIC%20Flow%20Documentation-blue?style=for-the-badge)  
![Tools](https://img.shields.io/badge/Tools-Synopsys%20DC%20%7C%20ICC2%20%7C%20kLayout-6f42c1?style=for-the-badge)  
![Tech](https://img.shields.io/badge/Technology-SAED%2032nm-orange?style=for-the-badge)  
![Category](https://img.shields.io/badge/Design-RTL%20to%20GDSII-green?style=for-the-badge)

---

## 🔎 Overview

This repository documents a complete **ASIC design flow** performed using **Synopsys Design Compiler (DC)** and **Synopsys IC Compiler II (ICC2)**, targeting the **SAED 32nm technology node**.  
The project demonstrates the full journey from **RTL synthesis** to **physical implementation**, including:

- Schematic generation  
- Area, power, and timing analysis  
- Floorplanning  
- Power grid creation  
- Placement & routing  
- GDSII visualization  

This repository is **documentation‑only** and contains:

- Screenshots captured during each stage of the ASIC flow  
- A detailed final report summarizing results, observations, and parameter analysis  

---

# 🧱 Project Structure

```
ASIC-flow-with-Synopsys-Tools/
│
├── screenshots/
│   ├── synthesis/
│   ├── reports/
│   ├── floorplan/
│   ├── power-grid/
│   ├── placement/
│   ├── routing/
│   └── gds/
│
└── Final_Report.pdf
```

- **screenshots/** — Contains all visual outputs captured during the ASIC flow  
- **Final_Report.pdf** — A complete written summary of the synthesis and PnR process  

---

# 🛠 Tools & Technologies

### **Synopsys Design Compiler (DC)**
Used for:
- RTL synthesis  
- Netlist generation  
- Area, power, and timing reporting  
- Schematic visualization  

### **Synopsys IC Compiler II (ICC2)**
Used for:
- Floorplanning  
- Power grid generation  
- Pin assignment  
- Placement  
- Routing  
- Layout inspection  

### **kLayout**
Used for:
- Viewing the final GDSII layout  

### **Technology**
- **SAED 32nm Standard Cell Library**

---

# 📊 Parameter Exploration

The design was synthesized using multiple parameter configurations (R, C, W_X, W_K).  
The final report includes:

- Area comparison  
- Power comparison  
- Observations on scaling behavior  

This demonstrates understanding of how architectural parameters influence silicon cost and power consumption.

---

# 🖼️ Visual Outputs Included

The repository contains screenshots for:

### ✔ Synthesis Stage
- RTL schematic  
- Area report  
- Power report  
- Timing report  
- Cell usage summary  

### ✔ Physical Design Stage
- Floorplan  
- Power rings (VDD/VSS)  
- Power grid prototyping  
- Pin assignment  
- Standard cell placement  
- Routing  
- Final layout (zoomed views)

### ✔ GDSII Visualization
- Final chip layout viewed in kLayout  

---

# 🎯 Purpose of This Repository

This project highlights:

- Practical experience with **ASIC design flow**  
- Familiarity with **Synopsys EDA tools**  
- Understanding of **physical design concepts**  
- Ability to analyze and document **area, power, and timing**  

