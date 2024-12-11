# Design-and-Implementation-of-32-bit-Single-Cycle-MIPS-Processor
Designed and verified a 32-bit MIPS processor using SystemVerilog, focusing on modular architecture and functionality. This project marks the beginning of my exploration into VLSI and SoC design.
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
# MIPS Processor Design and Verification

## Overview
This project involves the design and verification of a 32-bit **MIPS processor** using **SystemVerilog**. The processor implements a basic MIPS architecture, including key modules such as instruction fetch, decode, execute, memory access, and write-back stages. The project aims to provide hands-on experience in VLSI and SoC design, with a focus on modular design, verification, and understanding the functionality of each component within the processor.

## Key Features
- **32-bit MIPS Processor Design**: Developed the processor with a clear modular architecture, implementing core components such as ALU, register file, and memory access units.
- **SystemVerilog for Verification**: Created structured testbenches to verify key components and their interactions, ensuring the processor performs correctly in various scenarios.
- **Waveform Analysis**: Used tools like EDA Playground for debugging and analyzing waveforms to ensure the correctness of signal propagation and computation results.

## Project Structure
- **instruction.sv**: Instruction set architecture of MIPS.
- **alu.sv**: ALU module for arithmetic and logic operations.
- **mips_processor.sv**: Top-level design module for the MIPS processor.
- **testbench.sv**: Testbench for simulating and verifying the processor’s functionality.
- **register_file.sv**: Register file module to store and retrieve data.
- **memory.sv**: Memory module for data storage.
- **control_unit.sv**: Control unit to manage the processor’s control signals.


## Prerequisites
- A SystemVerilog simulator like [EDA Playground](https://www.edaplayground.com/) or [ModelSim](https://www.mentor.com/products/fpga/modelsim) is required for simulation and verification.
- Basic understanding of MIPS architecture and SystemVerilog.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
