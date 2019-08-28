# tpad
Touchpad enabling / disabling shell script

This simple POSIX shell script enables you to easily toggle your Linux laptop's touchpad on or off, under Xorg.

It's perfect for hooking up your laptop's hotkeys, for automation purposes or simple operation from the command line.

## Usage:

```
% tpad e(nable) | d(isable) | t(oggle)
```

Calling tpad without any parameters toggles your touchpad on / off by default.

**Please note:**
You may need to edit the script and change the device search string according how your touchpad is named. If this applies to you, inspect the output of "xinput" for your touchpad device and modify the script accordingly.

```
% xinput -list
```

This script works for me, don't hesitate to suggest improvements if you have them.
