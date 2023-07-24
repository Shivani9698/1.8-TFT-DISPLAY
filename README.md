# 1.8-TFT-DISPLAY

# Random Color Hello World

This Arduino sketch displays the text "Hello, World!" on a TFT screen using a random font color. The colors of the text change every 200 milliseconds to create a dynamic visual effect.

## Hardware Requirements

- Arduino UNO
- TFT screen compatible with the Arduino UNO
- Connections: Connect the TFT screen to the Arduino UNO using the following pin configuration:
  - TFT CS pin to Arduino pin 10 (cs)
  - TFT DC pin to Arduino pin 9 (dc)
  - TFT RST pin to Arduino pin 8 (rst)

## Pin Wiring

1.8 TFT Display	Wiring to Arduino Uno
LED-	3.3 V

SCK-	13

SDA	-11

A0 or DC-	9

RESET-	8

CS	-10

GND-	GND

VCC-	5 V

## Software Requirements

- Arduino IDE (Integrated Development Environment) to upload the sketch to the Arduino board.
- TFT library and SPI library for Arduino.

## Installation and Usage

1. Install the Arduino IDE on your computer (if not already installed).
2. Connect the TFT screen to the Arduino UNO following the hardware requirements.
3. Open the "RandomColorHelloWorld.ino" file in the Arduino IDE.
4. Upload the sketch to the Arduino UNO board.
5. The "Hello, World!" text will be displayed on the TFT screen with random font colors that change every 200 milliseconds.

## Wiring Diagram

![image](https://github.com/Shivani9698/1.8-TFT-DISPLAY/assets/119753029/c5edf185-9cf4-40e0-a733-64dd1dcd30ab)




## Author

- Shivani Raj

