# Modem and bootloader repository 
**for Samsung Galaxy S10e/S10/S10+ Exynos variants (including korean N)**

### Do note this is not a way to downgrade revision of modem and bootloader.

```
Copyright 2019-2020 © corsicanu

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
### Disclaimer
```
I am not responsable for anything you do with your device, don't blame me or anyone else 
involved in this for your failures, you are the only one choosing to mess up with your device. 
All the files here are pulled from official firmwares of the devices mentioned.
```

## Latest releases:
```
G970FXXS6CTE6
G973FXXS6CTE6
G975FXXS6CTE6 
G977BXXU3CTC9
G970NKSU4CTC9
G973NKSU4CTC9
G975NKSU4CTC9
G977NKSU3CTC9
```

## Instructions:
**1. Update via TWRP:**
   - Download **\*\_twrp\_flashable\.zip** from [releases](https://github.com/corsicanu/9820-bootloaders_and_modems/releases)
   - Boot phone in TWRP
   - Flash the downloaded zip as any other
   - Optional - download and flash [TWRP_Bootlogo_patcher.zip](TWRP_Bootlogo_patcher.zip) to get rid of the boot warning

**2. Update via Odin:**
   - Download Odin v3.14.1
   - Download and install Samsung Drivers (if you have them installed you can skip this step)
   - Download **\*\_odin\_flashable\.tar** from [releases](https://github.com/corsicanu/9820-bootloaders_and_modems/releases)
   - Switch off the phone
   - Use Volume Down+Bixby+Usb cable to enter Download Mode
   - Open Odin and make sure that your device is detected
   - Put **\*\_odin\_flashable\.tar** file into BL tab
   - Click Start and wait for the device to reboot
