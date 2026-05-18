# tiddlywink
An angled, unibody QAZ-like 40% keyboard with 38 keys and two optional rotary encoder positions.

## Hardware
| Component | Qty | Notes |
|---|---|---|
| MX Switches | 38 | 5-pin highly recommended |
| Diodes | 38 | SOD-123 |
| Pro Micro or equivalent | 1 | ATmega32U4, USB-C recommended |
| Low Profile Binding Barrels | 5 | https://www.mcmaster.com/93121A330/ |
| RGB LEDs | 10 | Optional — WS2812B-B |
| Rotary Encoder | 1 | Optional — Alps EC11, two positions available |
| Reset Button | 1 | Optional — SMD SW_SPST_SKQG https://www.amazon.com/gp/product/B07JM32QQW/ |

* Keyboard Maintainer: [drhigsby](https://github.com/drhigsby)
* Hardware Supported: tiddlywink PCB (Pro Micro / ATmega32U4)
* Hardware Availability: make your own

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb drhigsby/tiddlywink -km default

To compile the VIAL keymap:

    qmk compile -kb drhigsby/tiddlywink -km vial -c

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
