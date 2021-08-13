This repository helps you quickly setup a SystemVerilog starter template
with a basic Verilator testbench

## Getting started



### Dependencies
- Install Verilator >= v4.0 (See https://verilator.org/guide/latest/install.html)
- Fusesoc >= 1.12 (See https://fusesoc.readthedocs.io/en/stable/user/installation.html)

Tested on Linux Ubuntu

```
git clone https://github.com/saw235/rtl-starter.git
cd rtl-starter

# Add fusesoc libraries and dependencies 
fusesoc library add my_design .
fusesoc library add fusesoc-cores https://github.com/fusesoc/fusesoc-cores

# Runs simulation
fusesoc run --target=sim my_design
```
