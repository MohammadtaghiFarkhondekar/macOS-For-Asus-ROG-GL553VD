Guid for install macOS Mojave on Asus GL553VD 
----------------------------------------------
1- Only use clover folder for boot 
2- For install Trackpad -->
delete = AppleIntelLpssI2CController.kext + AppleIntelLpssI2C.kext in S/L/E
3- Open terminal and run=> 

-------------------

sudo kextcache -i /
sudo touch /System/Library/Extensions/ && sudo kextcache -u/

-------------------
4- for install sound -->
install VoodooHDA = UEFI mode
5- reboot

Thank a lot :
----------------------------------------------
https://www.hackintosh-forum.de/user/38895-anonymous-writer/

https://www.hackintosh-forum.de/

Source
----------------------------------------------
https://github.com/alexandred/VoodooI2C
https://github.com/acidanthera/Lilu
https://github.com/acidanthera/WhateverGreen
https://github.com/chris1111/VoodooHDA-2.9.0-Clover-V12
https://github.com/RehabMan
https://github.com/RehabMan/OS-X-Clover-Laptop-Config/blob/master/hotpatch/SSDT-XOSI.dsl
