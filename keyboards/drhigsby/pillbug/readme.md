# Pillbug
A unibody ergo 40% keyboard with two rotary encoders.

## Hardware
| Component | Qty | Notes |
|---|---|---|
| MX Switches | 38 | 5-pin highly recommended |
| Diodes | 38 | SOD-123 |
| Pro Micro | 1 | ATmega32U4 |
| Rotary Encoder | 2 | Alps EC11 |
| Reset Button | 1 | Optional — SMD SW_SPST |

* Keyboard Maintainer: [drhigsby](https://github.com/drhigsby)
* Hardware Supported: Pillbug PCB (Pro Micro ATmega32U4)
* Hardware Availability: make your own

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb drhigsby/pillbug -km default

To compile the VIAL keymap:

    qmk compile -kb drhigsby/pillbug -km vial -c

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Matrix
| | C0 (F4) | C1 (F5) | C2 (F6) | C3 (F7) | C4 (B1) | C5 (D7) | C6 (C6) | C7 (D4) | C8 (D0) | C9 (D1) |
|---|---|---|---|---|---|---|---|---|---|---|
| R0 (D3) | 0,0 | 0,1 | 0,2 | 0,3 | 0,4 | 0,5 | 0,6 | 0,7 | 0,8 | 0,9 |
| R1 (D2) | 1,0 | 1,1 | 1,2 | 1,3 | 1,4 | 1,5 | 1,6 | 1,7 | 1,8 | 1,9 |
| R2 (B3) | 2,0 | 2,1 | 2,2 | 2,3 | 2,4 | 2,5 | 2,6 | 2,7 | 2,8 | 2,9 |
| R3 (E6) | — | — | 3,2 | 3,3 | 3,4 | 3,5 | 3,6 | 3,7 | 3,8* | 3,9* |

*3,8 and 3,9 are the encoder click switches for KNOB1 and KNOB2 respectively.

## Encoders
| Encoder | Click Matrix | Pin A | Pin B |
|---|---|---|---|
| KNOB1 (left) | 3,8 | B6 | B5 |
| KNOB2 (right) | 3,9 | B2 | B4 |
