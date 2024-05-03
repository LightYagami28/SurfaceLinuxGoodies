# SurfaceLinuxGoodies
Configs and utilities for Linux users on a Microsoft Surface tablet.

## Note taking
This section contains everything that might be useful when using the tablet as a note-taking device.

### Surface Pen purple button
Enables the purple button to be programmed to take an action upon pressing. Be aware that for some reason, the pen must be paired each time upon reboot. The default action chosen is to send CTRL+z to the active window, which is helpful for note-taking.

### Pen disable touchscreen
Contains a script and a service (which must be enabled, of course) for disabling the touchscreen when the Surface Pen is hovering on the screen. Useful for improved palm rejection.

### xournalpp-config 
Just a set of settings the author is comfortable with in xournal++ (autosave settings, custom toolbars, etc.)

### config-wacom-libinput
Contains X11 configuration for using the libinput driver for both the Touchpad and Touchscreen while still using the wacom driver for the pen.

## General usage

### Automatic screen rotation
Contains a script and a service (which must be enabled, of course) for making it possible to automatically rotate the screen based on the device's orientation.

### Enable vsync
On integrated Intel graphics, vsync might not be enabled by default. This can cause a 'tearing' effect when scrolling contents.

### Wi-Fi restart switch
On the Surface Pro 3 (among few others), the wifi kernel drivers are a bit buggy. When launched, this script reloads the kernel module, effectively restarting connectivity (most of the time).
