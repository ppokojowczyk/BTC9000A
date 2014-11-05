BTC9000A Configuration Script
=============================

Linux config script for BTC 9000A PS/2 keyboard. It assigns key's scancodes to adequate Xorg events.
There is no 'Shortcut' Xorg event, so I assigned it to XF86Documents.

I've tested it on Manjaro Linux with 3.12.30-1 kernel, Xorg 1.16.1-1 and XFCE 4.10.

Scancodes:
----------

![Keys layout](keys.jpg)

* e05e - Shutdown -> XF86PowerOff
* e05f - Sleep -> XF86Suspend
* e063 - Wake Up -> XF86WakeUp
* e02e - Help -> Help
* e020 - Favorites -> XF86Favorites
* e030 - WWW / HomePage -> XF86HomePage
* e026 - Shortcut -> XF86Documents
* e032 - Search -> XF86Search
* e01e - Volume Up -> XF86AudioRaiseVolume
* e025 - Volume Down -> XF86AudioLowerVolume
* e012 - Mute -> XF86AudioMute
* e022 - Previous / FastBackward -> XF86AudioPrev
* e010 - Stop -> XF86AudioStop
* e019 - Play/Pause -> XF86AudioPlay
* e021 - Eject -> XF86Eject
* e024 - Next / FastForward -> XF86AudioNext

Advice for Windows users
------------------------

I recommend using [SharpKeys](http://sharpkeys.codeplex.com/). You can use it to remap certain keys to appropriate functions.
