# 8-bit Arithmetic Logic Unit (ALU) using Verilog HDL

## Overview

This project implements an **8-bit Arithmetic Logic Unit (ALU)** in **Verilog HDL**. The ALU performs arithmetic, logical, and shift operations based on a **3-bit select (SEL)** signal. The design follows a modular approach, where each operation is implemented as an individual Verilog module and integrated into a top-level ALU.

---

## Features

- 8-bit combinational ALU
- Modular Verilog implementation
- Carry Out (COUT) and Zero (ZERO) flag generation
- Functional verification using a Verilog testbench
- RTL schematic and simulation waveform verification

---

## Supported Operations

| SEL | Operation |
|:---:|-----------|
|000|Addition|
|001|Subtraction|
|010|AND|
|011|OR|
|100|XOR|
|101|NOT|
|110|Shift Left|
|111|Shift Right|

---

## Project Structure

```
8-bit-ALU-Verilog
│
├── src/
├── testbench/
├── waveform/
└── README.md
```

---

## Simulation Result

The ALU was verified using a Verilog testbench. The simulation confirms correct operation for all supported functions.

### Simulation Waveform

![Simulation Waveform](waveform/Waveform-ALU.png)

### RTL Schematic

![RTL Schematic](waveform/RTL_Schematic-ALU.png)

---

## Tools Used

- Verilog HDL
- Xilinx Vivado
- Git
- GitHub

---

## Key Learnings

- Designed an 8-bit ALU using modular Verilog HDL
- Implemented arithmetic, logical, and shift operations
- Generated Carry and Zero status flags
- Verified functionality through simulation
- Interpreted RTL schematics generated after synthesis

---
