
LCD I2C example in Zephyr
######

Overview
********

This sample shows how to interface an I2C OLD display and using LVGL in Zephyr.

Requirements
************

#. ESP32 Devkit C
#. Zephyr OS and West installed
#. SSD13o6 I2C based OLED display 128x64

Building and Running
********************
Initially and everytine you start a shell please run:
<br>
$>source ~/zephyrproject/zephyr/zephyr-env.sh

Build and flash as follows:
<br>
For the first build: 

For esp_custom board 

$> west build -p -b esp_custom


For subsequent builds:

$> west build


To Flash:

$> west flash


After flashing, optinally view the printk output on a terminal emnulator @ 115200, no handshaking

$> west flash ; minicom

