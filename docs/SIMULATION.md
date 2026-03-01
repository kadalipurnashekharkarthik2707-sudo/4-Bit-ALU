# Simulation Instructions for ALU Design

This document provides detailed instructions on how to run testbenches and simulate the ALU design.

## Prerequisites
- Ensure you have the appropriate simulation tool installed (e.g., ModelSim, Vivado, etc.).
- Clone the repository to your local machine:
  ```bash
  git clone https://github.com/kadalipurnashekharkarthik2707-sudo/4-Bit-ALU.git
  ```

## Steps to Run Testbenches
1. Navigate to the testbench directory:
   ```bash
   cd 4-Bit-ALU/testbenches
   ```
2. Compile the design files along with the testbench files. For example, using ModelSim:
   ```bash
   vlog ../src/*.v 
   vlog testbench/*.v
   ```
3. Run the simulation. You can call your testbench as follows:
   ```bash
   vsim testbench_name
   ```
4. Observe the simulation results in the waveform viewer to verify the ALU functionality.

## Example Testbench Command
To run a particular testbench, use:
```bash
vsim your_testbench_name
``` 
Make sure to replace `your_testbench_name` with the actual name of your testbench.

## Conclusion
Following these steps will allow you to set up and run simulations for the ALU design. Ensure to check each test's output against expected results to validate the design thoroughly.