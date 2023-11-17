---
date_added: 2020-03-26
model: E18-MS1-PCB
vendor: Ebyte
title: CC2530 2.4GHz Zigbee SMD Wireless Module
category: coordinator
supports: coordinator, router
image: /assets/images/devices/Ebyte_E18-MS1-PCB.jpg
zigbeeid: none
compatible: [tasmota,z2m,zha,z4d]
mlink: http://ebyte.com/en/product-view-news.aspx?id=122
link: https://www.amazon.com/Wireless-E18-MS1-PCB-Antenna-Transmitter-Receiver/dp/B082M8VWSL/
link2: https://www.amazon.de/dp/B07P5QZ8PP/
link3: https://www.aliexpress.com/item/32803052003.html
link4: https://www.banggood.com/Ebyte-E18-MS1-PCB-IO-CC2530-Mesh-Network-2_4GHz-Transceiver-Wireless-RF-Module-for-ZigBee-p-1765567.html
---
This module consists of a TI CC2530 with 2.5mW transmit power.

![Back](/assets/images/devices/Ebyte_E18-MS1-PCB_back.webp)

PCB pins are 1.27mm and slightly harder to solder wires to.

To be able to use it as a coordinator or router you need to [flash](flashing_ccloader) the **CC2530_** [Z-Stack-firmware](https://github.com/Koenkk/Z-Stack-firmware/).

## Flashing Instructions
Identify the required pins and follow flashing instructions:
- flash using [CCLoader](/flashing_ccloader.html) and NodeMCU/Wemos D1 mini (or similar ESP8266 board)
- flash using [Raspberry Pi](http://www.marrold.co.uk/2019/12/flashing-cc2530-cc2591-zigbee-module.html)
- flash using [CC Debugger](http://ptvo.info/how-to-select-and-flash-cc2530-144/) 

VCC pin tolerates 3.6V max. **DO NOT** connect to 5V.

![Pinout](/assets/images/devices/Ebyte_E18-MS1PA-PCB_pinout.webp)

[User manual](https://www.cdebyte.com/pdf-down.aspx?id=2523).
