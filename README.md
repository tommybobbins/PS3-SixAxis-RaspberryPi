PS3-SixAxis-RaspberryPi
=======================

PS3 controller attached via USB to Raspberry Pi. Button mapping for Minecraft Pi Edition.

    $ sudo apt-get install xserver-xorg-input-joystick 
    $ sudo cp 50-joystick.conf /usr/share/X11/xorg.conf.d/

Note that keycodes can be looked up using:

    $ DISPLAY=:0 xmodmap -pk >all_keys.txt
