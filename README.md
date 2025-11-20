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

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/38249fde-ed88-49a6-8034-e9fffbcbf164" />

<img width="515" height="663" alt="image" src="https://github.com/user-attachments/assets/d428dd29-b44f-4d1b-8955-92b5420093f3" />

### Schematicand Symbol of 2-Input EX-OR Gate:

<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/17ba9083-6b36-450a-85bc-770a711d2b3a" />

<img width="867" height="687" alt="image" src="https://github.com/user-attachments/assets/b31f7863-4d24-472b-843b-3b00e43807a8" />

### Schematicand Symbol of Half Adder:
![Screenshot 2025-05-10 160535](https://github.com/user-attachments/assets/5d98f983-d6b7-42b9-8f16-17407b2010b2)

![Screenshot 2025-05-10 161100](https://github.com/user-attachments/assets/bfaa7af0-6785-46e4-b434-87d677af5807)

### Schematic of 2-Bit Multiplier:
<img width="991" height="552" alt="image" src="https://github.com/user-attachments/assets/67662184-99d6-48fc-b52e-8bce2a15c43a" />


## Output
### Transient Analysis Output:
<img width="995" height="548" alt="image" src="https://github.com/user-attachments/assets/a1f67267-27c8-480e-9cbc-9253413f6a2a" />

![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)

Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
