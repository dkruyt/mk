# phantagom/baragon

[Baragon](https://en.wikipedia.org/wiki/Baragon) is a fictional monster, or kaiju, which first appeared in Ishirō Honda's 1965 film Frankenstein vs. Baragon.

![phantagom/baragon](https://i.imgur.com/17RkGUP.jpeg)

A marco pad, 3x3 with rgb ring and rotary encoder, via compatible. Key's can be rotated, so marcopad is useable at different angles.

* Keyboard Maintainer: [Dennis Kruyt](https://github.com/dkruyt)
* Project page: [baragon](https://github.com/dkruyt/mk/baragon)
* Hardware Supported: *RP2040-Zero*

In this repo you can find the build pictures, 3d stl files and QMK code.

[![Watch the video](https://img.youtube.com/vi/1jc_xD3B5aU/default.jpg)](https://youtu.be/1jc_xD3B5aU)

Make example for this keyboard (after setting up your build environment):

    make phantagom/baragon:default

Flashing example for this keyboard:

    Copy the uf2 file to the rp2040 

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootluf2 mode  in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the top of the PCB
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
