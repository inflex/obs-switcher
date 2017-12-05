# obs-switcher
USB keypad for switching scenes in Openbroadcaster.


Uses an Atmel ATMega48 AVR flashed with the v-usb / obdev firmware, modified by Paul L Daniels to provide a compact scene switcher with LED state indication.

# Firmware

In the firmware folder the Atmel AVR ATMega48 code is located.  If you have avr-gcc and the normal Atmel AVR build suite installed then you should be able to run "make && make fuse && make flash" and the AVR should be flashed with the firmware.

At this point, the ISP header is a simple non-polarised 6 x 1mm pitch set of holes in the board, while it's not ideal for a lot of situations it does make for a cheap and non-intrustive method of flashing using a cheap ISP such as the usbTiny.
