# Lithium-Ion Battery Electro-Thermal Model

---

## Overview

This project presents an electro-thermal lithium-ion battery cell model developed using MATLAB, Simulink, and Simscape Electrical.

The model captures both electrical and thermal behavior of a lithium-ion battery cell to enable realistic simulation under dynamic operating conditions.

It is mainly used for:
- Electric Vehicle (EV) systems
- Battery Management Systems (BMS)
- Energy Storage Systems (ESS)
- Academic and research studies

---

## Model Overview

<p align="center">
  <img src="./Simulink%20model%20Battery.png" width="700"/>
</p>

---

## System Signals

The system signals include inputs, internal states, and outputs used for analysis and monitoring of the battery behavior.

Note:
System signals represent the full model interaction, while output signals are only a subset of measured results.

---

<p align="center">
  <img src="./System%20Signals.png" width="700"/>
</p>

The simulation results show:
- Battery voltage response
- State of Charge (SOC)
- Temperature variation
- System performance under load

---

## Objectives

- Develop a coupled electro-thermal battery model
- Simulate SOC under dynamic load conditions
- Analyze heat generation and thermal effects
- Evaluate performance under different scenarios
- Support BMS testing and validation

---

## Modeling Environment

- MATLAB R2024a  
- Simulink  
- Simscape Electrical  

---

## Features

Electrical:
- Equivalent circuit model
- Internal resistance
- SOC estimation
- Voltage response

Thermal:
- Heat generation
- Thermal mass modeling
- Temperature dynamics
- Electro-thermal coupling

---

## How to Run

1. Clone the repository  
2. Open MATLAB  
3. Navigate to project folder  
4. Open `batteryCellModelling.slx`  
5. Click Run

---

## Repository Structure

- batteryCellModelling.slx  
- Simulink model Battery.png  
- System Signals.png  
- output signals.png  
- README.md  
- LICENSE  

---

## Applications

- EV battery modeling
- Thermal management systems
- Energy storage systems
- Battery performance analysis
- Academic simulations

---

## Author

Marwa Abdelkareem  
GitHub: marwa-abdelkareem  

---

## License

This project is licensed under the MIT License.
