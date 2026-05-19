# Little Knight
A unibody ergo 40% keyboard with a central rotary encoder and independent left/right bottom row layout options.

## Hardware
| Component | Qty | Notes |
|---|---|---|
| MX Switches | 37 | 5-pin highly recommended |
| Diodes | 37 | SOD-123 |
| ATmega32U2-AU | 1 | TQFP-32 |
| Rotary Encoder | 1 | Alps EC11 |
| USB-C Receptacle | 1 | USB 2.0 |
| Reset Button | 1 | Optional — SMD SW_SPST |

* Keyboard Maintainer: [drhigsby](https://github.com/drhigsby)
* Hardware Supported: Little Knight PCB (ATmega32U2-AU)
* Hardware Availability: make your own

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb drhigsby/little_knight -km default

To compile the VIAL keymap:

    qmk compile -kb drhigsby/little_knight -km vial -c

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Layout Options

* **Left Bottom Row** — four options: 1.25/1.25/1.5, 1/1.25/1.75, 1/1/2, 1/3
* **Right Bottom Row** — four options: 1.5/1.25/1.25, 1.75/1.25/1, 2/1/1, 3/1
* **Center Encoder** — clickable encoder with per-layer programmable CCW/CW actions via VIAL
