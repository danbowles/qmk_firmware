# klorball35

A 35-key, diodeless split keyboard with a trackball!

* Keyboard Maintainer: [Dan Bowles](https://github.com/danbowles)
* Hardware Supported: [Helios OxCB](https://github.com/0xCB-dev/0xCB-Helios?tab=readme-ov-file)

The matrix pins are an initial scaffold and should be checked against the PCB before flashing.

Make example for this keyboard (after setting up your build environment):

    make danbowles/klorball35:default

Flashing example for this keyboard:

    make danbowles/klorball35:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information.

A build guide for this keyboard has not yet been written.

## Bootloader

Helios comes equipped with a bootloader that can be accessed via the reset button or a keycode in the layout.
