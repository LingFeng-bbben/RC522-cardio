# Based on CrazyRedMachine/PN5180-cardio, but in RC522
 RC522 ISO14443A wavepass USB HID card reader (cardio)

# Acknowledgments

This work is based on zyp's cardio.
HID layer code is based on Matthew Heironimus' <Joystick.h> library.

Make sure to use a proper card so your important card id will not be exposed to any network services.

# Supported devices

This code has been tested on Arduino Leonardo.

# How to use

Download zip, flash the firmware, unplug, connect the RC522 to the Arduino.

Congratulations, your device should work just like a real cardio, use 
your favorite tools instructions to play (e.g. "spicetools -cardio" ).
