# Zigbee Retrofit

### Purpose
This project provide a PCB that will retrofit into an M5Stack Zigbee Unit but replaces the CC2630 with the more common and better supported CC2531 chipset.

Designed in KiCad 6.0.9
The output board measures 50mm x 20mm (I hope)

The design incorporates a Tag-Connect 10 pad pogo pin (TC-2050-NL) footprint to write firmware.
The design also incorporates a 4-pin Grove connector with UART interface for easy connection with M5Stack Atom products.

The design also uses the following symbols:
- 110990030: Seed Studio Grove connector
- CC2531F256RHAT: TI Chip Zigbee chip
- TC2050-IDC-NL: 10 pin flash connection
- U.FL-R-SMT-1_10: UFL antenna connector
- ECS-320-13-42-CKM-TR: 32 Mhz Crystal
- ECS-.327-12.5-34RR-TR: 32.768 kHz Crystal

