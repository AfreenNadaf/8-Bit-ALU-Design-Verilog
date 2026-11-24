# 8-Bit ALU Design Using Verilog

## Project Overview
This project implements an 8-bit Arithmetic Logic Unit (ALU) using Verilog HDL.

## Objective
To design and simulate an ALU capable of performing arithmetic and logical operations.

## Operations

| Select | Operation |
|---|---|
| 000 | Addition |
| 001 | Subtraction |
| 010 | AND |
| 011 | OR |
| 100 | XOR |

## Inputs
- A[7:0] – 8-bit input
- B[7:0] – 8-bit input
- Sel[2:0] – Operation selector

## Outputs
- Result[7:0] – 8-bit result
- CarryOut – Carry output
- Zero – Indicates whether the result is zero

## Tools Used
- Verilog HDL
- Icarus Verilog
- GTKWave
- Yosys
- NextPNR (if used)
- openFPGALoader (if used)

## Simulation
The ALU is verified using a Verilog testbench. Simulation waveforms are viewed using GTKWave.

## Conclusion
The project demonstrates arithmetic and logical operations using an 8-bit ALU design in Verilog HDL.
