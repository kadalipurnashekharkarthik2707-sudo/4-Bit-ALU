# Note

The **testbench file (`alu_tb.v`) is not included in the 4-Bit ALU repository**.

To simulate and verify the ALU operations, you need to **create and add the testbench file manually**.

## Steps

1. Create a new file named `alu_tb.v`.
2. Write the Verilog testbench code for the ALU.
3. Add the file to the project directory.
4. Compile both `alu.v` and `alu_tb.v` in your simulator.

## Example Compilation

```
iverilog alu.v alu_tb.v
vvp a.out
```

This will allow you to test the ALU functionality through simulation.
