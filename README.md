# HunStat2 – A Simple and Low-Cost Potentiostat with EIS Capability

This repository contains the open-source hardware and software of the **HunStat2** potentiostat described in the manuscript  
*HunStat2 – a Simple and Low-Cost Potentiostat with Electrochemical Impedance Spectroscopy Capability*  
(Analytical Methods, Royal Society of Chemistry, 2025)

---

## About HunStat2
**HunStat2** is a low-cost (30 USD), open-source potentiostat capable of performing  
- **cyclic voltammetry (CV)**,
- **open-circuit potential (OCP)** measurements,
- **electrochemical impedance spectroscopy (EIS)**.  

The instrument is based on the **AD5941** analog front-end and a **Seeeduino XIAO RP2040** microcontroller, which together enable accurate DC and AC electrochemical techniques.  
The system supports EIS at the measured OCP potential and includes free, standalone Windows software for data acquisition and visualization.  

HunStat2 is designed for **analytical chemistry, electrochemical research, and education**, allowing researchers and students to perform reliable electrochemical experiments at minimal cost.

---

## Repository Structure

- **Hardware**: This folder contains the files required for ordering the printed circuit board.
- **Samples**: CV and EIS measurement diagrams of different samples measured with HunStat2.
- **Software**: Arduino and GUI software components of HunStat2.
- **supplementary**: Supporting document of the project.
