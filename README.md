# Pipelined-RISC
# MIPS32 Processor Pipeline Simulation

I have implemented a MIPS32 processor pipeline simulation module in Verilog. This module emulates a simplified 5-stage pipeline processor with support for various instructions and memory operations.

## Features

- **Pipeline Architecture**: The module is structured as a 5-stage pipeline, including the stages of Instruction Fetch (IF), Instruction Decode (ID), Execution (EX), Memory Access (MEM), and Write Back (WB).
- **Instruction Set**: The module supports a subset of the MIPS32 instruction set, including R-type and I-type instructions such as ADD, SUB, AND, OR, SLT, MUL, ADDI, SUBI, SLTI, LW, SW, as well as branching instructions BEQZ and BNEQZ.
- **Memory Hierarchy**: The simulated memory hierarchy includes separate instruction and data memory arrays.
- **Branch Handling**: The pipeline module handles branching instructions and maintains a `TAKEN_BRANCH` signal to track taken branches.
- **Halting**: The module supports the HALT instruction to halt the processor.


