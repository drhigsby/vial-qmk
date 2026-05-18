# warpstone

An 11u traditionally staggered monstrosity of a keyboard with multiple layout options.

* Keyboard Maintainer: [drhigsby](https://github.com/drhigsby)
* Hardware Supported: warpstone PCB (Pro Micro / ATmega32U4)
* Hardware Availability: [drhigsby/warpstone](https://github.com/drhigsby/warpstone)

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb drhigsby/warpstone -km default

To compile the VIAL keymap:

    qmk compile -kb drhigsby/warpstone -km vial -c

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Layout Options

* **Z Key** — 2.25u single or 1.25u Shift + 1u Z split
* **L Key** — 2.25u single or 1u L + 1.25u semicolon split
* **Right Shift** — 2.75u single or 1.75u Shift (with >,. as companion)
* **Spacebar** — four options: 1.75+1.75 split, 3u+3u split, 6u, or 7u
