# 4bit_alu
4-bit ALU implemented in Verilog HDL with arithmetic, logical, and shift operations.
# 4-bit ALU using Verilog HDL

## Project Overview
This project implements a 4-bit Arithmetic Logic Unit (ALU) using Verilog HDL.  
The ALU performs different arithmetic, logical, and shift operations based on the select input.

The design is implemented using combinational logic and verified through simulation in Xilinx Vivado.



## Features
- 4-bit input operands
- 5-bit output result
- Arithmetic operations
- Logical operations
- Shift operations
- Combinational ALU design
- Simulation verified using testbench



## Operations Performed

| Select Line | Operation |

000 -> OR 
001  -> AND 
010 -> Addition 
011 -> Subtraction 
100 -> Left Shift 
101 -> Right Shift 
110 -> XOR 
111 -> XNOR 



## Files Included
### alu.v
Contains the Verilog RTL code for the ALU design.

### alu_tb.v
Contains the testbench used for simulation and verification.

### waveform.png
Simulation waveform showing different ALU operations.



## Working
- The ALU performs operations based on the value of the 'sel' input.
- Inputs 'a' and 'b' are 4-bit operands.
- The result changes according to the selected operation.
- The design uses combinational logic with a case statement.



## Tools Used
- Verilog HDL
- Xilinx Vivado



## Simulation
The ALU was simulated and verified using Vivado simulator.  
Waveforms confirm correct execution of arithmetic, logical, and shift operations.



## Learning Outcome
Through this project, I learned:
- ALU architecture and functionality
- Combinational circuit design
- Verilog case statements
- Arithmetic and logical operations in Verilog
- Testbench creation and simulation analysis
