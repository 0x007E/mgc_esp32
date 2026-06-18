[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/mgc_esp32) ![Build](https://github.com/0x007e/mgc_esp32/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `MGC_module` - ESP32

The `ESP32` (`mgc_module`) is an adaptable board for the [MeGARCard](https://github.com/0x007e/mgc). The board offers the possibility to control the `MeGARCard` with an [ESP32](#additional-information). The board itself is connected to the `MeGARCard` within the pcb-to-pcb connectors (no soldering necessary). With the onboard dip-switches the boot setup and the port expander `twi` address can be modified. The board itself operates with `3V3` deliverd from the `MeGARCard`.

> To mount the board on the `MeGARCard` disconnect the power source (`USB-C` connector) or any other used source from the MeGARCard!

| Experience  | Level                                                                               |
|:------------|:-----------------------------------------------------------------------------------:|
| Soldering   | ![?%](https://progress-bar.xyz/60?progress_color=0000ff&suffix=%20Medium&width=120) |

# Downloads

| Type      | File                                                                                                                                                 | Description     |
|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------|
| Schematic | [pdf](https://github.com/0x007E/mgc_esp32/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30425/main/files)                   | Schematic files |
| Board     | [pdf](https://github.com/0x007E/mgc_esp32/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30425/main/files)                         | Board file      |
| Drill     | [pdf](https://github.com/0x007E/mgc_esp32/releases/latest/download/drill.pdf)                                                                              | Drill file      |
| BoM | [xlsx](https://github.com/0x007E/mgc_esp32/releases/latest/download/bom.xlsx) / [html](https://github.com/0x007E/mgc_esp32/releases/latest/download/bom.html)          | Bill of Material as Excel/interactive HTML |
| PCB    | [zip](https://github.com/0x007E/mgc_esp32/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/mgc_esp32/releases/latest/download/kicad.tar.gz)    | KiCAD/Gerber/BoM/Drill files       |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on both sides (Top, Bottom). The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard soldering system.

### Top Layer

![Top Layer](https://github.com/0x007E/mgc_esp32/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/mgc_esp32/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link               | Description              |
|:----------:|:------------------:|:-------------------------|
| ESP32  | [pdf](https://documentation.espressif.com/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf) | ESP32-WROOM-32UE Datasheet |

---
