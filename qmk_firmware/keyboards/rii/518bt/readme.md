Rii 518BT (Custom USB PCB)
===

This project replaces the original Bluetooth-only PCB in the Rii 518BT with a custom-designed USB-compatible PCB based on an STM32 microcontroller.

![Rii 518BT](https://raw.githubusercontent.com/tim-eastwood/rii-518bt/main/images/rii-518bt-render.jpg) <!-- Replace with your actual image URL if available -->

A compact 68-key keyboard using a custom matrix and firmware designed for full USB support and QMK compatibility.

**Keyboard Maintainer:** [Tim Eastwood](https://github.com/tim-eastwood)  
**Hardware Supported:** Rii 518BT with custom USB/STM32 PCB  
**Hardware Availability:** Custom PCB design by Tim Eastwood

---

## Build Instructions

Make example for this keyboard (after setting up your build environment):

```
make rii/518bt:default
```

To flash the firmware (replace `dfu-util` or your method as needed):

```
make rii/518bt:default:flash
```

---

## Resources

- [QMK Build Environment Setup](https://docs.qmk.fm/#/getting_started_build_tools)
- [QMK Make Instructions](https://docs.qmk.fm/#/getting_started_make_guide)
- [Complete Newbs Guide](https://docs.qmk.fm/#/newbs)

---

This is an independent hardware project and is not affiliated with Rii or the original manufacturer.
