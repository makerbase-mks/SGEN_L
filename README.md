# MKS SGEN_L
## Features
- 32-bit MCU, LPC1768, CPU frequencies of up to 100 MHz
- Support TMC2208/2209 UART mode, TMC2130 SPI mode
- Support MKS TFT24/28/32/35/70...
- Support MKS LCD12864B/LCD12864/MKS MINI12864...
- Support Marlin2.0 and Smoothieware firmware

## Firmware
  - Marlin2.0 link: https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x
  - Smoothieware link: http://smoothieware.org/
  - Of course, you cna download firmware form SGEN_L path.
### How to Build Marlin2.0 by platformio and update firmware
  - Open platformio.ini file, set default_envs = LPC1768
  ![1-LPC1768](https://github.com/makerbase-mks/SGEN_L/blob/master/Picture/1-LPC1768.png "1-LPC1768")
  - Open configuration.h file, set board as MKS SGEN_L
  ![2-SGEN_L](https://github.com/makerbase-mks/SGEN_L/blob/master/Picture/2-SGEN_L.png "2-SGEN_L")
  - Build firmware
  ![3-build](https://github.com/makerbase-mks/SGEN_L/blob/master/Picture/3-build.png "3-build")
  - Build done
  ![4-build_done](https://github.com/makerbase-mks/SGEN_L/blob/master/Picture/4-build_done.png "4-build done")
  - Copy firmware.bin to TF card, inset MKS SGEN_L board, reset or repower uptade firmware.(firmware.bin path ".pio\build\LPC1768")
  ![5-copy_bin](https://github.com/makerbase-mks/SGEN_L/blob/master/Picture/5-copy_bin.png "5-copy bin")
  
## How to buy the MKS SGEN_L  
  https://www.aliexpress.com/item/33036918120.html?spm=2114.12010612.8148356.5.86d511412DjN3h
![MKS_SGEN_L](https://github.com/makerbase-mks/SGEN_L/blob/master/Picture/MKS_SGEN_L.png "MKS SGEN_L")