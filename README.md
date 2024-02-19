# VHDL_Assignment
This repository contains VHDL code and test cases for embedded system assignment. The code is compiled using GHDL and the waveforms is visualized using GTKWave. The development environment used is Notepad++.


# Prerequisites
Ensure you have the following software installed on your system:

GHDL:-
GTKWave
Notepad++

# Installing GHDL
Follow the instructions on the GHDL GitHub repository to install GHDL on your system.

# Installing GTKWave
Follow the instructions on the GTKWave website to install GTKWave on your system.

Running Test Cases
Describe how to run the test cases using GHDL and how to visualize waveforms with GTKWave.

# Example command for running GHDL
ghdl -a your_test_bench.vhd 
ghdl -e your_test_bench
ghdl -r your_test_bench --wave=wave.ghw
# Example command for GTKWave
gtkwave wave.ghw
