# BKF Unibody Split

A unibody split keyboard running QMK/VIAL firmware on the Waveshare RP2040-Zero.

## Features
- 4 rows × 12 columns
- COL2ROW diode orientation
- 3 independent layout options configurable in VIAL:
  - Top right: 2× 1u or 1× 2u Backspace
  - Left spacebar: 2u, 2.25u, 2.75u, or 1.75u
  - Right spacebar: 2u, 2.25u, 2.75u, or 1.75u

## Build
    qmk compile -kb drhigsby/bkf_us -km default
    qmk compile -kb drhigsby/bkf_us -km vial -c

## Flash
Put the RP2040-Zero into bootloader mode (hold BOOT, tap RESET, release BOOT).
A USB drive will appear. Copy the compiled .uf2 file to it:

    D:\vial-qmk\drhigsby_bkf_us_vial.uf2

## Wipe EEPROM
Hold the bootmagic key (top-left, matrix 0,0) while plugging in USB.

## Maintainer
drhigsby