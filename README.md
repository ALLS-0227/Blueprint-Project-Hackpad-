# SimpleKeypad

Designing a mini keyboard as a first hardware project, which will allow you to communicate in morse code with just 4 keys.

# Repository
Board layout of the PCB and the schematic.

STL/STP/f3z files of the assembly, lid, case and imported models.

Firmware based on the kmk tool.

# Bill of materials (BOM)
1x Seeed XIAO RP2040

4x Cherry MX-Style switches

4x Blank DSA keycaps

4x M3x5mx4mm heatset inserts

4x M3x20mm screws

1x Case (2 printed parts)

# CAD Model

Consists of 2 separate printed pieces. The bottom part, where the PCB sits, and the top cover, which allows the keys to be placed.
<img width="1918" height="1021" alt="Simple Keypad " src="https://github.com/user-attachments/assets/87e589d9-0b04-42f7-9151-5c35b3752b38" />
Made in Fusion360 by Ángel Leonardo LS

# PCB
The following pictures show the schematic and board layout of the PCB, made in KiCad.
<img width="1500" height="857" alt="image" src="https://github.com/user-attachments/assets/112d6a54-7485-475e-88b3-5af96f434b08" />
Schematic
<img width="1919" height="953" alt="image" src="https://github.com/user-attachments/assets/3958d51f-1349-4f8c-9416-275c2fcc0247" />
Layout

# Firmware
This keypad uses [kmk](https://github.com/KMKfw/kmk_firmware) for assigning each key a Morse macro.

Key 1# (.)

Key 2# (-)

Key 3# (.-)

Key 4# (..)

# Extra
You can write each letter of the alphabet with maximum 3 keystrokes.
