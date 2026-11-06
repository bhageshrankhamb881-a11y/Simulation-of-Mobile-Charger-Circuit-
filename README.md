# Simulation of Mobile Charger Circuit for Stable 5V Output Using Multisim

## 1. Project Overview

This project focuses on designing and simulating a mobile charger circuit that provides a stable 5V DC output using NI Multisim software.

Mobile phones require a regulated 5V DC supply for charging. Direct AC supply cannot be used because it has high voltage and fluctuations. Therefore, this project converts 230V AC into a stable 5V DC output using different electronic components.

## 2. Problem Statement

- Direct AC supply cannot be used for mobile charging.
- High voltage damages mobile batteries.
- Voltage fluctuations affect charging.
- A stable 5V DC output is required.

## 3. Project Objectives

- Design a mobile charger circuit.
- Study the transformer, rectifier, filter and regulator.
- Simulate the circuit using Multisim software.
- Verify the stable 5V DC output.

## 4. Block Diagram

The mobile charger circuit consists of the following stages:

230V AC → Transformer → Rectifier → Filter → Voltage Regulator → 5V DC Output

## 5. Components Used

| Sr. No. | Component | Specification |
|---|---|---|
| 1 | Transformer | 230V/12V |
| 2 | Diodes | 1N4007 (4) |
| 3 | Capacitor | 1000µF |
| 4 | Voltage Regulator IC | 7805 |
| 5 | Capacitor | 0.01µF |

## 6. Working Principle

### 6.1 Transformer

- Works on electromagnetic induction.
- Converts 230V AC into 12V AC.
- Provides electrical isolation and safety.

### 6.2 Rectifier

- Uses a bridge rectifier.
- Converts AC into pulsating DC.
- Provides unidirectional output.

### 6.3 Filter Circuit

- Uses a capacitor to smooth DC.
- Reduces ripple voltage.
- Provides smoother DC output.

### 6.4 Voltage Regulator (7805)

- Provides a fixed 5V DC output.
- Handles input and load variations.
- Provides thermal and short-circuit protection.

## 7. Pin Configuration of 7805

| Pin | Function |
|---|---|
| Pin 1 | Input |
| Pin 2 | Ground |
| Pin 3 | Output (5V) |

## 8. Simulation Software

**Software Used:** NI Multisim

Multisim is used for designing and simulating the mobile charger circuit.

Advantages:
- Safe virtual testing.
- Easy circuit analysis.
- Saves time and cost.
- Helps observe circuit output.

## 9. Simulation Procedure

1. Open Multisim software.
2. Select the required components.
3. Connect the circuit components.
4. Run the simulation.
5. Observe the output voltage.

## 10. Simulation Results

The simulation results show:

- Input DC approximately 16V.
- Output DC approximately 5V.
- Stable regulated output achieved.

## 11. Implementation and Results

- Circuit successfully simulated.
- Stable regulated output obtained.
- The project is educationally useful.
- Hardware implementation of the 5V mobile charger was also demonstrated.

## 12. Conclusion

The mobile charger circuit was successfully designed and simulated using Multisim software.

The circuit converts AC supply into regulated 5V DC output using a transformer, bridge rectifier, filter capacitor and 7805 voltage regulator IC.

The simulation demonstrates that a stable 5V output can be obtained for a mobile charger application.

## 13. Future Scope

- Smart mobile phone chargers.
- Fast charging technology.
- Higher charging efficiency.
- Improved charger protection systems.

## 14. Project Team

**Submitted By:**

1. Gaurav Giri
2. Shivam Thube
3. Bhagesh Rankhamb
4. Shreyash Sable
5. Vibhum Bhattad

**Roll Numbers:** 12, 36, 35, 38, 37

**Branch:** Chemical

**Subject:** IEEE

**Institute:** MIT Academy of Engineering, Alandi, Pune

**Submitted To:** Aniket Sir

---
