# syndaemon
Patched version of syndaemon that distinguishes Shift from other modifier keys.

Changed command line switch `-K` so that syndaemon does not ignore Shift+Key combos. Note: works only with XRecord extension (`-R`)!

Usage: `syndaemon -i 0.5 -K -R -d`

Original version: https://github.com/freedesktop/xorg-xf86-input-synaptics/blob/xf86-input-synaptics-1.8.2/tools/syndaemon.c

Note: latest version of syndaemon enables touchpad if you press modifier key, and in practice touchpad is enabled on almost all KeyRelease events. I have no intention to fix that behavior and will rather use older version of syndaemon.
