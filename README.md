# Automated Can Crusher | SolidWorks & Electropneumatic Automation

**Individual Mechatronics Engineering Project | German International University | 2025**

## Project Overview

This project focuses on the mechanical design and electropneumatic control of an automated can-crushing machine.

The system was designed in SolidWorks and uses three pneumatic cylinders to perform a sequential crushing operation. Capacitive proximity sensors provide position and object-detection signals for the control system.

The project combines mechanical design, pneumatic actuation, sensor integration, electrical control circuits, and manufacturing considerations.

## Final SolidWorks Assembly

![Can Crusher Assembly](image%20whole%20assembly.jpg)

*SolidWorks assembly showing the machine enclosure, pneumatic mechanisms, and removable collection compartment.*

## System Architecture

The proposed system consists of:

- **Three pneumatic cylinders:** Two provide linear motion, while the third drives a mechanism converting linear motion into rotational motion.
- **Seven capacitive proximity sensors:** Six detect cylinder extension and retraction positions, and one detects the presence of a can.
- **Can magazine:** Guides the workpiece into the mechanism.
- **Crushing mechanism:** Uses coordinated pneumatic actuation.
- **Enclosed frame:** Supports the mechanical components and transparent protective panels.
- **Collection compartment:** Provides a removable container for processed cans.
- **Electrical control system:** Coordinates the actuation sequence using sensor feedback and electropneumatic control circuits.

## Pneumatic Control Sequence

The designed actuation sequence is:

**A+ → B+ → C+ → A− → B− → C−**

Here:

- `A+`, `B+`, and `C+` represent cylinder extension.
- `A−`, `B−`, and `C−` represent cylinder retraction.

The sequence is documented using a pneumatic step diagram and electropneumatic circuit schematics.

## Engineering Work

### Mechanical Design
- Developed the machine's 3D mechanical assembly using SolidWorks.
- Designed the structural frame, cylinder arrangement, can magazine, and collection compartment.
- Documented mechanical components and assembly drawings.

### Pneumatic Automation
- Developed a sequential actuation concept using three pneumatic cylinders.
- Integrated sensor positions into the control design.
- Documented the electropneumatic circuit and its operating sequence.

### Electrical Control
- Prepared electrical circuit and wiring diagrams.
- Documented sensor and actuator connections.
- Included control-panel and electrical layout drawings.

### Manufacturing and Assembly
- Considered Design for Manufacturing (DFM) and Design for Assembly (DFA).
- Examined casting geometry, component accessibility, standardized fasteners, and modular assembly.
- Documented manufacturing and assembly considerations for the proposed machine.

## Engineering Tools and Topics

- SolidWorks
- Electropneumatic circuit design
- Pneumatic actuators
- Capacitive proximity sensors
- Electrical schematics
- Sequential control
- Design for Manufacturing (DFM)
- Design for Assembly (DFA)

## Project Documentation

The repository includes:

- `report mecha.docx` — Full university project report, including CAD illustrations, component information, pneumatic sequence diagrams, and electrical schematics.
- `dfa.pdf` — Additional manufacturing and assembly documentation.
- `image whole assembly.jpg` — Final SolidWorks assembly screenshot.

## Project Status

This repository documents the mechanical and electropneumatic design work.

The original editable SolidWorks assembly and part files are currently unavailable. The assembly screenshot and project report are retained as design evidence.

Physical fabrication and operational testing are not verified by the available documentation.

## Author

**Ahmed Waseim Azzam**

B.Sc. Mechatronics Engineering — German International University

M.Sc. Engineering Cybernetics — University of Stuttgart

[GitHub Profile](https://github.com/AhmedWaseim)
