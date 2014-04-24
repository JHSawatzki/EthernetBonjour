EthernetBonjour
===============

Bonjour (ZeroConf) Library for Arduino & Teensyduino

mDNS (registering services) and DNS-SD (service discovery) has been tested and works on:
Teensy++2 with WIZ81MJ and
Teensy3 with WIZ820io

Using Arduino 1.0.5 and Teensyduino 1.18

The newest revised code replaces all direct hardware calls to the W5100 chip with calls to EthernetUDP methods.
This will provide much better adaptability to different Ethernet hardware. 
