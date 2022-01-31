# Litkit-v2

![Likit1](https://github.com/GameboxSystems/Litkit-v2/images/litkit1.jpg)
![Likit2](https://github.com/GameboxSystems/Litkit-v2/images/litkit2.jpg)

Back for round 2, litkit aims to be the RGB LED pico board for your next project.

Features built in Micro USB interface for programming with Arduino IDE, powered by an Attiny85, an WS2812B addressable RGB LED, and on board button for cycling LED modes.

## Getting Started

### Prerequisites

Requied:

- Litkit v2 PCB
- Micro USB cable
- [Arduino IDE](https://www.arduino.cc/en/software/)
- [Digispark driver](https://github.com/digistump/DigistumpArduino/releases/download/1.6.7/Digistump.Drivers.zip)
- * USBtinyISP PCB
- * [USBtinyISP Driver]()

* If building from scratch

Recommended:

- FastLED Library(can be installed through Arduino IDE)

### Flashing Bootloader (Skip if purchased preassembled unit)

*Coming soon*

### Software Setup

- Install Arduino IDE and digispark drivers
- Open Arduino IDE
- Open File->Preferences
- Add http://digistump.com/package_digistump_index.json to "Additional Boards Manager URLs"
- Run Tools -> Board -> Boards Manager
- Install "Digistump AVR Boards" board package
- Select option Tools -> Board -> Digistump AVR Boards -> Digispark (Default 16.5MHz)
- Select option Tools -> Programmer -> Micronucleus

### Uploading Program to Litkit

Compile your code for the RGB LED. Once ready to upload the program to the board, select upload *WITH LITKIT UNPLUGGED!* A message will appear in the console instructing you to plug in the board within 60 seconds. Plug Litkit in and it will automatically start uploading your program. Once it's done, Litkit will reboot and display your RGB LED program

**NOTE:** If your computer says "Unrecognized USB device" after flashing or after allowing your litkit to be plugged in after 10 seconds, this is normal. It is the micro controller exiting USB flashing mode and running the program. To reprogram, unplug litkit and follow the flashing instructions again.

## Built with

- Eagle

## Versions

- v2.0 initial hardware release

