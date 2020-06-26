# Verilator Starter

This repo has a simple starter testbench file for simulating
Verilog files with [Verilator](https://www.veripool.org/wiki/verilator).

The script `gen-vcd` shows how to pass the `testbench.cpp` file
to Verilator and get a `.vcd` (Value Change Dump) file as an output.
You can also just use `gen-vcd` directly to generate a `.vcd` file.

`./gen-vcd <filename>.v` will compile, simulate, and generate `<filename>.vcd` for you.

`gen-vcd` also accepts Verilog files on stdin: `cat <filename>.v | ./gen-vcd -`
