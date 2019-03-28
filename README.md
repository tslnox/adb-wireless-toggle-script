# Magisk Module Template

**adb wireless toggle** is a little script that can toggle adb wireless on and off and print the current state
Use "adbw help" to show all parameters

When invoked without any parameters, it toggles between on and off, or you can tell it to enable or disable it regardless on the state. 

The prop should revert to default state on reboot. Script doesn't touch any system files and only uses getprop and setprop commands, so it should be absolutely safe.
