# Fifo_buffer_synch
The implemented FIFO buffer module offers functionalities for data input, output, read, write, and status flag management. The module is designed to be synchronous. The FIFO buffer can store up to eight 32-bit data elements, and it employs registers and counters to manage data movement and FIFO status.
# Verilog FIFO Buffer Simulation Project

Welcome to the Verilog FIFO Buffer Simulation Project repository! This project demonstrates the implementation and simulation of a synchronous First-In-First-Out (FIFO) buffer module using Verilog HDL. The simulation is powered by Icarus Verilog, and the results are visualized using GTKWave.

## Project Highlights

- **FIFO Buffer Module:** The project features a synchronous FIFO buffer module that efficiently manages data storage and retrieval while preserving the order of data.

- **Simulation Tools:** The simulation of the FIFO buffer is performed using Icarus Verilog, an open-source simulation and synthesis tool. The simulation results are then visually analyzed using GTKWave, an open-source waveform viewer.

## Contents

- `FIFObuffer.v`: The Verilog HDL code for the synchronous FIFO buffer module.

- `FIFObuffer_tb.v`: The Verilog test bench code used to simulate the FIFO buffer module.

## Getting Started

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/verilog-fifo-buffer.git

Install Icarus Verilog and GTKWave on your system.

Open a terminal and navigate to the project directory.
Run the simulation using the following commands:

- `iverilog -o simulation FIFObuffer_tb.v FIFObuffer.v`
- `vvp simulation`

Visualize the simulation results using GTKWave:
- `gtkwave simulation.vcd`

