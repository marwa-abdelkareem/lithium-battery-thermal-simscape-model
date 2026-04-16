# Lithium-Ion Battery Electro-Thermal Model – MATLAB/Simscape

---

<p align="center">
  <img src="Block Diagram2.png" width="750"/>
</p>

## Project Overview

This project presents a **coupled electro-thermal lithium-ion battery model** developed using **MATLAB, Simulink, and Simscape Electrical**.

The model captures both **electrical dynamics and thermal behavior** of a lithium-ion battery cell to enable realistic simulation under dynamic load conditions.

---

## Engineering Motivation

Accurate battery modeling is essential for:
- Electric Vehicle (EV) system design  
- Battery Management Systems (BMS) development  
- Energy Storage System (ESS) optimization  
- Thermal safety analysis and validation  

---

## Model Architecture

<p align="center">
  <img src="Simulink model Battery.png" width="750"/>
</p>

**Figure 1: Electro-thermal lithium-ion battery Simulink model**

---

## System Signals

<p align="center">
  <img src="System Signals.png" width="750"/>
</p>

System signals represent:
- Internal states of the battery model  
- Input/output interactions  
- Monitoring variables for analysis  

---

## Simulation Results

<p align="center">
  <img src="output signals.png" width="750"/>
</p>

**Figure 2: Battery output response under dynamic load conditions**

### Key Observations
- Stable voltage response under varying load  
- Accurate State of Charge (SOC) evolution  
- Temperature rise due to internal heat generation  
- Strong electro-thermal coupling behavior  

---

## Objectives

- Develop a coupled electro-thermal battery model  
- Simulate SOC under dynamic operating conditions  
- Analyze heat generation and thermal effects  
- Evaluate battery performance under load variations  
- Support BMS design and validation workflows  

---

## Model Features

### Electrical Domain
- Equivalent circuit battery model  
- Internal resistance effects  
- SOC estimation  
- Voltage response dynamics  

### Thermal Domain
- Heat generation modeling  
- Thermal mass representation  
- Temperature dynamics  
- Electro-thermal coupling  

---

## Applications

- Electric Vehicle battery systems  
- Battery Management Systems (BMS)  
- Energy Storage Systems (ESS)  
- Thermal safety analysis  
- Academic and research simulations  

---

## Modeling Environment

- MATLAB R2024a  
- Simulink  
- Simscape Electrical  

---

## How to Run

1. Clone the repository  
2. Open MATLAB  
3. Navigate to project folder  
4. Open `batteryCellModelling.slx`  
5. Click Run  

---

## System Files

- `batteryCellModelling.slx` → Main Simulink model  
- `Block Diagram2.png` → System architecture  
- `Simulink model Battery.png` → Model implementation  
- `System Signals.png` → Internal signal structure  
- `output signals.png` → Simulation results  

---

## Author

**Marwa Abdelkareem**  
GitHub: marwa-abdelkareem  

---

## License
This project is licensed under the MIT License.
