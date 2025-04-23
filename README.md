# CASE-STUDY-FOR-32-BIT-PIPELINED-CPU-DESIGN-WITH-NEW-ALU-ARCHITECTURE-
This project showcases the design and evaluation of a 32-bit pipelined CPU featuring a custom Arithmetic Logic Unit (ALU). It includes RTL design, simulation, logic synthesis, and performance analysis of four different adder architectures and a 32-bit comparator. The goal is to explore performance trade-offs in CPU datapath design using realistic ASIC design flows.

## 🧠 Overview
This project is a hardware design case study focused on implementing and evaluating a 32-bit pipelined Central Processing Unit (CPU) with a custom Arithmetic Logic Unit (ALU). The design simulates and synthesizes the CPU using various adder architectures to compare performance, timing, area, and power.

Key components of the project:

Pipelined CPU Design: The CPU fetches and executes multiple instructions concurrently using a two-stage pipeline, controlled by external clock signals.

Custom ALU Implementation: Supports arithmetic and logic operations such as ADD, SUB, MUL, AND, OR, XOR, and XNOR. Operands are selected through configurable multiplexers.

Adder Architectures: Designed and tested with four different 32-bit adder types to analyze speed and complexity:

Carry Ripple Adder (CRA)

Carry Lookahead Adder (CLA)

Carry Skip Adder (CSA)

Carry Select Adder (CSeA)

Comparator Block: A tree-structured 32-bit comparator is implemented for evaluating logical conditions.

The design flow includes RTL simulation, logic synthesis, post-synthesis simulation, place & route, and waveform verification using tools like Cadence Genus, Innovus, and SimVision, with FreePDK45 libraries.

This project showcases the real-world VLSI design process, from Verilog coding to hardware optimization, and offers insights into the impact of architectural choices on performance metrics such as clock frequency, path delay, and power efficiency.




### Components:

- Pipelined 32-bit datapath
- Custom ALU with operations:
  - ADD, SUB, MUL, AND, OR, XOR, XNOR
- Adder architecture comparison:
  - Carry Ripple Adder (CRA)
  - Carry Lookahead Adder (CLA)
  - Carry Skip Adder (CSA)
  - Carry Select Adder (CSeA)
- 32-bit Comparator (tree-structured)
- Full ASIC-style flow: RTL → Synthesis → Place & Route → Post-layout simulation

## 🔧 Technologies Used

- Verilog HDL
- Cadence Genus (synthesis)
- Cadence Innovus (place & route)
- SimVision (waveform viewer)
- FreePDK45 (45nm standard cell library)
