# xboxone-hecks
XboxONE is cool, artiface is cool! Attempt to recreate the SystemOS on a xbox on a window 10 IOT x86 build!
# the instructions without instructions!
Create a file structure for a usb drive! (make sure its a big drive)
```
[PC]> mkdir (DRIVE):/dump
    > mkdir (DRIVE):/dump/sysos
```
Dump the SystemOS partition!
```
[XBXONE DEVMODE SHELL]> xcopy c:/ (YourDrive):/dump/sysos/
```
# Then you will need to find a way to copy xbox stuff over to /dump/sysos, without ruining the install! (GoodLuck), Or wait and see if my dumbass can do it :(
