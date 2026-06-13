# LM2596 Adjustable Buck Converter PCB Design

A 2-layer LM2596-based adjustable DC-DC buck converter PCB designed in Altium Designer 25.1. The project includes custom schematic symbols, custom PCB footprints, ERC/DRC verification, BOM generation, and manufacturing-ready outputs.

---

## Project Overview

This project implements an adjustable DC-DC buck converter using the LM2596 switching regulator. The PCB is designed to efficiently step down a higher DC input voltage to a regulated lower output voltage while minimizing power loss and heat generation.

The design was developed from the LM2596 datasheet and application circuit, with the schematic recreated, verified, and implemented into a manufacturable PCB layout.

---

## Design Objectives

- Design a manufacturable 2-layer buck converter PCB
- Implement an LM2596 adjustable regulator circuit
- Create custom schematic symbols and PCB footprints
- Apply proper power-routing techniques
- Perform ERC and DRC verification
- Generate manufacturing-ready outputs
- Develop a portfolio-quality power electronics PCB project

---

## Key Features

- LM2596 Adjustable Switching Regulator
- 2-Layer PCB Design
- Adjustable Output Voltage
- Wide High-Current Power Traces
- Bottom Layer GND Copper Pour
- Custom Schematic Symbols
- Custom PCB Footprints
- ERC Verified
- DRC Verified
- BOM Generated
- Gerber Files Generated
- Manufacturing Ready Design
- 3D PCB Verification

---

## Main Components

| Designator | Component |
|------------|------------|
| U1 | LM2596 Adjustable Buck Regulator |
| D1 | SS54 Schottky Diode |
| L1 | 47 µH Inductor |
| RV1 | 10 kΩ Potentiometer |
| C1 | 100 µF Input Capacitor |
| C2 | 220 µF Output Capacitor |
| C3, C5 | 100 nF Ceramic Capacitors |
| C4, C6 | 1 µF Ceramic Capacitors |
| J1 | Input Terminal Block |
| J2 | Output Terminal Block |

---

## Working Principle

The LM2596 operates as a switching regulator.

1. DC input power enters through the input connector.
2. Input capacitors filter supply noise and ripple.
3. The LM2596 switches the input voltage at high frequency.
4. The inductor stores and transfers energy.
5. The SS54 Schottky diode provides the freewheeling current path.
6. Output capacitors smooth the output voltage.
7. The potentiometer adjusts the output voltage through the feedback network.

This switching topology provides significantly higher efficiency than traditional linear regulators.

---

## PCB Design Highlights

### Component Placement Strategy

Components were arranged according to power flow:

Input Connector → Input Filter → LM2596 → Inductor/Diode → Output Filter → Output Connector

### Routing Considerations

- Wide traces used for high-current paths
- Short power routing paths
- Logical functional grouping
- Reduced voltage drop
- Improved current carrying capability

### Grounding Strategy

- Bottom-layer GND copper pour
- Improved current return paths
- Reduced ground impedance
- Better manufacturability

---

## Design Verification

### ERC Status

- ERC Completed
- No critical schematic errors detected

### DRC Status

- Clearance Violations = 0
- Width Violations = 0
- Unrouted Nets = 0
- Final DRC Errors = 0

The PCB successfully passed design verification checks before manufacturing output generation.

---

## Manufacturing Outputs

The repository includes:

- Gerber Files
- NC Drill Files
- BOM
- ERC Report
- DRC Report
- PCB Source Files
- Custom Libraries

---

## Custom Libraries

Custom libraries were developed and verified during the project.

### Custom Schematic Library

- LM2596 Symbol
- Supporting Components

### Custom PCB Footprint Library

- LM2596 Package
- Passive Components
- Connectors
- Power Components

---

## Project Files

### Design Files

- Schematic Document (.SchDoc)
- PCB Layout (.PcbDoc)
- Project File (.PrjPcb)

### Libraries

- Schematic Library (.SchLib)
- PCB Library (.PcbLib)

### Reports

- ERC Report
- DRC Report

### Manufacturing Files

- Gerber Outputs
- Drill Files

---

## Skills Demonstrated

- PCB Design
- Power Electronics PCB Layout
- Altium Designer 25.1
- Custom Symbol Creation
- Custom Footprint Creation
- Datasheet Interpretation
- High-Current Routing
- Ground Plane Design
- ERC Verification
- DRC Verification
- BOM Generation
- Gerber Generation
- Manufacturing Documentation

---

## Software Used

- Altium Designer 25.1

---

## Author

**Moksh Prajapati**

Electronics Engineering Student  
PCB Design Engineer Aspirant

GitHub: https://github.com/moksh-pcb-design

---
