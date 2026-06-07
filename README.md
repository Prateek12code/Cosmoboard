# Cosmoboard

**Cosmoboard** is a custom 75% mechanical keyboard designed with a floating-switch, open-top style and a cosmic-themed PCB/plate design.

The goal of this project was to build a clean, practical, and good-looking custom keyboard from scratch while learning real PCB design, routing, keyboard matrices, plate design, and fabrication preparation.

> Type your ideas into orbit, one key at a time.

---

## Overview

Cosmoboard is a wired custom mechanical keyboard built around a Pico-compatible RP2350A controller module.  
It uses normal MX switches, MX hot-swap sockets, an FR4 plate, plate-mount stabilizers, one rotary encoder, and bottom RGB underglow.

The design uses an open-top / floating-switch style instead of a full enclosed case. The keyboard is supported by a bottom tray/base, while the switches and plate remain visually exposed.

---

## Features

- 75% keyboard layout
- MX mechanical switches
- MX hot-swap sockets
- FR4 switch plate
- Plate-mount stabilizers
- One rotary encoder
- 16 bottom RGB underglow LEDs
- WeAct Studio RP2350A_V20 controller module
- USB-C through the controller module
- 6 × 15 keyboard matrix
- Rounded PCB outline
- 9 mounting holes
- Custom silkscreen art
- Open-top floating-switch design
- Bottom tray/base case concept

---

## Hardware

| Part | Description |
|---|---|
| Controller | WeAct Studio RP2350A_V20 |
| Switches | MX-style mechanical switches |
| Sockets | MX hot-swap sockets |
| Plate | 1.6 mm FR4 plate |
| Stabilizers | Plate-mount stabilizers |
| RGB | 16 addressable RGB LEDs |
| Encoder | EC11-style rotary encoder |
| Connection | USB-C |
| Case | Bottom tray / open-top style |

---

## PCB Details

| Item | Value |
|---|---|
| PCB size | Around 354 mm × 134 mm |
| Matrix | 6 rows × 15 columns |
| Plate thickness | 1.6 mm FR4 |
| Main PCB thickness | 1.6 mm FR4 |
| Mounting holes | 9 |
| Layout style | 75% |
| Case style | Floating switch / bottom tray |

---

## Design Direction

Cosmoboard originally started as a more complex bare-microcontroller PCB.  
That version used a bare STM32 chip with USB-C, regulator, boot/reset circuits, and other support components.

After reaching the routing stage, I realized that for a first keyboard PCB, the bare-chip approach had too many failure points. A small mistake in USB, power, boot, reset, or MCU routing could make the whole board fail.

So the project pivoted to a safer and more realistic V1:

- Use a ready-made controller module
- Keep USB-C built in
- Focus on keyboard layout, routing, plate, case, and firmware
- Reduce the chance of hardware failure
- Actually finish a working keyboard

This made the project much more achievable while still keeping the design custom and interesting.

---

## PCB and Plate

The main PCB contains:

- Key matrix routing
- Hot-swap socket footprints
- Diodes
- Rotary encoder routing
- RGB underglow routing
- Controller module footprint
- Mounting holes
- Rounded Edge.Cuts outline
- Silkscreen branding and art

The FR4 plate contains:

- MX switch cutouts
- Plate-mount stabilizer cutouts
- Rotary encoder cutout
- Matching mounting holes
- Custom silkscreen art

---

## Current Status

- [x] Layout finalized
- [x] Schematic completed
- [x] Footprints assigned
- [x] PCB routed
- [x] Encoder routed
- [x] RGB routed
- [x] Edge.Cuts completed
- [x] Mounting holes added
- [x] FR4 plate completed
- [x] Silkscreen art added
- [x] DRC checked
- [x] Gerbers exported
- [ ] PCB ordered
- [ ] Components soldered
- [ ] Firmware written
- [ ] Case/base designed
- [ ] Final build assembled

---

## Community Help

A big thanks to the **Keyboard Atelier Discord** community.

Their feedback helped a lot with:

- Choosing between MX and low-profile switches
- Understanding why hot-swap boards need a plate
- Choosing plate-mount stabilizers
- Improving routing
- Reducing unnecessary vias
- Understanding through-hole pads
- Fixing Edge.Cuts issues
- Creating the FR4 plate
- Preparing the design for fabrication

Their advice helped turn Cosmoboard from an idea into a real manufacturable keyboard design.

---

## Lessons Learned

This project taught me a lot about:

- Keyboard matrix design
- PCB routing
- KiCad workflow
- Footprint assignment
- DRC errors
- Edge.Cuts
- Hot-swap socket placement
- Stabilizer compatibility
- Plate design
- Silkscreen art
- Manufacturing preparation

The hardest part was routing the keyboard matrix and cleaning up the PCB.  
The main PCB routing alone took around 7–8 hours.

---

## Future Plans

Possible improvements for future versions:

- Cleaner routing
- Better controller placement
- Custom bottom tray/base
- More refined RGB placement
- Improved silkscreen design
- A lower-profile version
- Optional display or macro cluster
- Full custom firmware support

---

## Gallery
```text
/images/pcb.png
/images/plate.png
/images/3d-view.png
