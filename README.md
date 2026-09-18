# -Flash-Memory--EEPROM-in-Verilog-HDL
# EEPROM / Flash Memory Design and Verification using Verilog HDL

## Project Overview
This project implements a synthesizable EEPROM/Flash Memory model in Verilog HDL along with a verification testbench. The design demonstrates non-volatile memory operation, memory initialization using HEX files, synchronous read functionality, and simulation-based verification.

## Features
- Verilog HDL based EEPROM/ROM design
- Parameterized memory architecture
- Memory initialization using `$readmemh`
- Synchronous read operation
- Functional verification using testbench
- Waveform generation (VCD)
- Compatible with Icarus Verilog and EDA Playground

## Project Structure

design.sv       - EEPROM/ROM design module  
testbench.sv    - Verification testbench  
rom_init.hex    - Memory initialization data  
run.bash        - Compilation and simulation script  
wave.vcd        - Generated simulation waveform  

## Simulation Flow
1. Load memory contents from HEX file.
2. Generate clock signal.
3. Apply read addresses sequentially.
4. Read memory data synchronously.
5. Verify output through simulation logs and waveforms.
6. Generate VCD file for waveform analysis.

## Tools Used
- Verilog HDL
- Icarus Verilog (iverilog)
- VVP Simulator
- EPWave / GTKWave
- EDA Playground

## Expected Outcome
- Verified EEPROM memory model
- Reusable Verilog testbench
- Synthesizable RTL design
- Educational and research-oriented memory IP core

## Applications
- FPGA Prototyping
- SoC Verification
- Digital VLSI Design
- Embedded Systems
- Memory Architecture Studies
