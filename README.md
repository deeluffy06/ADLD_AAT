# Analog & Digital Logic Design (ADLD) - AAT

This repository contains the Alternative Assessment Tasks (**AAT-1** and **AAT-2**) for the **Analog & Digital Logic Design (ADLD)** course.

---

## Student Details

| Field | Details |
| :--- | :--- |
| **Name** | **Deepak S R** |
| **USN** | **1BM24EC051** |
| **Course** | Analog & Digital Logic Design (ADLD) |

---

## Repository Structure

```plaintext
ADLD_AAT/
├── aat_1/
│   ├── code/                  # Verilog HDL source codes
│   │   ├── alu code.txt
│   │   ├── BARREL SHIFTER CODE.txt
│   │   ├── COMPARATOR CODE.txt
│   │   ├── DIVIDE BY N COUNTER CODE.txt
│   │   ├── JOHNSON COUNTER CODE.txt
│   │   ├── MEALY FSM CODE.txt
│   │   ├── MOORE FSM CODE.txt
│   │   ├── PARITY GENERATOR AND CHCEKER.txt
│   │   ├── RANDOM SEQ GENERATOR CODE.txt
│   │   ├── RING COUNTER.txt
│   │   ├── SHIFT REGISTER.txt
│   │   ├── SYNCHRONOUS AND ASYNCHRONOUS COUNTER CODE.txt
│   │   └── TIME MODULATOR CODE.txt
│   ├── report/                # AAT-1 documentation and report PDF
│   │   └── 1BM25EC400_A_Shiny_Deepa.pdf
│   └── simulation/            # Simulation waveforms and output screenshots
│       ├── 4 BIT BARREL SHIFTER.jpg
│       ├── 4 BIT COMPARATOR.jpg
│       ├── 4 bit Johnson counter.jpg
│       ├── 4 BIT PARITY GENERATOR AND CHECKER.jpg
│       ├── 4 BIT RING COUNTER.jpg
│       ├── 4 BIT SHIFT REGISTER.jpg
│       ├── ALU.jpg
│       ├── DIVIDE BY N COUNTER.jpg
│       ├── MEALY.jpg
│       ├── MOORE.jpg
│       ├── RANDOM SEQUENCE DETECTOR.jpg
│       ├── SYNCHRONOUS AND ASYNCHRONOUS.jpg
│       └── TIMER MODULE.jpg
│
└── aat_2/
    ├── comparator/            # 4-bit Comparator design & verification
    │   ├── comparator.v.txt       # Verilog module
    │   ├── comparator.tb.v.txt    # Testbench
    │   ├── comparator.jpg         # Simulation output
    │   └── comparatormp4.mp4      # Demo video
    ├── shift_reg/             # Shift Register design & verification
    │   ├── shift reg.v.txt        # Verilog module
    │   ├── shift reg.tb.v.txt     # Testbench
    │   ├── shift register.jpg     # Simulation output
    │   └── shift reg.mp4.mp4      # Demo video
    └── report/                # AAT-2 documentation and report PDF
        └── A_SHINYDEEPA ADLD-AAT 2.pdf
```

---

## Contents Overview

### AAT-1: Digital Logic Modules & FSM Implementations
Implementation and verification of core combinational and sequential digital circuits using Verilog HDL:
1. **ALU (Arithmetic Logic Unit)**: Basic arithmetic and logical operations.
2. **4-Bit Barrel Shifter**: Multi-bit data rotation and shifting.
3. **4-Bit Comparator**: Magnitude comparison ($A > B$, $A < B$, $A = B$).
4. **Counters**:
   - Divide-by-N Counter
   - 4-bit Ring Counter
   - 4-bit Johnson Counter
   - Synchronous and Asynchronous Counters
5. **Finite State Machines (FSM)**:
   - Mealy FSM
   - Moore FSM
   - Random Sequence Detector
6. **Registers & Logic**:
   - 4-Bit Shift Register
   - Parity Generator and Checker
   - Timer / Time Modulator Module

### AAT-2: Advanced Verilog Design & Simulation
Comprehensive design, testbench simulation, and video demonstrations for:
1. **4-Bit Magnitude Comparator**:
   - Source code (`comparator.v.txt`)
   - Testbench verification (`comparator.tb.v.txt`)
   - Waveform screenshot & video walkthrough
2. **Universal / 4-Bit Shift Register**:
   - Source code (`shift reg.v.txt`)
   - Testbench verification (`shift reg.tb.v.txt`)
   - Waveform screenshot & video walkthrough

---

## Tools Used

- **Hardware Description Language**: Verilog HDL
- **Simulation & Verification Tools**: ModelSim / QuestaSim / EDA Playground / Vivado
- **Waveform Viewer**: GTKWave / Simulator Waveform Viewer
