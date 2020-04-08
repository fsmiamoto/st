# st - simple terminal
My build for st, a simple terminal emulator for X which sucks less.

## Patches added:
- alpha
- boxdraw
- xresources
- font2
- scrollback

## Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st:

    $ sudo make clean install


## Requirements
In order to build st you need the Xlib header files.

## Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

