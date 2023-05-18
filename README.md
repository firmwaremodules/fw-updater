## Update your device firmware

fw-updater: a GUI firmware updater front end.

This **web application** runs in your browser and will interface with your devices over any supported link to facilitate the firmware update process.

It can update any device running the [stm32-secure-patching-bootloader](https://github.com/firmwaremodules/stm32-secure-patching-bootloader) and a supported updater module.

### Supported Updater Modules

| Module | Connection | Protocol | Description | 
| --- | --- | --- | --- | 
| *default* | UART | YMODEM | stm32-secure-patching-bootloader **built-in** YMODEM updater |
| ymodem-updater | UART |  YMODEM | YMODEM updater present in user application |
| lorawan-updater | LoRaWAN/Helium | [ELPP](https://github.com/measurementearth/elpp-decoder) | Update your device over any LoRaWAN or Helium network using the Measurement{Earth} Low Power Protocol |



