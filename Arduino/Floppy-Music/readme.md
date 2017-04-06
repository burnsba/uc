Floppy music project. It's harder than it looks.

Based on https://github.com/SammyIAm/Moppy

I bought a bluetooth usb power adapter that output 5V at 700mA, which is what the floppy drive specified. Cut the cord and wired it to a breadboard. I connected the floppy 4-pin power (groundx2 and 5v, left 12v unconnected).

The STEP (20) and DIR (18) pins on the floppy IDE connector are connected to pins 2 and 3 on the Arduino.

The drive select pins (12 & 14) are connected to ground. 

The arduino is powered through USB, but the ground pin was connected to the same power ground as the floppy drive.  
