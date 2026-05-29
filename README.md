# LM317 Voltage Regulator — PCB Design Project

## Overview
Fabrication ready 2-layer PCB. Adjustable voltage regulator built 
around the LM317 TO-220. Designed end-to-end in KiCad: schematic 
capture, component selection, layout, routing, and full fabrication 
outputs including Gerbers and BOM.

## Components
| Reference | Component | Value | Package |
|-----------|-----------|-------|---------|
| U1 | LM317 Voltage Regulator | — | TO-220 |
| C1 | Electrolytic Capacitor | 1000µF | Radial THT |
| C2 | Electrolytic Capacitor | 200µF | Radial THT |
| R1 | Resistor | 250Ω | Axial THT |
| R2 | Resistor | 2.5kΩ | Axial THT |
| R3 | Resistor | 100Ω | Axial THT |
| J1 | 2-Pin Connector (Output) | — | PinHeader 2.54mm |
| J2 | 2-Pin Connector (Input) | — | PinHeader 2.54mm |

## Repo Structure
```
lm317-voltage-regulator/
├── kicad/          # Schematic and PCB layout files
├── gerbers/        # Gerber and drill files
├── bom/            # Bill of Materials (CSV)
└── docs/           # Schematic PDF and PCB layout PDFs
```

## Tools
- **KiCad** — Schematic, layout, DRC, Gerber export
