# Implementation of a MIPS32 Pipeline Processor

This project involves implementing a **MIPS32 pipelined processor** with **hazard handling/resolution**, supporting:

- **8 R-type instructions**
- **6 I-type instructions**
- **1 J-type instruction**

## Features

- Full **control signals** for proper pipeline operation
- **Step-by-step execution trace** showing each instruction passing through the pipeline stages:
  - Instruction Fetch (IF)
  - Instruction Decode (ID)
  - Execute (EX)
  - Memory Access (MEM)
  - Write Back (WB)
