# Tcam_project

This project focuses on the design and implementation of a Ternary Content Addressable Memory (TCAM) architecture using SRAM resources available on FPGA devices. TCAMs are specialized memory structures that enable efficient parallel search operations, making them widely employed in applications like network routers, packet filtering, and address translation.
Overview
The primary objective of this work is to develop an efficient TCAM architecture that can be realized on FPGA platforms, leveraging the configurable logic and embedded memory resources. The design employs algorithms to encode TCAM functionality by mapping ternary words (consisting of 0, 1, and don't-care states) onto multiple RAM blocks. Width and depth division techniques are incorporated to optimize memory utilization, allowing the implementation of large TCAM configurations within the constraints of available FPGA resources.

## Key Features

- TCAM Encoding Algorithms: Efficient algorithms to encode TCAM functionality using multiple RAM blocks, enabling parallel search operations and handling ternary words with don't-care states.
- Width and Depth Division: Techniques to divide the TCAM width and depth across multiple RAM blocks, optimizing memory utilization for large TCAM configurations.
TCAM Operations: Implementation of TCAM write, read, and lookup operations in Verilog HDL.
- Simulation and Verification: Comprehensive simulation and verification of the TCAM design using ModelSim, with various test cases to validate the correctness of the implementation.


## Repository Structure

src/: Contains the Verilog HDL source code for the TCAM implementation, including the top-level module and supporting modules. Includes the testbench files and test cases for simulation and verification of the TCAM design.

## Setup and Usage

- Clone the repository: git clone https://github.com/Anirudhsk02/Tcam_project
- Open the project in your preferred HDL development environment (e.g., Quartus Prime, Vivado).

- Compile the Verilog source files and testbench files.
- Run simulations using ModelSim or your preferred simulator to verify the TCAM functionality.
