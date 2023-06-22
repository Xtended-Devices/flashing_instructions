<a href="#"><img src="assets/spacewar.png" height="60" /></a> 
#

~~~diff
- // Disclaimer:
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.
~~~

:point_right: **Download required packages**
- Recovery package [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)

:point_right: **If comming from NothingOS or from anyother ROM, Required clean flash, So...**
- Backup all your data to any external source. 
- Gapps included so no need to flash/sideload GApps

:point_right: **Now start Flashing**
1. Reboot to bootloader & connect your phone to PC
2. Extract above recovery package.zip
3. Double click on __flash.bat__
4. Reboot to recovery & Factory reset > Format data/factory reset
5. Back to recovery home page & Apply update > Apply from ADB
6. Now sideload rom using command ```adb sideload <rom_filename>.zip```
7. Now reboot to system.

:point_right: **Updating ROM (Because you're already on Xtended A13)**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
4. Reboot

Note: :warning: Every version isn't upgradable. It depends on system changes, So please follow release post first.

