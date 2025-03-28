# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram
![image](https://github.com/user-attachments/assets/dce1d820-c663-4ca2-96c5-bd9129a69770)


## Truth Table for 2-Bit Multiplier
| A1 | A0 | B1 | B0 | P3 | P2 | P1 | P0 |
|----|----|----|----|----|----|----|----|
|  0 |  0 |  0 |  0 |  0 |  0 |  0 |  0 |
|  0 |  0 |  0 |  1 |  0 |  0 |  0 |  0 |
|  0 |  0 |  1 |  0 |  0 |  0 |  0 |  0 |
|  0 |  1 |  0 |  1 |  0 |  0 |  0 |  1 |
|  0 |  1 |  1 |  0 |  0 |  0 |  1 |  0 |
|  1 |  0 |  0 |  1 |  0 |  0 |  1 |  0 |
|  1 |  0 |  1 |  0 |  0 |  1 |  0 |  0 |
|  1 |  1 |  1 |  1 |  1 |  0 |  0 |  1 |

## Schematic Diagram
### 1. Schematic of 2-Bit Multiplier:
*(Schematic image to be inserted here)*

## Output
### Transient Analysis Output:
*(Simulation waveforms to be inserted here)*

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
