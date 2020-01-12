# 24-bit Stereo Audio DAC for Raspberry Pi

This is a 24-bit stereo DAC, which is specifically built for Raspberry Pi boards. This R-2R ladder DAC is developing around Intel / Altera *EPM240T100C5N* CPLD.

DAC which described in this repo can directly connect with the I2S interface of Raspberry Pi boards. The recommended supply voltage for this DAC is 5V to 8V.

The *MCP602* opamp of this module is capable to drive headphone directly. An external AF power amplifier must pair with this module to obtain a higher output power.

This repository contains all the files and binaries to build DAC, which including *Intel Quartus* Project files, Raspberry Pi Device Tree Overlays, etc.

This is an open-source hardware project. All the content of this project are distributed under the terms of the following license:

- Hardware License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Software License: [MIT](https://github.com/dilshan/usb-external-display/blob/master/LICENSE)
- Documentation License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
