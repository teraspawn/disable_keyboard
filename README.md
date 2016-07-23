# disable_keyboard

Disable and re-enable the keyboard and trackpad.

First, find out the ID numbers for the keyboard and trackpad from running:

xinput

Then substitute these for 13 and 14 in the script.

Copy disable_keyboard into your /usr/bin/ directory (as root), then copy disable_keyboard.desktop into ~/.local/share/applications/

You can then add a shortcut to your Unity taskbar, by searching for "disable keyboard" in the apps menu and dragging it to the taskbar.
