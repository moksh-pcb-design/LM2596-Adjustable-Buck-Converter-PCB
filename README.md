# LM2596 Adjustable Buck Converter PCB Design

![PCB Layout](FINAL_VIEW.png)

A 2-layer LM2596-based adjustable DC-DC buck converter PCB designed in Altium Designer 25.1. The project includes custom schematic symbols, custom PCB footprints, ERC/DRC verification, BOM generation, and manufacturing-ready outputs.

---

## Project Overview

This project implements an adjustable DC-DC buck converter using the LM2596 switching regulator IC.

The objective was to design a compact, manufacturable, and electrically verified PCB capable of efficiently stepping down a higher DC input voltage to a regulated lower output voltage.

The schematic was developed by studying the LM2596 datasheet and reference application circuit, followed by complete PCB implementation, verification, and manufacturing preparation in Altium Designer.

---

## Project Specifications

| Parameter             | Value                 |
| --------------------- | --------------------- |
| PCB Layers            | 2                     |
| PCB Design Software   | Altium Designer 25.1  |
| Regulator IC          | LM2596 Adjustable     |
| Inductor              | 47 µH                 |
| Diode                 | SS54 Schottky         |
| Ground Plane          | Bottom Layer GND Pour |
| Verification          | ERC & DRC Passed      |
| Manufacturing Outputs | Generated             |
| Custom Libraries      | Yes                   |
| 3D Verification       | Completed             |

---

## Key Features

* LM2596 Adjustable Switching Regulator
* Adjustable Output Voltage
* 2-Layer PCB Design
* Custom Schematic Symbols
* Custom PCB Footprints
* Wide High-Current Power Traces
* Bottom Layer Ground Pour
* ERC Verification
* DRC Verification
* BOM Generation
* Gerber Generation
* Manufacturing-Ready Outputs
* 3D PCB Verification

---

## Project Images

### Schematic

![Schematic](SCHEMATIC.png)

---

### Final PCB Layout

![PCB Layout](FINAL_VIEW.png)

---

### Top Layer

![Top Layer](TOP_VIEW.png)

---

### Bottom Layer

![Bottom Layer](BOTTOM_VIEW.png)

---

### 3D Top View

![3D Top View](3D_TOP.png)

---

### 3D Bottom View

![3D Bottom View](3D_BOTTOM.png)

---

## Main Components

| Designator | Component                        |
| ---------- | -------------------------------- |
| U1         | LM2596 Adjustable Buck Regulator |
| D1         | SS54 Schottky Diode              |
| L1         | 47 µH Inductor                   |
| RV1        | 10 kΩ Potentiometer              |
| C1         | 100 µF Input Capacitor           |
| C2         | 220 µF Output Capacitor          |
| C3, C5     | 100 nF Ceramic Capacitors        |
| C4, C6     | 1 µF Ceramic Capacitors          |
| J1         | Input Terminal Block             |
| J2         | Output Terminal Block            |

---

## Working Principle

The LM2596 operates as a switching regulator.

1. Input DC power enters through the input terminal.
2. Input capacitors suppress ripple and supply noise.
3. The LM2596 switches the input voltage at high frequency.
4. The inductor stores and transfers energy.
5. The Schottky diode provides the freewheeling current path.
6. Output capacitors smooth the output voltage.
7. The feedback network maintains output voltage regulation.

Compared to linear regulators, this switching topology offers significantly higher efficiency and reduced power dissipation.

---

## PCB Design Highlights

### Component Placement Strategy

Components were arranged according to power flow:

**Input Connector → Input Filter → LM2596 → Inductor & Diode → Output Filter → Output Connector**

### Routing Considerations

* Wide traces used for high-current paths
* Reduced voltage drop
* Improved current carrying capability
* Short power-routing paths
* Logical component grouping

### Grounding Strategy

* Bottom-layer GND copper pour
* Reduced ground impedance
* Improved return current paths
* Better PCB manufacturability

---

## Design Verification

### Electrical Rule Check (ERC)

* ERC Completed Successfully
* No critical schematic connectivity issues detected

### Design Rule Check (DRC)

Final DRC Status:

* Clearance Violations = 0
* Width Violations = 0
* Unrouted Nets = 0
* Total DRC Errors = 0

The PCB successfully passed all verification checks before manufacturing output generation.

---

## Manufacturing Outputs

The repository includes:

* Gerber Files
* NC Drill Files
* Bill of Materials (BOM)
* ERC Report
* DRC Report
* PCB Source Files
* Custom Libraries

---

## Repository Contents

### Design Files

* PCB Layout (.PcbDoc)
* Schematic (.SchDoc)
* Project File (.PrjPcb)

### Libraries

* Custom Schematic Library (.SchLib)
* Custom PCB Library (.PcbLib)

### Reports

* ERC Report
* DRC Report

### Manufacturing Files

* Gerber Outputs
* Drill Files

### Documentation

* BOM
* PCB Layout Images
* 3D PCB Views

---

## Skills Demonstrated

* PCB Design
* Altium Designer 25.1
* Power Electronics PCB Layout
* Custom Symbol Creation
* Custom Footprint Creation
* Datasheet Interpretation
* High-Current Routing
* Ground Plane Design
* ERC Verification
* DRC Verification
* BOM Generation
* Gerber Generation
* Manufacturing Documentation

---

## Software Used

* Altium Designer 25.1

---

## Author

**Moksh Prajapati**

Electronics Engineering Student
PCB Design Engineer Aspirant

GitHub: https://github.com/moksh-pcb-design
