# Parameterized ALU Verification using Verilog HDL

## Project Overview

This project focuses on the verification of a parameterized Arithmetic Logic Unit (ALU) using Verilog HDL. The ALU supports multiple arithmetic and logical operations along with status flag generation and error handling. Verification was carried out using a self-checking testbench and reference model in QuestaSim/ModelSim.

The project mainly emphasizes RTL verification, waveform debugging, timing synchronization, and coverage analysis.

---

## Features of the ALU

* Parameterized ALU architecture
* Arithmetic and logical operation support
* Signed and unsigned arithmetic
* Comparison operations
* Shift and rotate operations
* Multi-cycle multiplication operations
* Overflow and carry detection
* Error handling for invalid commands and inputs

---

## Supported Arithmetic Operations

* Addition
* Subtraction
* Addition with carry
* Subtraction with borrow
* Increment/Decrement
* Signed Addition
* Signed Subtraction
* Multiplication Operations
* Comparison Operations

---

## Supported Logical Operations

* AND / NAND
* OR / NOR
* XOR / XNOR
* Bitwise NOT
* Left and Right Shift
* Left and Right Rotate

---

## Verification Methodology

Verification was implemented using:

* Self-checking Verilog testbench
* Reference model based comparison
* Directed and corner-case testing
* Waveform analysis
* Coverage-driven verification

The DUT outputs were continuously compared with the outputs generated from the reference model. PASS/FAIL messages were automatically displayed during simulation.

---

## Testbench Features

* Clock and reset generation
* Task-based stimulus generation
* Automatic result comparison
* PASS/FAIL tracking
* Corner-case verification
* Multi-cycle operation synchronization
* Coverage analysis support

---

## Tools Used

* Verilog HDL
* QuestaSim / ModelSim
* Vivado
* Linux Environment

---

## Coverage Results

* Statement Coverage: 99%
* Branch Coverage: 98.13%
* FEC Expression Coverage: 100%
* FEC Condition Coverage: 88.57%
* Toggle Coverage: 70.92%
* Overall Coverage: 91.32%

---

## Simulation Summary

* Total Test Cases: 177
* Passed Test Cases: 154
* Failed Test Cases: 23

Failures were mainly observed in:

* Signed arithmetic operations
* Multiplication latency handling
* Result extension mismatches
* Comparison flag mismatches
* Invalid command handling

---

## Learning Outcomes

Through this project, practical experience was gained in:

* RTL verification flow
* Self-checking testbench development
* Debugging using simulation waveforms
* Handling multi-cycle operations
* Coverage analysis and reporting
* Verification of corner-case scenarios

---

## Future Improvements

* Constrained-random verification
* Assertion-based verification
* Functional coverage implementation
* SystemVerilog/UVM-based environment
* Additional ALU operations and optimizations
