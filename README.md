# VLSI_PD_PROJECT
<details>
<summary> Day 0 - Tools Installation 
</summary>

# Day 0 - Tools Installation
## yosys
```bash
$sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ git Submodule Update --Init(Yosys source code expects a git submodule called abc to be initialized and updated)
$ make
$ sudo make install
```
![yosys_install](/home/partha/Pictures/Screenshots/yosys_installing.png)

</details>

<details>
<summary> Day 1 - Introduction to Verilog RTL Design and Synthesis
</summary>
 
