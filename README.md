# TTN-Device
Adafruit Adalogger m0 with Radio Featherwing
Using MCCI LoraWan LMIC Library by IBM

This is currently failing on os_init 
Specifically, radio_init is returning 0 in oslmic.c (part of library)

failure at \Documents\Arduino\libraries\MCCI_LoRaWAN_LMIC_library\src\lmic\oslmic.c:53

The goal is to get this device set up on The Things Network.

I've narrowed it down to either:
    1. My lmic pinout is wrong
    2. My Radio Featherwing is dead
