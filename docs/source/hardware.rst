Hardware
==============

Hardware Specification
----------------------

* Main Processor: 
  * ESP32 Wrover Module
  * PSRAM: 8MB
  * Flash: 16MB
* Display:
  * 2.8" TFT IPS Display
  * ST7789V driver
  * 320x240 pixels
  * 16bit color
  * SPI interface
* Touch Panel:
  * Capacitive Touch Panel
  * GT911 Touch Controller
  * 5-Point touch 
  * IIC interface
* Charger:
  * LTH7 LTC4054
  * 4.2V/800mA
* 3.3V LDO
  * AP2112K
  * 3.3V/600mA

Interfaces
-----------
* Battery Connector:
  * PH2.0 2P Connector
  * Li-Ion/Li-po Battery
  * Tpy. 3.7V, Max. 4.2V
* SD Card:
  * MicroSD Card
  * SPI interface
* USB:
  * CP2102 USB-to-serial converter
  * USB Type C connector
  * USB 2.0 interface
* QWIIC/STAMMA QT
  * IIC
* Buttons
  * Reset Button
  * IO0 Button
* Switch
  * ON/OFF Switch for LDO
* Header
  * 2 x 8 Pitch 2.54mm Pin Socket

Pin Socket IO
--------------

.. list-table:: Pin Socket
  :widths: 25 25

  * - VBAT
    - 3V3
  * - VUSB
    - TXD
  * - MISO
    - RXD
  * - MISO
    - IO35
  * - SCLK
    - IO34
  * - SDA
    - IO33
  * - SCL
    - IO26
  * - GND
    - IO25


Pin Table
---------

.. list-table:: Pin Table
  :widths: 25 25 40
  :header-rows: 1

  * - DPU ESP32
    - ESP32
    - Description
  * - MOSI
    - IO13
    - SPI MOSI
  * - MISO
    - IO12
    - SPI MISO
  * - SCLK
    - IO14
    - SPI SCLK
  * - SDA
    - IO4
    - I2C SDA
  * - SCL
    - IO5
    - I2C SCL
  * - TFT_CS
    - IO15
    - TFT Display SPI CS
  * - TFT_DC
    - IO27
    - TFT Display Data/Command 
  * - TFT_RST
    - IO32
    - TFT Display Reset
  * - TFT_BL
    - IO18
    - TFT Display Backlight control
  * - SD_CS
    - IO23
    - SD Card SPI CS
  * - SD_CD
    - IO22
    - SD Card Detect
  * - TP_RST
    - IO21
    - Touch Panel Reset
  * - TP_INT
    - IO19
    - Touch Panel Interrupt
  * - BAT_LV
    - IO39
    - Battery Level
  * - CHG
    - IO36
    - Charging Detect

