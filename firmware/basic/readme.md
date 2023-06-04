# mkh bully

* Keyboard Maintainer: [zhol0777](https://github.com/zhol0777)
* Hardware Supported: APM32F072
* Hardware Availability: [Coffee Break Keyboards](https://cbkbd.com/)

Make example for this keyboard (after setting up your build environment):

    qmk compile -kb zhol/bully -km default

Flashing example for this keyboard:

    qmk flash -kb zhol/bully -km default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

After flashing, you may see LIBUSB_ERROR_TIMEOUT; this is normal, simply tap the reset button once afterwards (or re-plug your PCB) and the keyboard should become operational again.

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Press the button on the back of the PCB for at least three seconds
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
