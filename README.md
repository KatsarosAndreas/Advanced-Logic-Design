# Advanced Logic Design

Digital circuit design and implementation using **Logisim Evolution**—demonstrating proficiency in combinational logic, sequential circuits, and processor architecture for embedded systems and hardware engineering roles.

## Overview

This repository contains exercises covering fundamental to advanced digital design concepts using Logisim Evolution—essential skills for FPGA development, ASIC design, and computer architecture engineering.

**Key Focus Areas:**
- **Combinational Logic**: Adders, multiplexers, decoders, encoders
- **Sequential Circuits**: Flip-flops, registers, counters, state machines
- **Arithmetic Units**: ALU design, multipliers, comparators
- **Memory Systems**: RAM/ROM interfacing, address decoding
- **Processor Architecture**: Datapath design, control units

---

## Project Structure

### Exercise 1: Combinational Logic Fundamentals
**Components Designed:**
- Multi-bit adders (ripple-carry, carry-lookahead)
- Multiplexers and demultiplexers
- Priority encoders and decoders
- Magnitude comparators

**Learning Outcomes:**
- Boolean algebra minimization
- Karnaugh map optimization
- Propagation delay analysis

**Files:** `ASKHSH1_2.circ`, `SCREENSHOT1_ASKHSH1.circ`

---

### Exercise 3: Sequential Logic & State Machines
**Components Designed:**
- D flip-flops and T flip-flops
- Synchronous counters (up/down, modulo-N)
- Shift registers (SISO, SIPO, PISO, PIPO)
- Finite state machines (FSM) for sequence detection

**Applications:**
- Clock dividers for frequency synthesis
- Serial-to-parallel data conversion
- Pattern recognition circuits

**Files:** `askhsh3.1.circ`, `ASKHSH3.circ`

---

### Exercise 5: Arithmetic & Logic Units
**Components Designed:**
- 4-bit ALU (ADD, SUB, AND, OR, XOR, NOT)
- Multipliers (array multiplier, Booth's algorithm concepts)
- Barrel shifters (left/right logical shifts)
- Overflow and zero-flag generation

**Design Methodology:**
- Modular component hierarchy
- Bus-based data routing
- Control signal generation

**Files:** `ASKHSH2.circ`

---

### Exercise 6: Memory Interfacing & Address Decoding
**Components Designed:**
- RAM/ROM modules with read/write control
- Address decoders (3-to-8, 4-to-16)
- Memory-mapped I/O systems
- Tri-state buffer networks

**Concepts Explored:**
- Memory addressing schemes
- Chip select logic
- Bus arbitration fundamentals

**Files:** `askhsh1.circ`, `askhsh2.circ`, `askhsh3.circ`, `askhsh4.circ`, `askhsh5.circ`

---

### Exercise 7: Advanced Sequential Systems
**Components Designed:**
- Programmable counters with parallel load
- Sequence generators (pseudo-random, custom patterns)
- Multi-mode registers (load, shift, hold)
- Synchronizer circuits for clock domain crossing

**Advanced Topics:**
- Metastability prevention
- Hazard-free state machine design
- Timing constraint analysis

**Files:** `A1_a.circ`, `A1_b.circ`, `Α2.circ`

---

### Final Project: Complete Processor Datapath
**Comprehensive Design:**
- **Instruction Set Architecture**: Custom 8-bit processor
- **Datapath Components**:
  - Register file (8 registers × 8 bits)
  - ALU with full arithmetic/logic operations
  - Program counter (PC) with increment/branch logic
  - Instruction decoder and control unit
- **Memory Subsystem**:
  - Instruction memory (ROM)
  - Data memory (RAM)
  - Address multiplexing
- **Control Logic**:
  - Fetch-decode-execute cycle
  - Microcode controller
  - Pipeline hazard handling (basic)

**Processor Features:**
- Load/Store architecture
- Conditional branching (BEQ, BNE)
- Arithmetic operations (ADD, SUB, AND, OR)
- Immediate operand support
- I/O port mapping

**File:** `KATSAROS_ANDREAS_AM1084522.circ`

---

## Technical Implementation
**Design Tool:** Logisim Evolution 3.4.2+


---
## Institution

**University of Patras**  
**Department of Electrical and Computer Engineering**  
**Student ID:** 1084522  
**Course:** Advanced Logic Design  
**Tool:** Logisim Evolution 3.4.2

---

*Demonstrating digital design and processor architecture expertise for hardware engineering and FPGA development positions.*
