# OpenBLEButton

The idea behind this project is to develop a generic BLE interface, a BLE WiFi gateway and a cloud service.

It should ideally contain schematics for two devices minimum and firmware for them. We hope to have a commercial product from it.

Platforms under investigation are: Nordic NRF51 for the button and ESP32 for the gateway.

Open to contributions!

## Generic BLE Interface
Battery, one button, one led and a radio. Based on experiments from https://www.iot-experiments.com/nrf51822-and-ble400/
References:
STLink SWO: https://blog.3mdeb.com/2017/2017-01-22-nrf51822-programming-with-openocd-under-linux/


## BLE WiFi
Micro USB for power, two leds for feedback and MQTT or similar for communication to cloud service.

## Cloud service
A docker container and a simple service to forward packets.
