# gg69_iso_dach

*A 69 Key ISO Keyboard with a modern, simple Layout called: DACH*

* Keyboard Maintainer: [SeeQu](https://github.com/iSeeQu)
* Hardware Supported: *STM32F072*
* Hardware Availability: *@LongValleylABS*

## GG69-ISO-GER with DACH Layout

ENGLISH
A new, simple DACH layout for the GG69-ISO-GER Keyboard.

## Layer 1: Basic layout
- Standard DE-ISO QWERTZ layout.

## Layer 2: FN Layer (hold Windows key)
- 1 - F1, 2 - F2, ..., DEL - F13.

## Special function:
- Key G activates the bootloader when held down while connecting the cable.


DEUTSCH!
Neues, simples DACH-Layout für die GG69-ISO-GER Tastatur.

## Layer 1: Basislayout
- Standard DE-ISO QWERTZ Layout.

## Layer 2: FN Layer (Windows-Taste gedrückt halten)
- 1 - F1, 2 - F2, ..., DEL - F13.

## Sonderfunktionen GG69: (Windows-Taste gedrückt halten)
- doppleklick Taste G lädt Einstellungen: (GG69-ISO-GER-ERNi / GG69-ISO-GER-LiLi)
- RGB_Light_PCB_Front/Back
- HE_Sensor
- OLED_Display_Top
- ROT_Decoder,

## Sonderfunktionen GG PRO: (Windows-Taste gedrückt halten)
- doppleklick Taste G lädt Einstellungen: (GG-ISO-GER-BIGBEN with TPM)
- RGB_Light_PCB_Front/Back
- RGB_Light_Case_Front/Back/Bottom/SideL/SideR
- OLED_Display_Top
- OLED_Display_Case_Front/Back/Bottom/SideL/SideR
- HE_Sensor,
- VOL_Touchsense,
- SONIC_Fingerprint,
- QR_Scanner,

## Spezielle Funktion:
- Taste G aktiviert den Bootloader, wenn sie während des Anschlusses des Kabels gedrückt gehalten wird.


Make example for this keyboard (after setting up your build environment):

    make gg69_iso_ger:default

Flashing example for this keyboard:

    make gg69_iso_ger:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

## Enter the bootloader:

* **Physical reset button**: Briefly press the RESET button on the back of the PCB
* **Bootmagic reset**: Hold down the key G and plug in the keyboard
