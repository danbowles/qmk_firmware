# klorball35

A 35-key split keyboard scaffold for QMK.

* Keyboard Maintainer: [Dan Bowles](https://github.com/dan.be)
* Hardware Supported: klorball35 PCBs with Elite-C or Pro-Micro-compatible controllers
* Hardware Availability: TBD

The matrix pins are an initial scaffold and should be checked against the PCB before flashing.

Make example for this keyboard (after setting up your build environment):

    make danbowles/klorball35:default

Flashing example for this keyboard:

    make danbowles/klorball35:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information.

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix and plug in the keyboard
* **Physical reset button**: Briefly press the reset button on the controller
* **Keycode in layout**: Press the key mapped to `QK_BOOT`
