# Information comes from [hobbyquaker/awesome-homematic](https://github.com/hobbyquaker/awesome-homematic)
# Awesome Homematic [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Homematic related links

[Homematic](http://www.homematic.com/) is a series of Smart Home devices from the german manufacturer [eQ-3](http://www.eq-3.de). 


## Contents

- [Community](#community)
- [Documentation](#documentation)
- [Mobile Apps](#mobile-apps)
- [CCU Alternatives](#ccu-alternatives)
- [Alternative Sensors and Actuators](#alternative-sensors-and-actuators)
- [CCU Addons](#ccu-addons)
- [Interfacing Software](#interfacing-software)
- [Misc Software](#misc-software)
- [Software Modules](#software-modules)
- [Generic Smart Home Software](#generic-smart-home-software)
- [License](License)


## Community 

* [Homematic Forum](https://homematic-forum.de/) - Discussion Forums.
* [Homematic Forum Link/Skript-Sammlung](https://homematic-forum.de/forum/viewtopic.php?f=26&t=27907) - Curated link list by AndiN.
* [Homematic Inside](https://www.homematic-inside.de/) - News, Blog and more.
* [Wikimatic](http://www.wikimatic.de/wiki/Hauptseite) - Community Wiki.


## Documentation

* [Dissecting HomeMatic AES](https://git.zerfleddert.de/hmcfgusb/AES/) - BidCos Protocol AES Handshake description.
* [Expert Parameters](https://www.homematic-inside.de/software/download/item/vortrag-expertenparameter-2017) - "Expert Parameters" and Virtual Channels for Direct Links (download links at the bottom of the page).
* [Script Documentation](http://www.wikimatic.de/wiki/Script_Dokumentation) - Inofficial Homematic Script Reference.


## Mobile Apps

* [Home-24](http://www.home-24.net/index.php?page=sites/home.php&app=home24) - **$** Android 
* [HomeControl](http://www.ksquare.de/myhomecontrol/) - **$** iOS
* [TinyMatic](http://tinymatic.de/) - **$** Android (formerly named HomeDroid)
* [HomeNOW](http://homenow.at) - **$** Android
* [Orbylon](https://www.orbylon.de/orbylon) - **$** iOS, Android, Windows Phone
* [Pocket Control](https://www.penzler.de) - **$** iOS


## CCU Alternatives

* [Anleitung zur Installation der CCU auf einem x86 system](https://homematic-forum.de/forum/viewtopic.php?t=39240) - HowTo install the CCU software on x86 systems (German).
* [dccu](https://github.com/litti/dccu2) - CCU docker image (x86). :star:3
<!-- * [Hmcon](https://github.com/hobbyquaker/hmcon) - Homematic Interface and Configuration. -->
* [Homegear](https://www.homegear.eu/index.php/Main_Page) - Free and open source program to interface your smart home devices with your home automation software or your own scripts.
* [piVCCU](https://github.com/alexreinert/piVCCU) - Install the original Homematic CCU2 firmware inside a virtualized container (lxc) on a Raspberry Pi running Raspbian Jessie or Stretch. :star:36
* [RaspberryMatic](https://github.com/jens-maus/RaspberryMatic) - Lightweight, Linux/buildroot-based distribution for running a HomeMatic CCU on embedded devices like the RaspberryPi. :star:215
* [YAHM](https://github.com/leonsio/YAHM) - Setup Scripts to run the CCU software in a LXC Container. :star:100


## Alternative Sensors and Actuators

* [Asksin_HM_LC_Sw1PBU_FM](https://github.com/jabdoa2/Asksin_HM_LC_Sw1PBU_FM) - Alternative Open Source Firmware for HM_LC_Sw1PBU_FM. :star:16
* [HAUS-BUS.DE](http://www.haus-bus.de/) - **$** Homematic Wired compatible Devices.
* [Homematic Wired Hombrew Hardware](https://github.com/jfische) - Several Homebrew Sensors/Actuators for Homematic Wired.
* [NewAskSin](https://github.com/trilu2000/NewAskSin) - Arduino-Library to create Homematic RF (BidCoS) compatible Devices. :star:24
* [WIFFI-WZ](https://www.stall.biz/project/der-wiffi-wz-2-0-der-wohnzimmersensor) - **$** Multi Sensor for the living room.


## CCU Addons

* [CUxD](https://www.homematic-inside.de/software/cuxdaemon) - The "Leatherman" for the CCU. Connects FS20, ... (**$** EnOcean, ...)
* [CUxD-Highcharts](https://github.com/hobbyquaker/cuxd-highcharts) - Visualize CUxD Logs with Highcharts. :star:7
* [Email](https://github.com/jens-maus/hm_email) - HomeMatic CCU Addon for sending Emails. :star:15
* [Hm-print](https://github.com/litti/hm-print) - Print CCU Programs. :star:5
* [Homeputer](https://www.contronics.de/shop/HomeMatic-System/Zentralen-und-Software.html) - **$**
* [Homematic-addon-hue](https://github.com/j-a-n/homematic-addon-hue) - HomeMatic addon to control Philips Hue Lighting. :star:12
* [homematic_check_mk](https://github.com/alexreinert/homematic_check_mk) - Addon for the Homematic CCU2 or a Raspberrymatic device which acts as an check_mk_agent. :star:5
* [HQ-WebUI](https://github.com/hobbyquaker/hq-webui) - Fast alternative WebUI for the Homematic CCU. :star:23
* [WebMatic](http://webmatic.lmdsoft.de/tiki-index.php) - WebUI for the Homematic CCU.
* [XML-API](https://github.com/hobbyquaker/xml-api) - Simplified CCU Access via HTTP/XML. :star:31


## Interfacing Software

* [Homebridge-homematic](https://github.com/thkl/homebridge-homematic) - Supports the Homematic System on [HomeBridge](https://github.com/nfarina/homebridge) Platform. :star:76
* [Homematic-Virtual-Interface](https://github.com/thkl/Homematic-Virtual-Interface) - Virtual Interface for Homematic CCU with plugins to connect other devices to your CCU (e.g. Philips Hue). :star:17
* [Hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js) - Interface between Homematic and MQTT. :star:14
* [Hmcompanion](https://github.com/owagner/hmcompanion) - Generic telnet based interface. :star:12
* [Node-red-contrib-homematic](https://github.com/firsttris/node-red-contrib-homematic) - Integrate your Homematic devices with [Node-RED](https://nodered.org). :star:10


## Misc Software

* [CCU Historian](http://www.ccu-historian.de/) - Long term archive and graphing solution.
* [Check_homematic](https://github.com/hobbyquaker/check_homematic) - Nagios/Icinga Plugin for checking Homematic CCU. :star:1
* [Hm-simulator](https://github.com/hobbyquaker/hm-simulator) - Simulates (partly) a Homematic CCU.
* [HMXMLBIN](https://github.com/leonsio/HMXMLBIN) - Converter between BINRPC and XMLRPC. :star:4
* [Homematic-manager](https://github.com/hobbyquaker/homematic-manager) - Manage homematic interface processes (rfd/hs485d/homegear). :star:59
* [Language-homematic](https://github.com/Ayngush/language-homematic) - Adds syntax highlighting and snippets to HomeMatic Script files in Atom. :star:2
* [occu-test](https://github.com/hobbyquaker/occu-test) - Automated System Tests of ReGaHss - the HomeMatic (O)CCU "Logic Layer". :star:2

## Software Modules

* [Binrpc](https://github.com/hobbyquaker/binrpc) - Xmlrpc_bin protocol client and server Node.js module. :star:7
* [Hmcfgusb](https://git.zerfleddert.de/cgi-bin/gitweb.cgi/hmcfgusb) - Utilities to use the HM-CFG-USB(2) on Linux/Unix.
* [Homematic-rega](https://github.com/hobbyquaker/homematic-rega) - Node.js Homematic CCU ReGaHSS Remote Script Interface.
* [Homematicip-rest-api](https://github.com/coreGreenberet/homematicip-rest-api) - Python wrapper for the homematicIP REST API (Cloud / Access Point Based). :star:33
* [Homematic-xmlrpc](https://github.com/hobbyquaker/homematic-xmlrpc) - Xmlrpc client and server Node.js module. :star:2
* [Pmatic](https://github.com/LarsMichelsen/pmatic) - Python API for Homematic. Easy to use. :star:22
* [Pyhomematic](https://github.com/danielperna84/pyhomematic) - Python 3 Interface to interact with Homematic devices. :star:31

## Generic Smart Home Software

These smart home software solutions support Homematic:

* [FHEM](https://fhem.de/)
* [Home Assistant](https://home-assistant.io/)
* [ioBroker](http://www.iobroker.net/?lang=de)
* [IP-Symcon](https://www.symcon.de/) - **$**
* [Mediola](http://www.mediola.com/) - **$**
* [OpenHAB](https://www.openhab.org/)
* [Pimatic](https://pimatic.org/)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[Public Domain CC0](http://creativecommons.org/publicdomain/zero/1.0/)

