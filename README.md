# Yet Another MCU From Scratch - 16b (YAMCUFS)

## What is this project?
As the name suggests, in this repository I will be building a complete 16-bit MCU (Microcontroller Unit). Not only that but I also will make its own assembly language, programming language and finally I would like to make a mini-os.

## Hardware Design (Logisim)
The processor and its components were built from the ground up using Logisim-evolution. Below are the schematics of the main modules:

### Main System (YAMCUFS)
The complete Harvard architecture microcontroller, integrating the CPU core, instruction memory (ROM), and data memory (RAM).
![Main System](hardware/diagram_YAMCUFS.png)

### Arithmetic Logic Unit (ALU)
Handles all the mathematical and logical operations (ADD, SUB, AND, OR, XOR, shifts, and comparisons).
![Arithmetic Logic Unit](hardware/diagram_ALU.png)

### Register File
Contains the 16 general-purpose 16-bit registers (R0 to R15), with R0 hardwired to zero.
![Register File](hardware/diagram_REGFILE.png)

### Program Counter (PC)
Controls the execution flow, instruction fetching, and branching/jumping logic.
![Program Counter](hardware/diagram_PC.png)