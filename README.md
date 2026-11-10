# Elevator System Simulator

A Qt/C++ simulator for a 3-elevator, 7-floor system with an interactive GUI and console event logging. Built as a COMP3004 course project at Carleton University.

The simulator source is no longer available. This repository preserves the design documentation: use cases, UML diagrams, design decisions, and the requirements traceability matrix.

## What it does

- Simulates 3 elevators across 7 floors, dispatching the closest available elevator to each request
- Two control designs: centralized (an elevator control system dispatches requests) and distributed (each floor allocates elevators by availability and proximity)
- Validated against 7 scenarios covering normal operation and safety features: fire alarm, overload, power outage, door obstruction, and help-button 911 escalation

## Documentation

All design documentation is in the `Documentation/` folder:

- `Traceability Matrix.docx` — 18 requirements mapped to use cases, design elements, and test cases
- `COMP3004 Assignment 1(Use case).pdf` — use cases (including installing rails, car sling, cab, and doors) and software-safety analysis
- `Design Decisions.docx` — centralized vs distributed control design and the sequence diagram's success scenarios
- `UML Sequence diagram(containing the safety features and 2 success scenarios).png` — passenger flow, emergency stop, fire alarm, help button, door obstruction, overload, and power outage
- `UML CLASS DIAGRAM(centralized and distributed).drawio` — class diagram (open in diagrams.net)
- `Controller State Diagram.drawio` — controller state diagram (open in diagrams.net)
- `State Diagram for Elevator(centralized and distributed).drawio` — elevator state diagram (open in diagrams.net)
