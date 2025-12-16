# PMP5114 – Power Supply Design (Altium)

## Overview
Multi-rail power supply design study (flyback + DC/DC buck stages).
Shared as view-only documentation (schematics/PCB screenshots/BOM).

## Key components
- UCC28610 – flyback PWM controller
- TL431 – precision feedback reference
- H11A817 – optocoupler (isolation)
- TPS54326 – DC/DC buck converters

## Files
- `docs/schematic.pdf` – schematic export (if available)
- `docs/PCB.png` – PCB view screenshot
- `docs/3D.png` – bill of materials

## Status
Prototype / design study. Not fully validated in hardware.

## What I learned
- power architecture & component selection
- isolated feedback (opto + TL431)
- multi-rail distribution
