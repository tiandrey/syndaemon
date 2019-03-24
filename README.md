# syndaemon
Patched version of syndaemon that distinguishes Shift from other modifier keys.

Added command line switch `-S` that acts like `-K` (ignore Modifier and Modifier+Key combos) but does not ignore Shift+Key combos.

Usage: `syndaemon -i 0.5 -S -R -d`

Original version: https://github.com/freedesktop/xorg-xf86-input-synaptics/blob/xf86-input-synaptics-1.8.2/tools/syndaemon.c
