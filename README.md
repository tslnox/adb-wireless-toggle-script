# Magisk Module Template

**ADB Wireless toggle** is a little script that, when used, will check if adb wireless is active or not, and switch it on or off.
Usage: adbw

When the script toggles the adb wireless on, it prints the current IP in the shell. It uses standard 5555 port.

If the prop service.adb.tcp.port is anything else than 5555 (enabled) or -1 (disabled), it resets it off. The prop should revert to default state on reboot and the script doesn't touch any system files, only uses getprop and setprop commands.
