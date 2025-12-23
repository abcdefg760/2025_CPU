# 2025 CPU Project

This repository contains a CPU implementation as part of a computer architecture course or project.

## Project Structure

- `SampleCPU/` - Main CPU implementation files
  - `mycpu_top.v` - Top-level CPU module
  - `mycpu_core.v` - CPU core implementation
  - `IF.v` - Instruction Fetch stage
  - `ID.v` - Instruction Decode stage
  - `EX.v` - Execute stage
  - `MEM.v` - Memory access stage
  - `WB.v` - Write Back stage
  - `CTRL.v` - Control unit
  - `lib/` - Library components (ALU, register file, etc.)
- `task-11.5/` - Additional tasks or examples

## Description

This is a MIPS-based CPU implementation, likely for educational purposes or as part of a computer architecture course. The design follows a pipelined approach with separate stages for instruction fetch, decode, execute, memory access, and write back.

## Getting Started

To use this project:
1. Clone the repository
2. Open with a Verilog-compatible IDE or simulator
3. Compile and simulate the CPU modules

## Files

- Verilog source files (.v)
- Documentation files in PDF format
- Test benches and examples

## License

Add your license information here.