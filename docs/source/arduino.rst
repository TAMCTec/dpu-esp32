Arduino Usage
===

DPU ESP32 is now mainly supported by Arduino, with LVGL libraries. Now all examples are using LVGL for the UI.

Here's the repository for the examples: https://github.com/tamctec/dpu-esp32-arduino

Gettting Started
---------------

To get started, you need to install the Arduino IDE first from here: https://www.arduino.cc/en/Main/Software

Then, you need to install the ESP32 Arduino library:

Go throuth Files => Preferenced. At Additionnal Boards, add the following url: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json

Next, you need to install ESP32 core library from Tools => Boards => Board Manager...

And under Board Manager, search ESP32, and install it.

Now we have ESP32 core library installed, we need to install the DPU library for examples and the needed dependencies.

Go through Sketch => Include Library => Manage Libraries...

Under Library Manager, search DPU ESP32, and install the TAMC DPU ESP32 library. It will automatically install all nessesary dependencies.

Now everything is ready! Remember to choose DPU ESP32 board: 
Go through Tools => Boards => ESP32 Arduino, Scroll to the very bottom, and you will see it.

Choose an example to start! It's under Files => Examples => DPU ESP32.
