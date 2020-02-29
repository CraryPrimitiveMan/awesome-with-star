# Information comes from [agucova/awesome-esp](https://github.com/agucova/awesome-esp)
<!--lint disable awesome-list-item-->
<!--lint disable awesome-toc-->
<!--lint disable no-blockquote-without-marker-->

# Awesome ESP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code-of-conduct.md)
A curated list of awesome ESP8266/32 projects and code.

<a href="http://espressif.com/en/products/hardware/esp8266ex/overview"><img src="https://cdn.instructables.com/FTQ/HQNH/J4OFNC31/FTQHQNHJ4OFNC31.LARGE.jpg" alt="ESP8266" align="left" style="margin-right: 25px" height=150></a>
<a href="http://espressif.com/en/products/hardware/esp32/overview"><img src="https://pbs.twimg.com/profile_images/863510403120222208/rjVOiTe3.jpg" alt="ESP32" align="left" style="margin-right: 25px" height=150></a>
> Both the [ESP8266](http://espressif.com/en/products/hardware/esp8266ex/overview) and the [ESP32](http://espressif.com/en/products/hardware/esp32/overview) are low-cost Wi-Fi microchips with full TCP/IP stack and microcontroller capabilities produced by the Shanghai-based manufacturer Espressif Systems.  
> <br/>
> See [Contributing](contributing.md) for information on how to contribute to this list.
> <br/><br/> 

<!--lint disable no-repeat-punctuation-->
## Contents
- [Firmware](#firmware)
- [Tools](#tools)
- [Projects](#projects)
  - [Smart Home and IoT](#smart-home-and-iot)
  - [InfoSec](#infosec)
  - [Biomedical](#biomedical)
  - [Others](#others)
- [Libraries](#libraries)

## Firmware
- [Espressif AT](http://bbs.espressif.com/) - The default vanilla firmware for the ESP8266.
- [NodeMCU](https://github.com/nodemcu/nodemcu-firmware) - An eLua-based firmware for the ESP8266. :star:5896
- [ESPBasic](http://www.esp8266basic.com/) - A BASIC firmware for easy and wireless programming, ready for the 8266.
- [MicroPython](https://github.com/micropython/micropython/) - An implemention of Python3 for the ESP8266. :star:10123
- [MicroPython/32](https://github.com/micropython/micropython-esp32) - A MicroPython port for the ESP32. :star:538
- [ESP32](https://github.com/luc-github/ESP3D) - An experimental firmware for 3D Printers, both the ESP32 and 8266. :star:643
- [Frankenstein](https://github.com/nekromant/esp8266-frankenstein) - A quick and dirty firmware with cool features for the ESP8266. :star:297
- [MongooseOS](https://github.com/cesanta/mongoose-os) - An IoT specific firmware, with both C and JS. Available for the ESP32/8266. :star:1930
- [DeviceHive](https://devicehive.com/) - A firmware made as a client for DeviceHive's IoT data platform, only for the 8266.
- [RT-Thread](https://github.com/RT-Thread/rt-thread) - Chinese open source firmware available for the ESP32. :star:4047
## Tools
- [ESP Flash Tool](http://espressif.com/en/support/download/other-tools) - The vanilla firmware flasher for both ESP's.
- [Arduino Core/8266](https://github.com/esp8266/arduino) - The Arduino core for the ESP8266. :star:10845
- [Arduino Core/32](https://github.com/espressif/arduino-esp32) - The other Arduino core for the ESP32. :star:4457
- [ESPTool](https://github.com/espressif/esptool) - Espressif's command line tool for bootloader comms in both ESP's. :star:2986
- [ESP-Open-SDK](https://github.com/pfalcon/esp-open-sdk) - An open SDK for the ESP8266. :star:1744
- [ESPTool-ck](https://github.com/igrr/esptool-ck) - A CLI tool for flashing in the ESP8266. :star:308
- [ESPTool-gui](https://github.com/Rodmg/esptool-gui) - A flashing GUI tool based on ESPTool-ck. :star:94
- [NodeMCU Flasher](https://github.com/nodemcu/nodemcu-flasher) - NodeMCU's official flashing tool for its OS. :star:1244
- [LuaNode](https://github.com/Nicholas3388/LuaNode) - A lua-only SDK for 32/8266. :star:513
- [Arduino FS Plugin](https://github.com/esp8266/arduino-esp8266fs-plugin) - An Arduino plugin for filesystem uploads in the 8266. :star:436
- [PlatformIO](https://github.com/platformio/platformio-core) - Cross Platform IDE and Debugger that supports both the ESP32 and ESP8266. :star:3803
## Projects
### Smart Home and IoT
- [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) - An implementation of a multiprotocol MQTT gateway for both ESP's among other devices. :star:1551
- [ESPHome](https://esphome.io/) - A full-featured system for controlling ESP's through simple yet powerful configuration files and Home Automation systems.
- [Sonoff-Homekit](https://github.com/Gruppio/Sonoff-Homekit) - An alternative firmware for Sonoff devices (and other 8266 devices) which allows control through Apple's Homekit. :star:475
- [DoorsignEPD](https://github.com/jamct/DoorsignEPD) - A smart... doorsign with an E-Paper display using the ESP32. :star:56
- [EPaperWeatherDisplay](https://github.com/henri98/esp32-e-paper-weatherdisplay) - A very cute e-ink weather display using the ESP32. :star:57
- [SuperGreenOS](https://github.com/supergreenlab/SuperGreenOS) - A full-featured home farming automation software for the ESP32. :star:31
### InfoSec
- [ESP32-BLECollector](https://github.com/tobozo/ESP32-BLECollector) - A wardriving device which displays BLE devices and collects data from them, all in a nice screen interface. :star:75
- [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) - An integrated suite of offensive and defensive tools for WiFi and Bluetooth. :star:63
- [ArduinoPcap](https://github.com/spacehuhn/ArduinoPcap) - A library which allows generation of .pcap files with network traffic, for both ESP's. :star:232
- [WiFi Satellite](https://hackaday.io/project/28831-wifi-satellite-34c3) - A giant Wifi "satellite" that can monitor all 14 2.4Ghz channels using, well, 14 ESP32s.
- [ESP8266 Deauther](https://github.com/spacehuhn/esp8266_deauther) - A very cool pseudojammer (deauther) of Wifi networks that uses the ESP8266. :star:6229
- [PacketMonitor](https://github.com/spacehuhn/PacketMonitor32) - A beautiful OLED monitor for packet activity in a WiFi channel. Two versions for each ESP. :star:176
- [WiFiDuck](https://github.com/spacehuhn/WiFiDuck) - A wireless-enabled keystroke injector, analogous, but even more awesome than the Rubber Ducky. :star:292
- [ESP8266 Beacon Spam](https://github.com/spacehuhn/esp8266_beaconSpam) - Want to confuse people? This device creates hundreds of fake WiFi networks. :star:446
- [DeauthDetector](https://github.com/spacehuhn/DeauthDetector) - A small device that shines a light if it detects a WiFi deauth attack. Made by the same guy as the last six projects. :star:315
### Biomedical
- [HeartyPatch](https://heartypatch.protocentral.com/) - A wearable BLE and WiFi connected ECG-HR patch which uses the ESP32.
- [HealthyPi v4](https://www.crowdsupply.com/protocentral/healthypi-v4-unplugged) - An amazing open source vital signs monitor that can monitor ECG, respiration, pulse oximetry and body temperature, all run by an ESP32.
### Others
- [SoftRF](https://github.com/lyusupov/SoftRF) - A DIY aviation proximity awareness system that can be used in UAV projects. :star:201
- [Retro ESP32](https://github.com/retro-esp32/RetroESP32) - An extremely cool launcher for the Odroid Go (with the ESP32), which allows emulating several retro consoles. :star:164
- [PedalinoMini](https://github.com/alf45tar/PedalinoMini) - A wireless MIDI pedal controller for guitarists, built with the ESP32. :star:49
- [StickWatch](https://github.com/eggfly/StickWatch) - A smartwatch module based on the M5Stick, using the ESP32. :star:57
- [DroneBridge](https://github.com/DroneBridge/ESP32) - An implementation of DroneBridge, a signal link for drones and UAV's on the ESP32. :star:26
## Libraries
- [Wasm3](https://github.com/wasm3/wasm3) - A lightning fast WebAssembly interpreter designed for embedded devices, compatible with both ESP's. :star:1811
- [Homie8266](https://github.com/marvinroger/homie-esp8266) - Framework implementation of the Homie protocol for the 8266. :star:1114
- [ESP-Dash](https://github.com/ayushsharma82/ESP-DASH) - Beautiful and fast framework for creating remote dashboards in the 8266/32. No internet required. :star:346
- [ESP_mqtt](https://github.com/tuanpmt/esp_mqtt) - MQTT helper library for the ESP8266. :star:1005
- [GUIslice](https://github.com/ImpulseAdventure/GUIslice) - A drag and drop GUI framework for several devices and screen controllers. Compatible with 8266 and 32. :star:289
- [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) - A very powerful MicroPython web server which can be used in the ESP32. :star:84
- [IRremoteESP8266](https://github.com/markszabo/IRremoteESP8266) - Emit and receive IR signals in the ESP8266. :star:1267
- [esphomelib](https://github.com/OttoWinter/esphomelib) - Framework to integrate with HomeAssistant in the 8266. :star:552
- [TTS](https://github.com/jscrane/TTS) - A somehow good text to speech library for several Arduino devices, both ESP's included. :star:94
- [Free802.11](https://github.com/Jeija/esp32free80211) - Library to emit arbitrary 802.11 signals with the ESP32. :star:305
- [Koyn](https://github.com/elkrem/koyn) - A decentralized Bitcoin library for the ESP32 and the ESP8266. :star:50
- [TFTLibrary](https://github.com/loboris/ESP32_TFT_library) - TFT compatibility for the ESP32. :star:299
- [UTFT-ESP](https://github.com/gnulabis/UTFT-ESP) - UTFT Support for the ESP32/8266. :star:76
- [ESPAudio](https://github.com/earlephilhower/ESP8266Audio) - Library for playing a diverse range of audio formats in the ESP8266/ESP32. :star:633
- [AsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP) - Asynchronous TCP Library for both the 8266 and the 32. :star:391
- [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) - Homekit implementation for 8266 on RTOS. :star:452
- [ESPHelper](https://github.com/ItKindaWorks/ESPHelper) - MQTT and Wi-fi automation-oriented library for the 8266. :star:286
- [ESPHelper/32](https://github.com/ItKindaWorks/ESPHelper32) - Port of the ESPHelper library for the 32. :star:53
- [ESP8266Wifi](https://github.com/ekstrand/ESP8266wifi) - Simple Arduino Wifi library for the 8266. :star:375
- [WiFiESP](https://github.com/bportaluri/WiFiEsp) - Arduino library for Wifi management, client/server for 8266 board. :star:359
- [TinyGSM](https://github.com/vshymanskyy/TinyGSM) - A quick and simple Arduino library for interaction with GSM modules which can also control the 8266 through AT commands. :star:906
- [mJS](https://github.com/cesanta/mjs) - A lightweight and restricted JS engine that is used by MongooseOS, compatible on the 32 and 8266. :star:1224
- [ESPUI](https://github.com/s00500/ESPUI) - A simply library for making interactive web interfaces for both ESP's. :star:186
- [ESP32 ePaper](https://github.com/loboris/ESP32_ePaper_example) - A full-featured library for using ePaper modules with the ESP32. :star:113
- [TinyUPnP](https://github.com/ofekp/TinyUPnP) - A lightweight UPnP IGD library for automatic port forwarding on the 8266 and 32. :star:46
- [Esp32SSHClient](https://github.com/J-Rios/Arduino-esp32sshclient) - A library that implements a SSH client in the ESP32. :star:10



