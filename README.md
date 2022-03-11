# Modem and bootloader repository 
**for Samsung Galaxy S10e/S10/S10+ Exynos variants (including korean N)**

### Do note this is not a way to downgrade revision of modem and bootloader.

```
Copyright 2020-2022 © corsicanu
Licensed under CC BY-NC-SA 4.0
https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode
```
### Disclaimer
```
I am not responsable for anything you do with your device, don't blame me or anyone else 
involved in this for your failures, you are the only one choosing to mess up with your device. 
All the files here are pulled from official firmwares of the devices mentioned.
```

### WARNING!!! DO NOT FLASH DEVICE_TREE UNLESS YOU WERE TOLD TO, BEFORE DOING BAD THINGS TO YOUR DEVICE YOU BETTER CHECK OUT WITH YOUR LOCAL DEV

## Instructions:
**1. Update via TWRP:**
   - Download proper  **\*\-twrp\_flashable\.zip** according to your phone model from [releases](https://github.com/corsicanu/9820-bootloaders_and_modems/releases) 
   - Boot phone in TWRP
   - Flash the downloaded zip as any other
   - Optional - download and flash [TWRP_Bootlogo_patcher.zip](https://downloads.corsicanu.ro/samsung/TWRP_Bootlogo_patcher.zip) to get rid of the boot warning

**2. Update via Odin:**
   - Download [Odin v3.14.1](https://downloads.corsicanu.ro/samsung/Odin3_v3.14.1.zip)
   - Download and install [Samsung Drivers](https://downloads.corsicanu.ro/samsung/SAMSUNG_USB_Driver_for_Mobile_Phones.zip)
   - Download proper **\*\-odin\_flashable\.tar** according to your phone model from [releases](https://github.com/corsicanu/9820-bootloaders_and_modems/releases)
   - Switch off the phone
   - Use Volume Down+Bixby+Usb cable to enter Download Mode
   - Open Odin and make sure that your device is detected
   - Put **\*\-odin\_flashable\.tar** file into BL tab
   - Click Start and wait for the device to reboot

