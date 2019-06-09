# K1FM Pico Balloon

This is a work in progress which never flew (yet!). There certainly are errors and/or parts subject to change.
Feel free to test it, boards are available here:

https://oshpark.com/shared_projects/b55LTlS2

https://oshpark.com/shared_projects/1jyIOWdR

Suggestions and technical advice are welcome!

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
