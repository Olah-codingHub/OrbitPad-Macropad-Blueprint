# OrbitPad

### A custom-designed programmable macropad

OrbitPad is a personal electronics project focused on designing and developing a programmable macropad using a custom PCB and enclosure.

The project uses a Seeed XIAO RP2040 microcontroller, 16 mechanical switches and 16 addressable RGB LEDs.

<!-- Main project image -->
![OrbitPad](<images/OrbitPad's CAD V2 (Assembly).png>)

## Features

- 16 mechanical switches in a 4x4 layout
- 16 individually addressable NeoPixel LEDs
- Seeed XIAO RP2040 microcontroller
- Custom PCB designed in KiCad
- Custom enclosure designed in Fusion 360
- Programmable key inputs and RGB lighting (planned)

## Hardware

| Component | Quantity |
|---|---:|
| Mechanical switches | 16 |
| NeoPixel LEDs | 16 |
| Seeed XIAO RP2040 | 1 |
| 0.91" OLED Screen | 1 |

## Design Process

### 1. PCB Design

The PCB was designed using KiCad, with consideration for component placement, GPIO availability and circuit routing.

#### Schematics

![PCB Schematic](<images/PCBSchematic.png>)

The Microcontroler

![PCB Schematic](<images/PCB1.png>)

the LED

![PCB LED Schematic](<images/PCB2.png>)

The switch matrix

![PCB Switch Matrix Schematic](<images/PCB3.png>)

Connection for the OLED Screen

![PCB Oled Schematic](<images/PCB4.png>)

#### Circit Board routing

Front

![PCB Front](<images/PCB_Front.png>)

Back

![PCB Back](<images/PCB_Back.png>)



### 2. PCB 3D Model

The PCB was exported as a STEP file and imported into Fusion 360 to assist with enclosure development.

![PCB 3D Model](Images/pcb-3d.png)

### 3. Enclosure Design

A custom enclosure is being developed in Fusion 360 to house the PCB and its components.

![Enclosure Design](Images/enclosure.png)

