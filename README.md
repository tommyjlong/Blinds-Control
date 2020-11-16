# Tasmota Customized for Tilt Blinds

This is Tasmota firmware that has been customized and optimized for _ESP8266 based_ **Blinds Controller** like [MK SmartHouse](https://www.mksmarthouse.com/). It has been written for use with an Arduino IDE and tested on boards Generic and NodeMCU. 

The software originated as Sonoff-Tamota version 6.2.1.  It was compiled with Arduino core for ESP8266 version 2.3.0.


See [RELEASENOTES.md](https://github.com/tommyjlong/Blinds-Control/blob/master/RELEASENOTES.md) for release information

### Quick Install
Download one of the released binaries from https://github.com/tommyjlong/Blinds-Control/ and flash it to your ESP8266 hardware using your favorite method.

### If You Want to Compile Yourself on Windows 10
If you want to compile this yourself with Arduino IDE keep in mind the following:
- Dont yet start Arduino IDE
- Copy Sonoff Tasmota ..\lib files to C:\Users\<UserName>\Documents\Arduino\ directory. 
  This Assumes Arduino->File->Preferences->Sketch Location set to: C:\Users\<UserName>\Documents\Arduino
- Assumes no other interfering libraries are present in this same directory.
- Goto Sonoff Tasmota ..\sonoff\  directory.  Double-Click sonoff.ino to start Arduino IDE
- When setting up the Board Manager for esp8266, choose version 2.3.0. 
- Set the board type parameters acording to esp module being used (See below).
- Click on Verify button (the one with the check mark).  This should compile successfully.


The following devices are supported:
- ESP12
  Example, see [MK Smarthouse Blinds Controller with MG995 Servo](https://www.mksmarthouse.com/blinds-control)

  You can use the following Arduino IDE Board settings:
   TBD
- Node MCU

  You can use the following Arduino IDE Board settings:
   TBD

### Configuring the Blinds Controller


TO BE DONE

### Credits and License
Credit goes to [arendst/Tasmota](https://github.com/arendst/Tasmota), formerly
https://github.com/arendst/Sonoff-Tasmota, for the original code base.

This program is licensed under GPL-3.0
