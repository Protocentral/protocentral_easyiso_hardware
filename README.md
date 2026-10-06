ProtoCentral easyISO — Isolated Qwiic Adapter
==============================================

easyISO galvanically isolates a Qwiic / STEMMA QT I²C link — data and power — so a body-connected
sensor never shares a ground with a mains-powered computer.

* **I²C isolator:** TI ISO1640 (8-pin SOIC), bidirectional SDA/SCL, hot-swappable, up to 1.7 MHz
* **Isolated power:** MPS MIE1W0505BGLVH isolated DC-DC module, 3.3 V out (about 75 mA)
* **Connectors:** one Qwiic port and one 0.1" 4-pin header (SCL, SDA, VCC, GND) on each side
* **Pull-ups:** 10 kΩ on SDA and SCL, on both sides
* **Board:** 33 × 18.7 mm, 2-layer, 4 × M2 mounting holes

The voltage ratings above are the manufacturers' component ratings. easyISO is a development tool,
not a certified medical isolation barrier.

Repository contents
-------------------
* **/hardware** — KiCad project (`easyISO.kicad_pro`, `.kicad_sch`, `.kicad_pcb`) and the schematic
  PDF (`pc_easyiso_v1_schematic.pdf`)

Revisions
---------
| Revision | Date | Notes |
|---|---|---|
| v1 | 2026-08 | First release |

License Information
===================

Hardware
--------
**All hardware is released under the [CERN-OHL-P v2](https://ohwr.org/cern_ohl_p_v2.txt)** license.

This source describes Open Hardware and is licensed under the CERN-OHL-P v2.

You may redistribute and modify this documentation and make products using it under the terms of
the CERN-OHL-P v2 (https://cern.ch/cern-ohl). This documentation is distributed WITHOUT ANY EXPRESS
OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN-OHL-P v2 for applicable conditions.

Documentation
-------------
**All documentation is released under [Creative Commons Share-alike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/).**
