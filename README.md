 Special thanks to the original author, Bruce E. Hall:

NTP Dual Clock

This project is a modified version of Bruce E. Hall's NTP Dual Clock. It displays local time and a secondary time zone on a TFT screen using an ESP32  microcontroller.
The clock syncs with an NTP server and updates both time zones every 30 minutes.

Features
Displays local time and a second time zone of your choice.
Supports 12-hour or 24-hour format for both time zones.
Displays WiFi signal strength and NTP sync status.
Optional serial output of the current time.
Customizable time zones and WiFi credentials.

Hardware Requirements
ESP32 CYD esp32-2432S028 from ali express or Amazon
No soldering required!

Software Requirements
Arduino IDE 1.8.13 (or later) with Expressif ESP32 package installed
TFT_eSPI Library
ezTime Library

Open the sketch in Arduino IDE, and ensure you have the correct TFT_eSPI User_Setup.h configured for your board.

Update your WiFi credentials and time zone information in the code:

Usage
Once powered on, the device will display both the local and secondary time zones, refreshed every second. Ensure the device has a stable WiFi connection to synchronize time via NTP.

Special Thanks
A huge thank you to Bruce E. Hall (w8bh.net) for the original codebase, and to John Price for his contributions. 
This sketch has been adapted by Coolmd (Mark) to include custom time zone support, with additional modifications for the CYD 2.8” ESP32 display.

For much more detailed information and help for the CYD boards see_ https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display.

Also here is a link to the correct CYD_2usb User_Setup for the TFT_espi library for the later version of the CYD
https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display/blob/main/DisplayConfig/CYD2USB/User_Setup.h
