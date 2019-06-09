# K1FM Pico Balloon

*This is a work in progress which never flew (yet!). Everything seems to be working right, but there still might be errors.*

Active development of this board can be followed in the [Aries HAB mailing list](https://ovmrc.groups.io/g/AriesHAB).
The recommended software is the [Orion project](https://github.com/ve3wmb/OrionWspr/) by VE3WMB

Feel free to test these boards. You can purchase them here:

https://oshpark.com/shared_projects/b55LTlS2
https://oshpark.com/shared_projects/1jyIOWdR
https://oshpark.com/shared_projects/ud3vH8MF

Suggestions and technical advice are welcome!
73 de Alain K1FM

## Changelog:

**Version 1.0**
Initial, not functioning prototype.

**Version 1.1**
- Bugfixes

**Version 1.2**
- Added optional K1FM Pico Power board for battery charge management
- Added bottom hook for dipole antennas
- Replaced Si5351a quartz with TCXO (Q1)
- Added switches to power the Si5351a, GPS down (Q2 - Q3)
- Added temperature sensor (TMP-36)
- Added fixed V_BCK connection to 3.3V
- Added VDD measurement point (ADC0)

**Version 1.3**
- Switched to 4 Layers design
- Added Time Pulse feedback to external interrupt input (PD2)
- Added Clock Generator Feedback to T1 input (PD5)
- Added external SDA, SCL pins
- Added extra power pin for direct battery charging via Schottky diode
- Reorganized external pins, added standard ISCP header
- 4.7 voltage divider on ADC0
- Fixed Q2-Q3 Mosfet polarization
- Expanded gap between main board and "Remove Before Flight" section

