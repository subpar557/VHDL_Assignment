# VHDL_Assignment

Embedded System VHDL Assignment
This repository contains VHDL code and test cases for embedded system assignment. The code is compiled using GHDL and the waveforms is visualized using GTKWave. The development environment used is Visual Studio Code (VSCode).

Table of Contents
Introduction
Prerequisites
Getting Started
Cloning the Repository
Installing GHDL
Installing GTKWave
Setting up VSCode
Running Test Cases
Project Structure
Introduction
Prerequisites
Ensure you have the following software installed on your system:

GHDL
GTKWave
Visual Studio Code
Getting Started
Cloning the Repository
git clone https://github.com/Aayush518/Embedded-System-VHDL.git
cd Embedded-System-VHDL
Installing GHDL
Follow the instructions on the GHDL GitHub repository to install GHDL on your system.

Installing GTKWave
Follow the instructions on the GTKWave website to install GTKWave on your system.

Running Test Cases
Describe how to run the test cases using GHDL and how to visualize waveforms with GTKWave.

# Example command for running GHDL
ghdl -a your_test_bench.vhd
ghdl -e your_test_bench
ghdl -r your_test_bench --wave=wave.ghw
# Example command for GTKWave
gtkwave wave.ghw
Project Structure
├── src/                    # VHDL source files
│   ├── module1.vhd
│   ├── module2.vhd
│   └── ...
├── test/                   # Testbench files
│   ├── testbench1.vhd
│   ├── testbench2.vhd
│   └── ...
└── README.md               # Project documentation
