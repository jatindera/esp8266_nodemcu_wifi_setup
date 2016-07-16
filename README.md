# DEPRECATED by nodemcu enduser_setup module

# ESP8266 NodeMCU WiFi Setup 
![Alt text](/../images/screenshot.png?raw=true "Screenshot")

This script allows and end users to easily configure an ESP to connect to a local WiFi.
 * Start ESP.
 * Connect to the "SetupGadget" WiFi through your internet enabled thing of choice.
 * Submit credentials of your local WiFi.
 * The ESP reboots and connects to your local WiFi.

## This is magic! How can I replicate it?
A guide to building NodeMCU can be found [here](http://memset.io/building-nodemcu-for-the-esp8266.html).

 * In dhcpserver.h, #define USE_DNS 1
 * Build NodeMCU.
 * Flash NodeMCU.
 * Upload all .lua files **and** index.html.
 * Reboot ESP.
 
## Thank you
This is based on Andy Reischles [Captive Portal](https://github.com/reischle/CaptiveIntraweb/tree/dev).
