<a href="#"><img src="assets/oneplus9.png" height="60" /></a> 
#

~~~diff
- // Disclaimer:
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.
~~~

:point_right: **Download required packages**
- Recovery package [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)

:point_right: **If comming from OxygenOS or from anyother ROM, Required clean flash, So...**
- Backup all your data to any external source. 
- Update your device to OOS 13
- Firmware already included
- Gapps included so no need to flash/sideload GApps

:point_right: **Now start Flashing**
1. Extract recovery package zip
2. Reboot to bootloader & connect your phone to PC
3. Double click on __flash.bat__
4. Reboot to recovery & Factory reset > Format data/factory reset
5. Back to recovery home page & tap > Apply update > Apply from ADB
5. Now sideload rom using command ```adb sideload <rom_filename>.zip```
7. Now reboot to system.

:point_right: **Updating ROM (Because you're already on Xtended A13)**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
4. Reboot

Note: :warning: Every version isn't upgradable. It depends on system changes, So please follow release post first.

