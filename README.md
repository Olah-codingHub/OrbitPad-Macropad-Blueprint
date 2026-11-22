# OrbitPad

### A custom-designed programmable macropad

OrbitPad is a personal electronics project to design and develop a
compact, programmable macropad. The project brings together PCB design,
electronic component integration and mechanical enclosure design.

The PCB has been designed in **KiCad** around a **Seeed XIAO RP2040**
microcontroller. The board is then imported into **Autodesk Fusion 360**
to guide the design of a custom enclosure.

> **Project status:** In development. The PCB design is complete;
> enclosure design is underway. Firmware has not yet been implemented.

```{=html}
<!-- Replace this with a clean Fusion 360 render when the enclosure is ready. -->
```
![OrbitPad project render](Images/orbitpad-hero.png)

------------------------------------------------------------------------

## Overview

OrbitPad is planned around a 4 × 4 key layout, with individually
addressable RGB lighting. Its aim is to provide a compact input device
while giving me practical experience of designing and integrating
electronic and mechanical hardware.

### Planned features

-   **16 mechanical switches** arranged in a 4 × 4 layout.
-   **16 addressable NeoPixel LEDs** for per-key lighting.
-   **Seeed XIAO RP2040** as the microcontroller.
-   **Custom-designed PCB** created in KiCad.
-   **Custom enclosure** being designed in Autodesk Fusion 360.
-   **Programmable inputs and LED behaviour**, to be implemented during
    firmware development.

## Hardware

  Component                     Quantity Purpose
  --------------------------- ---------- ------------------
  Mechanical switches                 16 Key inputs
  Addressable NeoPixel LEDs           16 Per-key lighting
  Seeed XIAO RP2040                    1 Microcontroller

*Add exact switch and LED part numbers once the final component choices
are confirmed.*

## Design and development

### 1. PCB design

The PCB was designed in KiCad to arrange the 16 switches, LEDs and
microcontroller on a single board. Component placement and routing had
to account for the available microcontroller GPIO pins and the
connections required by the inputs and lighting.

![OrbitPad PCB layout](Images/orbitpad-pcb-layout.png)

### 2. 3D PCB model

The KiCad design was exported as a STEP model so it could be used as a
reference when designing the enclosure in Fusion 360. This makes it
possible to work around the board's dimensions and the positions of the
mounted components.

![OrbitPad PCB 3D model](Images/orbitpad-pcb-3d.png)

### 3. Enclosure design

The PCB STEP model was imported into Fusion 360. The enclosure is being
designed around the board, with consideration for the switch positions,
microcontroller and physical access to the device.

![OrbitPad enclosure CAD model](Images/orbitpad-enclosure.png)

### 4. Firmware

Firmware development is a future stage of the project. It will be
responsible for reading key presses and controlling the addressable
LEDs. The firmware and its functionality will be documented here once
implemented and tested.

## Repository structure

``` text
OrbitPad/
├── Hardware/
│   ├── PCB/
│   └── Enclosure/
├── Firmware/
├── Images/
└── README.md
```

The folder names above are a suggested layout. Adjust them to match the
actual files in this repository.

## Current progress

  -----------------------------------------------------------------------
  Stage                               Status
  ----------------------------------- -----------------------------------
  PCB design in KiCad                 Complete

  PCB STEP export and Fusion 360      Completed; export issue being
  import                              investigated

  Enclosure design in Fusion 360      In progress

  Firmware development                Not started

  Hardware assembly and testing       Not yet completed
  -----------------------------------------------------------------------

## Next steps

-   Finalise the enclosure design.
-   Resolve the PCB STEP export/import issue and verify the model in
    Fusion 360.
-   Implement firmware for key input and LED control.
-   Assemble the macropad and test its functionality.
-   Add photographs and test results to this documentation.

------------------------------------------------------------------------

*OrbitPad --- personal electronics and hardware design project.*
