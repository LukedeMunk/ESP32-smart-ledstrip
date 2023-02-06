# ESP32 Smart Ledstrip Controls

Code is comming soon!

Code for IR and web-based controls of WS2801 ledstrip using an ESP based microchip. The software is tested on the following boards:

* ESP32 DEVKIT V1

## Features

The application consist of a wide range of features.

* XX different modes
* Sunrise simulation on time
* Time controls
* A web-interface to control and configure modes
* IR remote controls

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The software is written, compiled and uploaded using the Arduino IDE (v1.8.13). You could use the online Arduino IDE or other software, but I recommend using the version you can download on [this page](https://www.arduino.cc/en/software). In order to use the Arduino IDE as tool for uploading to the ESP, there are several steps to follow. Please visit the following tutorials:

* https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
* https://randomnerdtutorials.com/install-esp32-filesystem-uploader-arduino-ide/

### Installing

Clone the repository, open "ws2801controls.ino" and upload the program to the ESP. XXXXXXXXXXXXX

## Hardware

The following hardware is nessecary for this project:

* 1x ESP32 (or comparable)
* 1x 5V xA adapter (x depends on the number of leds. x = number_leds*60mA)
* 1x IR receiver
* 1x IR remote

In the `documentation` folder you can find a circuit diagram.

## Questions or feedback?

You can submit an issue if you have questions or feedback for this repository. If you are interested in more of my projects, checkout my GitHub [profile](https://github.com/LukedeMunk). If you are interested in hiring me, checkout my [LinkedIn](https://www.linkedin.com/in/luke-de-munk/).

## Authors

* **Luke de Munk** - *Head author* - [LinkedIn](https://www.linkedin.com/in/luke-de-munk/)

## Built With

* [FreeRTOS](https://www.freertos.org/) - Real-Time Operating System used to do parrallel processing.
* [FastLED](https://github.com/FastLED/FastLED) - Firmware for LEDstrip.
* [IRRemote](https://www.arduinolibraries.info/libraries/i-rremote) - The library for IR receiving.
* [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer) - The library for webserver.