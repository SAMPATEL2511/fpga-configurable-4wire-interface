# fpga-configurable-4wire-interface
Master Thesis: FPGA implementation of a configurable 4-wire interface for data acquisition and generation. VHDL code, SPI protocol architecture, simulation results, and testing.

# 🔧 FPGA-Based Configurable 4-Wire Interface for Data Acquisition & Generation

**Author:** Parth Bhalani  
**Institution:** Università degli Studi di Roma Tor Vergata 
**Degree Program:** Master of Science in Mechatronics Engineering  
**Academic Year:** 2023–2024  
**Supervisor:** Prof. Luca Di Nunzio  
**Co-Supervisor:** Dott. Valerio Campomaggiore  

---

## 📄 Thesis Summary

This repository contains the full implementation of a **configurable 4-wire SPI interface** using **FPGA technology** for efficient data acquisition and generation. Designed with **VHDL**, simulated using **ModelSim**, and deployed on an **Intel Cyclone 10 LP** board using **Quartus Prime**.

---

## 🧠 Abstract

This work presents a high-performance, SPI-based communication interface using a 4-wire configuration implemented on an FPGA. The interface supports variable data width, clock frequency, and custom protocol features, making it suitable for sensor data capture and control systems. Simulations validate behavior under multiple conditions, while real-world testing confirms electrical integrity and timing compliance using oscilloscope probes.

---

## ⚙️ Features

- ✅ SPI Master & Slave Implementation in VHDL
- ✅ Support for custom clock and data formats (MSB/LSB)
- ✅ ModelSim simulation results (4 cases)
- ✅ Timing and signal analysis via SignalTap and Oscilloscope
- ✅ Modular, reusable code structure

---

## 📂 Project Structure

| Folder            | Description |
|-------------------|-------------|
| `VHDL_Code/`      | All VHDL source files and testbenches |
| `Diagrams/`       | Electrical and timing schematics |
| `Simulation_Results/` | Waveform captures from ModelSim |
| `Videos/`         | Testing and demo videos |
| `Docs/`           | Full thesis PDF and related documents |

---

## 🖥️ Tools Used

- **Intel Quartus Prime**
- **ModelSim**
- **Cyclone 10 LP FPGA Development Kit**
- **VHDL Language**
- **SignalTap Logic Analyzer**
- **Oscilloscope for hardware verification**

---

## 🖼️ Diagrams

- ![Electrical Schematic](Diagrams/electrical_schematic.png)
- ![SPI Timing Diagram](Diagrams/timing_diagram.png)

---

## 📄 Full Report

📘 **[Download Thesis PDF](Docs/Master_Thesis_by_Parth_Bhalani.pdf)**

---

## 🧪 Simulation Results

Simulation includes multiple SPI scenarios showing protocol correctness under:
- Varying bit lengths
- Clock polarities and phases (CPOL, CPHA)
- Simulated noise and error injection

Waveforms can be found in:
- `Simulation_Results/modelsim_waveform_1.png`
- `Simulation_Results/modelsim_waveform_2.png`

