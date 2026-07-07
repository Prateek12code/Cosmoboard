# Cosmoboard

Cosmoboard is a custom 75% mechanical keyboard project with an open-top design, MX hot-swap support, custom PCB, 3D printed case, and 3D printed switch plate.

The goal of Cosmoboard V1 is simple: build a working custom keyboard from scratch while learning real PCB design, keyboard matrices, routing, stabilizers, manufacturing, and case design.

Type your ideas into orbit, one key at a time.

## Why I Made This

I wanted to design and build my own keyboard instead of only using prebuilt ones. Cosmoboard started as a way to learn how custom keyboards are actually made, from the PCB and matrix to the case, plate, switches, stabilizers, and final assembly.

The first version had a more expensive FR4 plate plan, but I changed it to a 3D printed plate and case to reduce cost and make the project easier to prototype.

V1 is focused on making a keyboard that works, looks clean, and teaches me enough to build a better version later.

## Features

- 75% custom keyboard layout
- MX-style mechanical switches
- MX hot-swap sockets
- 1N4148W SOD-123 diodes
- PCB-mount stabilizers
- Addressable RGB LEDs
- Custom PCB
- 3D printed switch plate
- 3D printed case
- Open-top / floating-switch style
- Split case design for easier 3D printing

## Hardware Overview

| Part | Details |
|---|---|
| PCB | Custom Cosmoboard PCB ordered from JLCPCB |
| Switches | HMX Macchiato Linear Switches |
| Sockets | Kailh MX hot-swap sockets |
| Diodes | 1N4148W SOD-123 diodes |
| Keycaps | Cherry Colour PBT Keycap Set |
| Stabilizers | Glorious GOAT PCB-mount stabilizers |
| RGB | Worldsemi WS2812B 5050 addressable RGB LEDs |
| Plate | 3D printed plate |
| Case | 3D printed case |
| Filament | Numakers PLA+ Clear Transparent |

## PCB Details

| Item | Value |
|---|---|
| PCB name | Cosmoboard-PCB_Y12 |
| PCB size | Around 361.6 mm wide |
| PCB thickness | 1.6 mm |
| PCB color | Black |
| Mounting | PCB screw holes |
| Switch type | MX-style |
| Socket type | Kailh MX hot-swap |
| Plate type | 3D printed plate |
| Case type | 3D printed split case |

## Case Design

The keyboard is larger than a normal Bambu Lab A1 build plate, so the case is designed to be split into printable parts.

The case plan includes:

- Split 3D printed frame
- 3D printed switch plate
- Internal support ribs to reduce flex
- Screw mounting through the PCB
- USB cutout
- Open-top look

The FR4 plate was removed from the project plan to reduce cost. A 3D printed plate is now used instead.

## Bill of Materials

The updated BOM is available in:

```text
production/BOM.csv
