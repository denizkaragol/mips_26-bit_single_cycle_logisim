# Single-Cycle MIPS Processor (Logisim)

## Overview
This project implements a single-cycle MIPS processor using Logisim. It demonstrates how instructions are executed at the hardware level within a single clock cycle.

## Features
- Single-cycle architecture
- ALU (Arithmetic Logic Unit)
- Register File
- Control Unit
- Program Counter (PC)
- Instruction Memory
- Data Memory

## Supported Instructions
- add
- sub
- lw
- sw
- beq

## Architecture
The processor is based on a standard single-cycle datapath. Each instruction is completed in one clock cycle. The control unit generates the required control signals to manage data flow between components.

## Datapath Diagram
![Datapath](screenshots/datapath.png)

## How It Works
1. The Program Counter (PC) fetches the instruction from instruction memory  
2. The instruction is decoded by the control unit  
3. The register file provides the required operands  
4. The ALU performs the operation  
5. The result is written back to the register file or memory  

## Example
