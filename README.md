# Cosmoboard

**Cosmoboard** is a custom 75% mechanical keyboard with an open-top floating-switch design, custom PCB, MX hot-swap support, RGB lighting, and a 3D printed case and plate.

It is designed as a clean V1 keyboard build: simple enough to manufacture, but still custom enough to learn PCB design, keyboard matrices, routing, stabilizer placement, case design, and real hardware assembly.

> Type your ideas into orbit, one key at a time.

---

## Gallery

| PCB | Plate | 3D View |
|---|---|---|
| ![PCB](images/PCB.png) | ![Plate](images/Plate.png) | ![3D View](images/3D.png) |

---

## Why I Made This

I wanted to design and build my own keyboard from scratch instead of only using prebuilt keyboards.

Cosmoboard started as a learning project, but it slowly became a full custom keyboard design. Through this project, I worked on the keyboard layout, PCB routing, diode matrix, hot-swap sockets, stabilizer placement, case design, plate design, BOM planning, and manufacturing decisions.

The first plan used an FR4 plate, but I later changed it to a **3D printed plate** to reduce the total cost and make the project easier to prototype.

The goal of V1 is simple: make a keyboard that works, looks clean, and teaches me enough to build a better version later.

---

## Features

- Custom 75% keyboard layout
- MX-style mechanical switches
- MX hot-swap sockets
- 1N4148W SOD-123 diodes
- PCB-mount stabilizers
- WS2812B 5050 RGB LEDs
- Custom black PCB
- 3D printed switch plate
- 3D printed case
- Open-top floating-switch style
- Split case design for easier 3D printing
- Designed for real manufacturing and assembly

---

## Hardware Overview

| Part | Selected Item |
|---|---|
| PCB | Custom Cosmoboard PCB from JLCPCB |
| Switches | HMX Macchiato Linear Switches |
| Sockets | Kailh MX Hot-swap Sockets |
| Diodes | 1N4148W SOD-123 Diodes |
| Keycaps | Cherry Colour PBT Keycap Set |
| Stabilizers | Glorious GOAT PCB-mount Stabilizers |
| RGB | Worldsemi WS2812B 5050 LEDs |
| Plate | 3D Printed Plate |
| Case | 3D Printed Split Case |
| Filament | Numakers PLA+ Clear Transparent |

---

## PCB Details

| Item | Value |
|---|---|
| PCB Name | Cosmoboard-PCB_Y12 |
| PCB Width | Around 361.6 mm |
| PCB Thickness | 1.6 mm |
| PCB Color | Black |
| Switch Type | MX-style |
| Socket Type | Kailh MX Hot-swap |
| Diode Package | SOD-123 |
| Plate Type | 3D Printed |
| Case Type | Split 3D Printed Case |

---

## Case And Plate

The keyboard is wider than a normal Bambu Lab A1 build plate, so the case and plate are designed to be split into printable parts.

The case plan includes:

- Split 3D printed frame
- 3D printed switch plate
- Internal support ribs to reduce flex
- PCB screw mounting
- USB cutout
- Open-top floating-switch look

The FR4 plate was removed from the plan to reduce cost. The keyboard now uses a 3D printed plate and case.

---

## Bill Of Materials

The updated BOM is stored in:

```text
production/BOM.csv
