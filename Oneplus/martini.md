~~~diff
- // Disclaimer:
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.
~~~
## Flashing instructions for OnePlus 9rt/martini

:point_right: **Pre-requisites:**

* Make sure you have oos13 on both slots of your device
* If already currently on OOS13 (F15) do local install of Oos13 F15 once again
* OOS13.1 not recomonded as it has not been tested, So rollback to F.15
* If you are currently on custom rs based on oos13 f.15 just follow Flashing instructions

:point_right: **CLEAN FlASH**
* Download boot dtbo and vendor_boot from [**HERE**](https://sourceforge.net/projects/mrick-projects/files/project_xtended/recovery)
* Reboot to bootloader & connect phone to PC
* Flash all images by using command:
```
fastboot flash boot boot.img
fastboot flash vendor_boot vendor_boot.img
fastboot flash dtbo dtbo.img
```
* Now reboot to recovery & tap Factory reset > Format data/factory reset
* Now Back to recovery home page > Apply update > Apply from ADB
* Now sideload rom using command ```adb sideload <rom_filename>.zip```
* Now reboot to system.

:point_right: **Updating Rom: (If already on Xtended A13)** 
* Download the ROM 
* Now reboot to recovery > Apply update > Apply from ADB
* Now sideload rom using command ```adb sideload <rom_filename>.zip```
* Now reboot to system.

Note: :warning: **_If the status stops while flashing ROM at 47% don't panic since that's normal_**
