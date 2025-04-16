# CODTECH-TASK2
Name - Yogita Shrikant Dhonge
Company - CODETECH IT SOLUTIONS
ID - CT04WM47
Domain -VLSI
Duration -March 18th,2025 to April 18th,2025
Mentor - Vaishali

Project Overview: Simple Synchronous RAM Module

Objective:

Design and implement a simple Synchronous Random Access Memory (RAM) module with basic read and write capabilities using a hardware description language like Verilog or VHDL. This module will be tested through a testbench and simulated to verify its functionality.


---

1. RAM Design Requirements

Type: Synchronous RAM

Addressable size: Configurable (e.g., 8-bit address space = 256 locations)

Data width: 8-bit or 16-bit

Control signals:

clk (clock)

we (write enable)

re (read enable)

addr (address bus)

din (data input)

dout (data output)




---

2. Functional Description

On every positive edge of the clock:

If we = 1, data at din is written to memory at address addr.

If re = 1, data from memory at address addr is loaded to dout.


Read and Write operations cannot occur simultaneously.



---

3. Deliverables

a. Code

RAM module written in Verilog (or VHDL)


b. Testbench

Simulates various scenarios:

Writing data to multiple addresses

Reading and verifying data

Attempting reads/writes without enable signals



c. Simulation

Waveform generation using tools like ModelSim, Vivado, or GTKWave

Visual confirmation of correct timing and data flow



---

4. Tools Suggested

Verilog/VHDL compiler (ModelSim, Vivado, Icarus Verilog)

Simulation tool (GTKWave, Vivado Simulation)

Text editor or IDE (VS Code with Verilog extension)



---

5. Outcome

By the end of this project, you'll have:

A working synchronous RAM design

A testbench demonstrating correct functionality

A simulation verifying your RAM behavior

Internship completion certificate from CODTECH
