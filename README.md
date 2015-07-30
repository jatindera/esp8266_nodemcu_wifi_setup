# ESP8266 NodeMCU WiFi Setup
![Alt text](/../images/screenshot.png?raw=true "Screenshot")

This script allows and end users to easily configure an ESP to connect to a local WiFi.
 * Start ESP
 * Connect to the "SetupGadget" WiFi through your internet enabled thing of choice
 * Submit credentials of your actual WiFi
 * The ESP reboots and connects to your actual WiFi

## This is magic! How can I replicate it?
 * Build NodeMCU with the nodemcu_use_dns.patch applied (or #define USE_DNS 1, set in dhcpserver.h)
 * Flash NodeMCU
 * Upload all .lua files _and_ index.html
 * Reboot ESP
 
## Thank you
This is based on Andy Reischles [Captive Portal](https://github.com/reischle/CaptiveIntraweb/tree/dev).
