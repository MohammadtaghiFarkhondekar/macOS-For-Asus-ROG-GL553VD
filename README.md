**Guid for install macOS Mojave on Asus GL553VD**
![cover](https://raw.githubusercontent.com/MohammadtaghiFarkhondekar/macOS-Mojave-For-Asus-ROG-GL553VD/master/cover.jpg)
----------------------------------------------
1. Only use clover folder for boot 
2.  For install Trackpad -->
- delete kexts in S/L/E =
- AppleIntelLpssI2CController.kext 
- AppleIntelLpssI2C.kext in 
- Open terminal and run=> 
```
sudo kextcache -i /
sudo touch /System/Library/Extensions/ && sudo kextcache -u/
```
3. reboot


*Thank a lot :*
----------------------------------------------
- https://www.hackintosh-forum.de/user/38895-anonymous-writer/
- https://www.hackintosh-forum.de/user/15790-macpeet/
- https://www.hackintosh-forum.de/

*Source*
----------------------------------------------
- https://github.com/alexandred/VoodooI2C
- https://github.com/acidanthera
- https://github.com/RehabMan
- https://www.insanelymac.com/forum/topic/321080-sineteks-driver-for-realtek-rtsx-sdhc-card-readers/
