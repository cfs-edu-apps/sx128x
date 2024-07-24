# sx128x
An SX1280 transceiver library design to be used on a Raspberry Pi. The LoRa app is an example of how an app can use this library. 

## cFS Integration Notes
1. arch_build_custom.cmake: Comment out -std=c99 in order to build C++