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

![WhatsApp Image 2025-11-19 at 11 34 06_3c21818e](https://github.com/user-attachments/assets/134d2003-ab54-4df5-90bd-2041c0faa0e6)

![WhatsApp Image 2025-11-19 at 11 34 05_2e947e88](https://github.com/user-attachments/assets/402d2578-a9ee-4c07-bf4e-10812906a2c8)

### Schematicand Symbol of 2-Input EX-OR Gate:

![WhatsApp Image 2025-11-19 at 11 34 06_2bf515b1](https://github.com/user-attachments/assets/033749d5-c4d8-4716-b214-9a09122792a1)

![Screenshot 2025-05-10 160523](https://github.com/user-attachments/assets/4230854b-5f8e-43d0-9875-258b457660e3)

### Schematicand Symbol of Half Adder:
![Screenshot 2025-05-10 160535](https://github.com/user-attachments/assets/5d98f983-d6b7-42b9-8f16-17407b2010b2)

![Screenshot 2025-05-10 161100](https://github.com/user-attachments/assets/bfaa7af0-6785-46e4-b434-87d677af5807)

### Schematic of 2-Bit Multiplier:
![Screenshot 2025-05-10 162446](https://github.com/user-attachments/assets/5b4b78a1-5812-4789-85ec-60324c2b5968)

## Output
### Transient Analysis Output:
![Screenshot 2025-05-15 153033](https://github.com/user-attachments/assets/2c94f184-525c-49ba-8733-27c982f0dffa)

![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


![WhatsApp Image 2025-11-19 at 11 34 07_6ddc07ed](https://github.com/user-attachments/assets/edcd9bea-3611-4a14-98be-111734e60325)

Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
