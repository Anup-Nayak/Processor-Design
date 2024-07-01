# Processor Design in Logisim

## Project Overview

This project involves designing a 32-bit single-cycle processor using Logisim-evolution. The processor is based on a mini RISC-V Instruction Set Architecture (ISA) and supports a range of instructions including arithmetic, logic, and memory operations. The design includes an Arithmetic Logic Unit (ALU), Register File, and Control Unit to manage instruction execution.

## Project Components

1. **Arithmetic Logic Unit (ALU)**:
    - Performs arithmetic and logical operations such as addition, subtraction, bitwise AND/OR, shifts, and comparisons.
    - Handles 32-bit inputs and generates outputs including overflow and zero flags.

2. **Register File**:
    - Contains nine specified registers, ensuring proper read/write operations.
    - Maintains the zero register constraint and integrates it into the processor design for accurate instruction execution.

3. **Control Unit**:
    - Manages the execution of instructions.
    - Coordinates the ALU, Register File, and memory operations to ensure correct operation sequencing and data flow.

### Simulation

The alu.circ must be added as a logisim library in processor_4.circ.

To simulate the design, open the `processor.circ` file in Logisim-evolution. Use the built-in tools to step through the execution of instructions and observe the behaviour of the processor components.

### Testing

1. Open `testbench.circ` in Logisim-evolution.
2. Run the simulation to verify the functionality of the processor.
3. Modify the test cases as needed to test different instructions and scenarios.

## Requirements

- Logisim-evolution

## Example

Here's a simple example of how to use the processor design:

1. Load the `processor.circ` file in Logisim-evolution.
2. Enter a program in the instruction memory.
3. Run the simulation and observe the output on the data memory and registers.



