# RISC-V
# Design and Implementation of 32-bit RISC-V Pipelined Processor

## 🔹 Overview
This project focuses on the design and implementation of a 32-bit 5-stage pipelined RISC-V processor using Verilog HDL. The processor architecture is designed to improve instruction execution efficiency through pipelining while maintaining a clear separation between control and datapath units.

## 🔹 Key Features
- 5-stage pipeline architecture (IF, ID, EX, MEM, WB)
- Efficient control and datapath design
- Hazard detection mechanism
- Data forwarding unit to reduce pipeline stalls
- Basic branch handling

## 🔹 Description
The processor is designed to execute instructions in a pipelined manner, allowing multiple instructions to overlap in execution. To ensure correct operation, hazard detection and forwarding techniques are implemented to handle data dependencies and avoid pipeline stalls.

The design was simulated and verified using AMD Vivado to validate functionality and pipeline behavior.

## 🔹 Project Resources
The following project materials will be added to this repository:

- 📄 Detailed Project Report  
- 📄 Research Paper  
- 📊 Simulation Results (Waveforms)  
- 🖼️ Architecture and Pipeline Diagrams  

## 🔹 Tools Used
- Verilog HDL  
- AMD Vivado  

## 🔹 Note
This repository is intended to showcase the design methodology, architecture, and results of the project. Supporting documents and simulation outputs will be uploaded progressively.
