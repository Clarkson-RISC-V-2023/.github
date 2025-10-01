- ### [MAIN REPO (top-main)](https://github.com/Clarkson-RISC-V-2023/top-main)
- ### [RISCy Buisness Google Drive](https://drive.google.com/drive/folders/1B9FN8L_GMV-wG6qtd3uNzaaNvoyyHgSz)

![Milestone 1.0 Block Diagram](https://github.com/Clarkson-RISC-V-2023/.github-private/blob/main/profile/images/Milestone_1-0.png)
![Milestone 1.1 Block Diagram](https://github.com/Clarkson-RISC-V-2023/.github-private/blob/main/profile/images/Milestone_1-1.png)
![RISC-V Logo](https://riscv.org/wp-content/uploads/2020/06/riscv-color.svg)

# Project Overview

Design a custom processor based on the open-source RISC-V architecture or a subset of it. This project's main purpose will be to develop a calculator that can perform subtraction, addition possibly multiplication and division operations. The custom processor will handle all the mathematical operations and the custom firmware will allow the processor to drive the peripherals. The base RISC-V architecture will be modified/customized to allow interface the required external logic or peripherals.
The targeted FPGA currently is the Basys 3 board as it provides a wide range of switches, push buttons and 7-segment displays. An overview of the proposed use for the FPGA GPIOs is shown in “Proposed Use of Basys 3”. This project will involve hands-on work in diverse fields, such as architecture design in the process of customizing the RISC-V architecture and planning the bases of the proposed interactive calculator. Design through the process of developing the custom processor and its additions/modifications will be further described in the section Proposed Design Architecture. Verification to verify that the RTL of this project performs as expected from the project specs, a base Universal Verification Environment (UVM) will be implemented. This project will use GitHub to implement git as a version control system.

The outcome of this project will include having created a custom processor, lots of experience in the context of decision making within logic architecture design, possible exposure to UVM, and a fully functional and very cool calculator that runs on an FPGA with custom hardware and firmware. 

### [Link to the Project Proposal](https://clarkson0-my.sharepoint.com/:w:/g/personal/schumae_clarkson_edu/EUdUE70viBBCvmclsxku4SABC-uydwZhRiyyJ6euBa7byQ?e=wxUaMR)
# Potential Free to use tools for project

1. ⭐[**RISC-V GNU Toolchain**](https://github.com/riscv-collab/riscv-gnu-toolchain): The RISC-V GNU Toolchain provides a collection of compilers, assemblers, linkers, and other tools for building software that runs on RISC-V processors. It's an essential tool for developing and compiling code for your custom RISC-V processor.

2. ⭐[**Verilator**](https://verilator.org/guide/latest/install.html): Verilator is an open-source simulator for RTL (Register Transfer Level) designs. It is used for simulating and verifying hardware designs written in Verilog or SystemVerilog. You can use Verilator to simulate your custom RISC-V processor's RTL code.

3. ⭐[**Icarus Verilog**](https://github.com/steveicarus/iverilog): Similar to Verilator, Icarus Verilog is another open-source simulator that supports the Verilog language. It's commonly used for simulating digital circuits and can be used to simulate your RISC-V processor design. [This can be used with GTKWave](https://www.youtube.com/watch?app=desktop&v=3Xm6fgKAO94)

4. [**Yosys**](https://yosyshq.net/yosys/): Yosys is an open-source synthesis tool that can synthesize RTL code written in various hardware description languages (HDLs) like Verilog and SystemVerilog. It's commonly used to convert your processor's RTL code into a gate-level netlist for FPGA or ASIC implementation. [Formal Verification on RISC-V](https://github.com/YosysHQ/riscv-formal)

5. [**FuseSoC**](http://fusesoc.net/): FuseSoC is a package manager and build system for FPGA/ASIC development. It helps manage and organize various IP cores, including RISC-V processors, and facilitates their integration into larger designs.

6. [**QEMU**](https://www.qemu.org/): QEMU is a fast and versatile open-source machine emulator and virtualizer. It can emulate RISC-V processors and can be a valuable tool for testing your processor's software stack.

7. [**Chisel**](https://www.chisel-lang.org/): Chisel is a hardware construction language embedded in Scala. It allows you to write parameterized circuit generators and has been used to design RISC-V processors.

8. [**RISC-V Proxy Kernel (pk)**](https://github.com/riscv-software-src/riscv-pk): The RISC-V Proxy Kernel is a lightweight application that serves as a bridge between the hardware and software. It's useful for early-stage development and testing of your RISC-V processor.

9. [**Rocket Chip Generator**](https://github.com/chipsalliance/rocket-chip): Rocket Chip is a generator for RISC-V cores developed at UC Berkeley. It provides a flexible platform for generating custom RISC-V processors with various features.
