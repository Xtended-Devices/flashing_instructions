<a href="#"><img src="assets/oneplus7.png" height="60" /></a> 
#

~~~diff
- // Disclaimer:
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.
~~~

:point_right: **Download required packages**
- Recovery package [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)
- Sideload copy-partition zip: [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/copy-partitions-20220613-signed.zip/download)

:point_right: **If comming from OxygenOS or from anyother ROM, Required clean flash, So...** 
- Backup all your data to any external source. 
- Required OxygenOS 12 in both slot, If already then skip step 3 & 4 if not **must follow all steps**
- Gapps included so no need to flash/sideload GApps

:point_right: **Now start Flashing**
1. Reboot to bootloader & connect your phone to PC
2. flash recovery.img. (Extract recovery package to get recovery.img)
3. Reboot to recovery > Apply update > Apply from ADB
4. Sideload copy-partition zip by using command ```adb sideload copy-partitions-20220613-signed.zip```
5. After complete, Back to recovery home page & tap Factory reset > Format data/factory reset
6. Back to recovery home page & tap > Apply update > Apply from ADB
7. Now sideload rom using command ```adb sideload <rom_filename>.zip```
8. Now reboot to system.

:point_right: **Updating ROM (Because you're already on Xtended A13)**
1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
4. Reboot

Note: :warning: Every version isn't upgradable. It depends on system changes, So please follow release post first.

