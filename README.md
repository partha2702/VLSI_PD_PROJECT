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

<img width="1000" height="877" alt="yosys_installing" src="https://github.com/user-attachments/assets/9a711c2b-5378-4a49-bd30-a6844137e7ac" />

---
## Iverilog
```bask
$ sudo apt-get install iverilog
```
<img width="1036" height="366" alt="iverilog_installing" src="https://github.com/user-attachments/assets/4f31dffd-7e08-47ae-b5e1-ee6abdbb88cf" />

----

## GTKWAVE

```bash
$ sudo apt update
$ sudo apt install gtkwave
```

<img width="1116" height="772" alt="gtkwave_installing" src="https://github.com/user-attachments/assets/75d2d10a-10e9-4e77-a717-e2bd2a6d2947" />

---
</details>

<details>
<summary> Day 1 - Introduction to Verilog RTL Design and Synthesis
</summary>
 
 # Day 1 - Introduction to Verilog RTL Design and Synthesis

 ## Introdution to Open-Source tools Simulator Iverilog

---
</details>

<details>
<summary> Day 2 - Timing libs, Hierarchical vs Flat Synthesis and Efficient Flop Coding Styles 
</summary>
 
# Timing libs, Hierarchical vs Flat Synthesis and Efficient Flop Coding Styles 

---

</details>

<details>
<summary> Day 3 - Combinational and Sequential Optimizations
</summary>
 
# Combinational and Sequential Optimizations

---
</details>

<details>
<summary> Day 4 - GLS, Blocking vs Non-blocking and Synthesis-Simulation Mismatch
</summary>
 
# GLS, Blocking vs Non-blocking Statement and Synthesis-Simulation Mismatch

----
</details>

<details>
<summary> Day 5 -Introduction to DFT
</summary>
 
# Introduction to DFT
 
 ----
</details>
