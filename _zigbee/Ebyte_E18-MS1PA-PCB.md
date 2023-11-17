---
date_added: 2020-03-26
model: E18-MS1PA-PCB
vendor: Ebyte
title: CC2530 PA 2.4GHz 100mW Zigbee SMD Wireless Module
category: coordinator
supports: coordinator
image: /assets/images/devices/Ebyte_E18-MS1PA-PCB.jpg
zigbeeid: none
compatible: [tasmota,z2m,zha, z4d]
mlink: https://www.cdebyte.com/products/E18-MS1PA1-PCB
link: https://www.amazon.com/cdebyte-Wireless-Transceiver-E18-MS1PA1-PCB-Antenna/dp/B082M6W88K/
link2: https://www.amazon.de/dp/B07P8Z383W/
link3: https://www.aliexpress.com/item/4000537373705.html
link4: https://www.banggood.com/Ebyte-E18-MS1PA1-PCB-CC2530-RF-Module-2_4GHz-20dBm-PA-CC2592-SMD-PCB-Antenna-Mesh-Network-Transmitter-and-Receiver-for-ZigBee-p-1765563.html
---
This module consists of a TI CC2530 and a CC2592 power amplifier chip. With 20dbm transmit power its realistic indoor range is 10-12m.

![Back](/assets/images/devices/Ebyte_E18-MS1PA-PCB_back.webp)

PCB pins are 1.27mm and slightly harder to solder wires to.

To be able to use it as a coordinator you need to [flash](flashing_ccloader) the **CC2530_CC2592_xx** [Z-Stack-firmware](https://github.com/Koenkk/Z-Stack-firmware/).

## Flashing Instructions
Identify the required pins and follow flashing instructions:
- flash using [CCLoader](/flashing_ccloader.html) and NodeMCU/Wemos D1 mini (or similar ESP8266 board)
- flash using [Raspberry Pi](http://www.marrold.co.uk/2019/12/flashing-cc2530-cc2591-zigbee-module.html)
- flash using [CC Debugger](http://ptvo.info/how-to-select-and-flash-cc2530-144/) 

VCC pin tolerates 3.6V max. **DO NOT** connect to 5V.

![Pinout](/assets/images/devices/Ebyte_E18-MS1PA-PCB_pinout.webp)

![Wired to Dupont cables](/assets/images/devices/Ebyte_E18-MS1PA-PCB_wired.webp)

[User manual](https://www.cdebyte.com/pdf-down.aspx?id=1751).
