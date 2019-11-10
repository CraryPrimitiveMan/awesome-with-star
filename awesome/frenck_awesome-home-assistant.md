# Information comes from [frenck/awesome-home-assistant](https://github.com/frenck/awesome-home-assistant)
# Awesome Home Assistant [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

<div align="center">
  <a href="https://awesome-ha.com">
    <img width="400" src="https://www.awesome-ha.com/images/awesome-home-assistant.svg" alt="Awesome Home Assistant">
  </a>
  <br>
  <a href="https://awesome-ha.com"><strong>https://awesome-ha.com</strong></a>
</div>

Home Assistant is an open source home automation that puts local control and
privacy first. Powered by a worldwide community of tinkerers and DIY
enthusiasts. Perfect to run on a Raspberry Pi or a local server.

If you want to get an impression on the look and feel,
you should check out the [Home Assistant online demo](https://demo.home-assistant.io).

Awesome Home Assistant is a curated list of awesome
[Home Assistant](https://www.home-assistant.io) resources.
Additional software, tutorials, custom components, Hassio add-ons,
custom Lovelace panels, cookbooks, example setups, and much more.

The list is divided into categories. The links in those categories do not have
pre-established order; the order is for contribution. If you want to contribute,
please read the [guide](https://github.com/frenck/awesome-home-assistant/blob/master/CONTRIBUTING.md).

## Contents

- [How to use](#how-to-use)
- [Installing](#installing)
- [In case you need help](#in-case-you-need-help)
  - [Official Channels](#official-channels)
  - [Other Channels](#other-channels)
- [Public Configurations](#public-configurations)
- [Hass.io](#hassio)
  - [Official Add-ons](#official-add-ons)
  - [Third Party Add-ons](#third-party-add-ons)
- [Lovelace User Interface](#lovelace-user-interface)
  - [Themes](#themes)
  - [Custom Lovelace UI Cards](#custom-lovelace-ui-cards)
  - [Alternative Dashboards](#alternative-dashboards)
- [Custom Components](#custom-components)
- [DIY](#diy)
  - [DIY Gateways](#diy-gateways)
  - [DIY Projects](#diy-projects)
- [Online Resources](#online-resources)
  - [Blogs](#blogs)
  - [YouTube Channels](#youtube-channels)
  - [Podcasts](#podcasts)
  - [Twitter](#twitter)
- [Uncategorized](#uncategorized)
- [Alternative Home Automation Software](#alternative-home-automation-software)
- [Other Awesome Lists](#other-awesome-lists)
- [Trademark Legal Notice](#trademark-legal-notice)

## How to use

Awesome Home Assistant is a fantastic list for people trying to automate every
aspect of their home. Automating your home is a long, hard, and never finished
task that usually involves a lot of tinkering.

You can navigate through the list by:

- Simply press <kbd>command/ctrl</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our [_Contents list_](#contents)
- Alternatively, use the search on our website: <https://www.awesome-ha.com>

## Installing

Home Assistant has several installation / running methods. Many people have
different opinions and their personal favorites. Each method has its
advantages and disadvantages. Important to know, there is no wrong, or right here,
each technique installs the **SAME** Home Assistant.

Home Assistant currently _recommends_ the Hass.io method.

- [Hass.io](https://www.home-assistant.io/getting-started/) - Installing using a Docker managed environment (recommended method).
- [Docker](https://www.home-assistant.io/docs/installation/docker/) - Installing on Docker.
- [Hassbian](https://www.home-assistant.io/docs/installation/hassbian/installation/) - Installing Hassbian.
- [Manually](https://www.home-assistant.io/docs/installation/virtualenv/) - Manual installation using a Python virtual environment.

## In case you need help

_There are various ways to get in touch with the Home Assistant community.
It doesn’t matter if you have a question, need help, want to request a feature,
or just say ‘Hi’._

### Official Channels

- [Home Assistant Discord](https://discordapp.com/invite/c5DvZ4e) - Join the chat, most of us are there.
- [Home Assistant Community](https://community.home-assistant.io/?u=frenck) - The discussion forum, also used for feature requests.
- [Home Assistant Subreddit](https://www.reddit.com/r/homeassistant/) - If you are into Reddit, subscribe.
- [Home Assistant Enthusiasts](https://www.facebook.com/groups/HomeAssistant/) - Facebook group for enthusiasts.

### Other Channels

- [Dr. ZZs](https://www.facebook.com/groups/1969622823351838/) - Facebook group by Dr. Zzs.
- [Community Hassio Add-ons Discord](https://discord.me/hassioaddons) - Get support on the Community Hassio Add-ons.
- [ESPHome Discord](https://discord.gg/KhAMKrd) - Get support for your DIY ESPHome project.

## Public Configurations

_Some people store their full Home Assistant configuration on GitHub. They are
an awesome source for learning and a great source of inspiration._

- [Carlo Costanzo](https://github.com/CCOSTAN/Home-AssistantConfig#logo) - Probably the most documented configuration out there. :star:2328
- [DubhAd](https://github.com/DubhAd/Home-AssistantConfig) - Also known as Tinkerer shares his configuration files. :star:179
- [geekofweek](https://github.com/geekofweek/homeassistant) - Has over 300+ automations. :star:560
- [Isabella Gross Alström](https://github.com/isabellaalstrom/home-assistant-config) - Hass.io, Intel NUC, Ubuntu, Docker, Lovelace UI. :star:104
- [Mahasri Kalavala](https://github.com/skalavala/mysmarthome) - Impressive setup, with lots of different hardware working together. :star:52
- [stanvx](https://github.com/stanvx/Home-Assistant-Configuration) - Complete setup which uses AppDaemon and HA Floorplan as well. :star:365
- [Vasiley](https://github.com/Vasiley/Home-Assistant-Main) - Runs two instances that work together. :star:87
- [Alok Saboo](https://github.com/arsaboo/homeassistant-config) - Also known as arsaboo. Regularly updated. :star:974
- [Aaron Bach](https://github.com/bachya/smart-home) - Also known as bachya. Regularly updated and includes numerous Dockerized services. :star:140
- [James McCarthy](https://github.com/JamesMcCarthy79/Home-Assistant-Config) - Well documented, 3 instances & automations in YAML & Node-RED. :star:769
- [Franck Nijhof](https://github.com/frenck/home-assistant-config) - Hass.io based, very different configuration structure compared to others. :star:463
- [Andrea Donno](https://github.com/adonno/Home-AssistantConfig) - Hass.io based, focused on touchscreen usage. :star:86
- [Klaas Schoute](https://github.com/klaasnicolaas/Smarthome-homeassistant-config) - Hass.io based, Intel NUC, Ubuntu Server, Docker and regularly updated. :star:91
- [Jason Hunter](https://github.com/hunterjm/home-assistant-config) - Hass.io based, Intel NUC i5, TensorFlow & camera streams. :star:16

## Hass.io

_Hass.io is a complete operating system that will take care of installing and
updating Home Assistant, and is managed from the frontend._

- 📺 [Hass.io Beginner's Guide](https://www.youtube.com/watch?v=qnCRcGTznXs) - Excellent step-by-step guide on getting started (based on HassOS).

### Official Add-ons

_Add-ons are easily installable services that extend the functionality around
your Hass.io instance._

- [DuckDNS](https://www.home-assistant.io/addons/duckdns/) - Updates your Duck DNS IP address and generate SSL using Let's Encrypt.
- [HASS Configurator](https://github.com/home-assistant/hassio-addons/tree/master/configurator) - Browser-based configuration file editor. :star:150
- [Mosquitto](https://www.home-assistant.io/addons/mosquitto/) - Fast and reliable MQTT broker.
- [SSH Server](https://www.home-assistant.io/addons/ssh/) - Allows logging in remotely to using SSH.
- [Samba](https://www.home-assistant.io/addons/samba/) - Access your configuration files using Windows network shares.
- [NGINX SSL proxy](https://www.home-assistant.io/addons/nginx_proxy/) - Reverse proxy with SSL termination.
- [deCONZ](https://github.com/home-assistant/hassio-addons/tree/master/deconz) - Control a ZigBee network using ConBee or RaspBee hardware by Dresden Elektronik. :star:150
- [TellStick](https://github.com/home-assistant/hassio-addons/tree/master/tellstick) - Run a TellStick and TellStick Duo service. :star:150

### Third Party Add-ons

_Anyone could create an add-on, the following are created by the community._

- [SSH & Web Terminal](https://github.com/hassio-addons/addon-ssh) - SSH and Web-based terminal with tons of pre-loaded useful tools. :star:41
- [Pi-hole](https://github.com/hassio-addons/addon-pi-hole) - Network-wide ad blocking. :star:102
- [UniFi Controller](https://github.com/hassio-addons/addon-unifi) - The UniFi Controller allows you to manage your UniFi network using a web browser. :star:36
- [Node-RED](https://github.com/hassio-addons/addon-node-red) - Flow-based programming for the Internet of Things. :star:86
- [Plex Media Server](https://github.com/hassio-addons/addon-plex) - Your recorded media beautifully organized and ready to stream. :star:25
- [IDE](https://github.com/hassio-addons/addon-ide) - Advanced web-based IDE, based on Cloud9 IDE. :star:57
- [Dasshio](https://github.com/danimtb/dasshio) - Easily use your Amazon Dash Buttons. :star:113
- [InfluxDB](https://github.com/hassio-addons/addon-influxdb) - Scalable datastore for metrics, events, and real-time analytics. :star:39
- [Grafana](https://github.com/hassio-addons/addon-grafana) - Open platform for beautiful analytics and monitoring. :star:52
- [Tor](https://github.com/hassio-addons/addon-tor) - Protect your privacy and access your instance via Tor. :star:14
- [Spotify Connect](https://github.com/hassio-addons/addon-spotify-connect) - Spotify Connect client for playing music on your Home Assistant device. :star:27
- [zigbee2mqtt](https://github.com/danielwelch/hassio-zigbee2mqtt) - Zigbee to MQTT bridge, get rid of your proprietary Zigbee bridges. :star:250
- [AppDaemon3](https://github.com/hassio-addons/addon-appdaemon3) - Python Apps and HADashboard. :star:39
- [TasmoAdmin](https://github.com/hassio-addons/addon-tasmoadmin) - Centrally manage all your Sonoff-Tasmota devices. :star:76
- [Aircast](https://github.com/hassio-addons/addon-aircast) - AirPlay capabilities for your Chromecast players. :star:46
- [AirSonos](https://github.com/hassio-addons/addon-airsonos) - AirPlay capabilities for your Sonos players. :star:21
- [Dropbox Sync](https://github.com/danielwelch/hassio-dropbox-sync) - Upload your backup snapshots to Dropbox. :star:66
- [Log Viewer](https://github.com/hassio-addons/addon-log-viewer) - Browser-based live log viewing utility. :star:17
- [Tautulli](https://github.com/hassio-addons/addon-tautulli) - Monitor and get statistics from your Plex server. :star:10
- [motionEye](https://github.com/hassio-addons/addon-motioneye) - Simple, elegant and feature-rich CCTV/NVR for your cameras. :star:52
- [JupyterLab Lite](https://github.com/hassio-addons/addon-jupyterlab-lite) - Create documents containing live code, equations, visualizations, and explanatory text. :star:16
- [Backup to Google Drive](https://github.com/samccauley/addon-hassiogooglebackup) - Backup snapshots to Google Drive. :star:56
- [ADB](https://github.com/hassio-addons/addon-adb) - The Android Debug Bridge server program. :star:41
- [Glances](https://github.com/hassio-addons/addon-glances) - A cross-platform system monitoring tool written in Python. :star:25
- [Matrix](https://github.com/hassio-addons/addon-matrix) - A secure and decentralized communication platform. :star:8
- [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home) - A network-wide ad-and-tracker blocking DNS server with parental control. :star:23
- [Traccar](https://github.com/hassio-addons/addon-traccar) - Traccar is modern GPS Tracking Platform. :star:20
- [Home Panel](https://github.com/hassio-addons/addon-home-panel) - A touch-compatible web frontend for controlling the home. :star:58
- [Hass.io Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup) - A complete and easy to configure solution for backing up your snapshots to Google Drive. :star:479
- [Grocy](https://github.com/hassio-addons/addon-grocy) - ERP beyond your fridge! A groceries & household management solution for your home. :star:39

## Lovelace User Interface

_The Home Assistant frontend is already pretty, but you can customize it to
fit your needs or taste better._

- [Lovelace UI Documentation](https://www.home-assistant.io/lovelace) - The official documentation.
- 📺 [Getting started with Lovelace UI](https://www.youtube.com/watch?v=ObfRzMIEJPgx) - Great introduction to Lovelace UI by DrZzs.
- [Plan Coordinates](https://github.com/ciotlosm/custom-lovelace/tree/master/plan-coordinates) - Helps to find left and top values for `picture-elements` cards. :star:543
- [Share the Love](https://sharethelove.io) - Custom card demos and configuration examples for Lovelace.
- 📺 [How to set up Lovelace](https://www.youtube.com/watch?v=n5xMtONydEo) - Excellent step by step video for beginners by JuanMTech.
- [Font Awesome Icons](https://github.com/thomasloven/hass-fontawesome) - Use the free icons from Font Awesome in your frontend. :star:66

### Themes

_It is all about the looks, apply some style._

- 📺 [Themes Tutorial](https://www.youtube.com/watch?v=h1h8FFy9_Co) - Quick tutorial/example on how to configure themes.
- [Midnight](https://community.home-assistant.io/t/midnight-theme/28598?u=frenck) - A dark theme by Marcel Hoffs.
- [Dark Cyan](https://community.home-assistant.io/t/dark-cyan-theme/28594?u=frenck) - A dark theme with cyan accents by Ryoen Deprouw.
- [Grey Night](https://community.home-assistant.io/t/grey-night-theme/30848?u=frenck) - A dark theme with grey accents by ksya.
- [Dark Red](https://community.home-assistant.io/t/dark-red-theme/28592?u=frenck) - A dark theme with red accents by Ryoen Deprouw.
- [Halloween](https://community.home-assistant.io/t/halloween-theme/30872?u=frenck) - Pumpkins colored by Mahasri Kalavala.
- [Black and Green](https://community.home-assistant.io/t/black-and-green-theme/28602?u=frenck) - A dark theme with pale green accents by GreenTurtwig.
- [Vintage](https://community.home-assistant.io/t/vintage-theme/42806?u=frenck) - Give your frontend a vintage look with this theme by Anup Surendran.
- [Carbon Green](https://community.home-assistant.io/t/share-your-themes/22018/95?u=frenck) - Light carbon theme with green accents by Reua.
- [20 Great Themes](https://www.juanmtech.com/themes-in-home-assistant/) - 20 Great themes by JuanMTech (includes a guide).
- [Many Themes, One Repo](https://github.com/maartenpaauw/home-assistant-community-themes/) - 13 Themes in a convenient ZIP file. :star:130
- [Slate](https://github.com/seangreen2/slate_theme) - A dark theme close to the vanila looks from seangreen2. :star:23
- [Synthwave](https://github.com/bbbenji/synthwave-hass) - A theme influenced by the cover artwork of modern Synthwave bands. :star:44
- [Google Home Theme](https://github.com/liri/lovelace-themes) - Two themes (light and dark) matching the design of Google Home Hub. :star:25

### Custom Lovelace UI Cards

_Lovelace allows people to build custom cards on top of it, which you can
easily add to your instance._

- [Monster Card](https://github.com/ciotlosm/custom-lovelace/tree/master/monster-card) - Dynamically adds entities: 🔮 Magic. :star:543
- [Canvas Gauge Card](https://github.com/custom-cards/canvas-gauge-card) - Use awesome gauges from canvas-gauges.com. :star:36
- [Alarm Control Panel Card](https://github.com/ciotlosm/custom-lovelace/tree/master/alarm_control_panel-card) - Card that looks like an alarm keypad. :star:543
- [Big Number Card](https://github.com/ciotlosm/custom-lovelace/tree/master/bignumber-card) - Display big numbers for sensors, including severity level as background. :star:543
- [Animated Weather Card](https://github.com/bramkragten/custom-ui/blob/master/weather-card/README.md) - Nice looking card showing the weather, with subtle animations. :star:156
- [Thermostat Card](https://github.com/ciotlosm/custom-lovelace/tree/master/thermostat-card) - Thermostat control card that looks like a Nest Thermostat. :star:543
- [Mini Media Player](https://github.com/kalkih/mini-media-player) - A minimalistic media player card. :star:447
- [Mini Graph Card](https://github.com/kalkih/mini-graph-card) - A minimalistic sensor graph card. :star:521
- [Button card](https://github.com/kuuji/button-card) - Button card for your entities. :star:278
- [Slideshow card](https://github.com/zsarnett/slideshow-card) - Dynamic slideshow of images or cards. :star:13
- [Swiper card](https://community.home-assistant.io/t/lovelace-swiper-card/72447?u=frenck) - Flick/swipe through multiple cards.
- [Slider Entity Row](https://github.com/thomasloven/lovelace-slider-entity-row) - Add a slider to adjust, e.g., the brightness of lights in lovelace entity cards. :star:212
- [Power Wheel Card](https://github.com/gurbyz/power-wheel-card) - An intuitive way to represent the power that your home is consuming or producing. :star:30
- [Simple Thermostat](https://github.com/nervetattoo/simple-thermostat) - A simpler and more flexible thermostat card. :star:151
- [Compact Custom Header](https://github.com/maykar/compact-custom-header) - Customize and compact the frontend header bar. :star:244
- [Card Modder](https://github.com/thomasloven/lovelace-card-modder) - Style your Lovelace cards. :star:94
- [Bar Card](https://github.com/Gluwc/bar-card) - Customizable animated bar card. :star:65
- [Calendar Card](https://github.com/rdehuyss/homeassistant-lovelace-google-calendar-card) - A nice Google calendar card. :star:92
- [forked-daapd Card](https://github.com/kalkih/forked-daapd-card) - Control a forked daapd instance. :star:31
- [Dual Gauge Card](https://github.com/Rocka84/dual-gauge-card) - Shows two gauges in one. :star:34
- [Atomic Calendar Card](https://github.com/atomic7777/atomic_calendar) - Calendar card with advanced settings. :star:63
- [Xiaomi Vacuum Card](https://github.com/benct/lovelace-xiaomi-vacuum-card) - Detailed card for Xiaomi vacuum cleaners (and others). :star:38
- [Simple Weather Card](https://github.com/kalkih/simple-weather-card) - A minimalistic weather card, inspired by Google Material Design. :star:54
- [Lovelace Floorplan](https://github.com/pkozul/lovelace-floorplan) - Interaction with your entities from a Floorplan. :star:94
- [Home Card](https://github.com/postlund/home-card) - A quick glance of the state of your home. :star:57
- [Banner Card](https://github.com/nervetattoo/banner-card) - A fluffy linkable banner with interactive glances to spice up your home dashboards. :star:115
- [Upcoming Media Card](https://github.com/custom-cards/upcoming-media-card) - Display upcoming episodes and movies from services like: Plex, Kodi, Radarr, Sonarr, and Trakt. :star:85
- [Spotify Card](https://github.com/custom-cards/spotify-card) - List and select from current available devices and users top playlists on Spotify. :star:64
- [Battery Entity](https://github.com/cbulock/lovelace-battery-entity) - Displaying battery levels for battery entities. :star:50
- [Multiple Entity Row](https://github.com/benct/lovelace-multiple-entity-row) - Show multiple entity states or attributes on entity rows. :star:44
- [Toggle Lock Entity Row](https://github.com/thomasloven/lovelace-toggle-lock-entity-row) - Display a toggle with a lock, avoiding toggling it by mistake. :star:55
- [Xiaomi Vacuum Map Card](https://github.com/PiotrMachowski/Home-Assistant-Lovelace-Xiaomi-Vacuum-Map-card) - Interactive Xiaomi Vacuum map, just like in Mi Home app. :star:102
- [Home Feed Card](https://github.com/gadgetchnnel/lovelace-home-feed-card) - Display a combination of persistent notifications, calendar events, and entities in the style of a feed. :star:48
- [Config Template Card](https://github.com/custom-cards/config-template-card) - Allow using templates in Lovelace. :star:62

### Alternative Dashboards

- [TileBoard](https://github.com/resoai/TileBoard) - A simple yet highly configurable Dashboard. :star:596

## Custom Components

_Additional components for Home Assistant, that were created by the community._

- [Hue Sensors](https://github.com/robmarkcole/Hue-sensors-HASS) - Enables the use of Philips Hue sensors. :star:294
- [Google Geocode](https://github.com/michaelmcarthur/GoogleGeocode-HASS) - Converts a device tracker location into a human-readable address. :star:80
- [Lutron Caseta Pro](https://github.com/upsert/lutron-caseta-pro) - Integrates Lutron Caseta Smart Bridge PRO / RA2 Select. :star:83
- [SmartIR](https://github.com/smartHomeHub/SmartIR) - Integrates devices using Broadlink IR. :star:275
- [Xiaomi Hygrothermo](https://github.com/dolezsa/Xiaomi_Hygrothermo) - Sensor platform for Xiaomi Mijia BT Hygrothermo temperature and humidity sensor. :star:70
- [Volkswagen Carnet](https://github.com/robinostlund/homeassistant-volkswagencarnet) - Integrates Volkswagen Carnet (requires valid Carnet subscription). :star:50
- [Untappd](https://github.com/custom-components/sensor.untapped) - Connects with your Untappd account. :star:15
- [Elasticsearch](https://github.com/legrego/homeassistant-elasticsearch) - Publishes events to Elasticsearch. :star:29
- [Sonoff/eWeLink](https://github.com/peterbuga/HASS-sonoff-ewelink) - Control Sonoff/eWeLink smart devices using the stock firmware. :star:370
- [Alexa Media Player](https://github.com/keatontaylor/alexa_media_player) - Allow control of Amazon Alexa devices. :star:339
- [iCloud3](https://github.com/gcobb321/icloud3) - Improved version of the iCloud device tracker component with a lot of capabilities. :star:82
- [HACS](https://hacs.netlify.com/) - This is a manager for your custom integration (components) and plugin (lovelace elements) needs.
- [breaking_changes](https://github.com/custom-components/breaking_changes) - Component to show potential breaking_changes in the current published version based on your loaded components. :star:29
- [Circadian Lighting](https://github.com/claytonjn/hass-circadian_lighting) - Circadian Lighting slowly synchronizes your color changing lights with the regular naturally occuring color temperature of the sky throughout the day. :star:99
- [HASS Aarlo](https://github.com/twrecked/hass-aarlo) - Asynchronous Arlo integration. Similar to the Arlo web site; monitors events and states for all base stations, cameras and doorbells. :star:62

## DIY

_Do It Yourself; rather than buying home automation hardware or solutions, you
could also build them yourself!_

- [ESPHome](https://esphome.io/) - Program ESP8266 boards and ESP32 boards using YAML.
- [Magic Cards](https://github.com/maddox/magic-cards) - RFID scannable cards that you can program to do anything. :star:252
- [Sonoff Tasmota](https://github.com/arendst/Sonoff-Tasmota) - Firmware for ESP8266 boards and devices. :star:8341

### DIY Gateways

- [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) - A flexible MQTT gateway for IR, RF, BLE, MiFlora, SMS, and many sensors. :star:1309
- [esp8266 Milight Hub](https://github.com/sidoh/esp8266_milight_hub) - Alternative hub for Milight/LimitlessLED devices that uses MQTT. :star:506
- [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) - Zigbee to MQTT bridge, get rid of your proprietary Zigbee bridges. :star:3109

### DIY Projects

- [HA SwitchPlate](https://community.home-assistant.io/t/ha-switchplate-diy-lcd-touchscreen-wall-switch-replacement/25464?u=frenck) - LCD Touchscreen wall switch replacement.
- 📺 [DIY Multisensor](https://www.youtube.com/watch?v=jpjfVc-9IrQ) - $15, Temperature, Humidity, Light, Motion, and RGB LED, without soldering.
- [$10 WiFi RGB Bulb](https://community.home-assistant.io/t/how-to-inexpensive-10-us-wifi-rgb-bulb-that-works-with-home-assistant/14735?u=frenck) - In inexpensive RGB bulb that works on WiFi.
- [433mhz/IR Bidirectional Gateway](https://community.home-assistant.io/t/433mhz-infrared-ir-to-and-from-mqtt-on-esp8266/6779?u=frenck) - Bidirectional with IR and 433mhz using ESP8266 and MQTT.
- [esp8266MQTTBlinds](https://community.home-assistant.io/t/esp8266-window-blinds-mqtt/14863?u=frenck) - Automate your window blinds using an ESP8266, a servo and MQTT.
- [Home Assistant's Hackster.io](https://www.hackster.io/home-assistant?f=1#_=_) - A Hackster channel with multiple DIY projects.
- [ESP MQTT Digital LEDs](https://github.com/bruhautomation/ESP-MQTT-JSON-Digital-LEDs) - WS2811 LED Stripe for the JSON Light Component from BRUH. :star:449
- [Bed Presence Detection](https://selfhostedhome.com/diy-bed-presence-detection-home-assistant/) - ESP8266 based Bed Presence Detection.
- [NFC Scanner](https://github.com/klaasnicolaas/ha_nfc_scanner) - Build an NFC tag/card scanner with an ESP8266, PN532 and MQTT. :star:28
- [ESP32-Cam Facebox](https://www.dopebuild.com/i-am-sorry-dave-i-am-unable-to-do-that/) - Tie a ESP32-CAM, HA, and Facebox together for a cheap Facial Recog / Home monitoring solution.
- [RaspiPool](https://github.com/segalion/raspipool) - A cost-effective, easy-to-build, easy-to-use "Swimming-Pool Automation System". :star:53

## Online Resources

_Links to various users of Home Assistant that regularly publish Home Assistant focussed content._

### Blogs

- [DIY Futurism](https://diyfuturism.com/) - Brad posts articles with great instructions for new users.
- [Phil Hawthorne](https://philhawthorne.com/homeautomation) - Co-host of the Home Assistant Podcast.
- [Smart Home Hobby](https://smarthomehobby.com/) - Features budget friendly guides and information.
- [Self Hosted Home](https://selfhostedhome.com/) - Articles on DIY home automation projects and self hosted services.
- [Tinkering with Home Automation](https://blog.ceard.tech/) - Tinkerer's blog and guides.
- [HomeTechHacker](https://HomeTechHacker.com) - DIY Smarthome guides, reviews, and advice.
- [Intermittent Technology](https://blog.quindorian.org) - Quindor's personal blog for pasting random (mostly technology related) things.

### YouTube Channels

_Sit back, relax, watch, and learn._

- [BRUH](https://www.youtube.com/channel/UCLecVrux63S6aYiErxdiy4w) - Ben has great tutorials for getting started, unfortunately, inactive lately.
- [BurnsHA](https://www.youtube.com/channel/UCSKQutOXuNLvFetrKuwudpg) - Great informational and tutorial videos.
- [DrZzs](https://www.youtube.com/channel/UC7G4tLa4Kt6A9e3hJ-HO8ng) - Great how-to videos and also streams live.
- [The Hook Up](https://www.youtube.com/channel/UC2gyzKcHbYfqoXA5xbyGXtQ) - Tutorials and more, also has videos on home automation in general.
- [HASSCASTS](https://www.youtube.com/channel/UCGOCeqMJnLvr-5C-ypUw7IQ) - Tips, Tricks & Tutorials, moving to mainly live streams.
- [JuanMTech](https://www.youtube.com/juanmtech) - Easy to follow how-to videos, product reviews and more.
- [vCloudInfo](https://www.youtube.com/vCloudInfo) - Publishes videos based on his home and GitHub repository.
- [digiblurDIY](https://www.youtube.com/channel/UC5ZdPKE2ckcBhljTc2R_qNA) - Tutorials on hardware projects and Tasmota automations.
- [Intermit.Tech](https://www.youtube.com/channel/UCv7UOhZ2XuPwm9SN5oJsCjA) - Tutorials & reviews: Camera's, Home Networking, ESP8266 boards, Node-RED.

### Podcasts

_Get inspired, while commuting, doing your morning routine, or at the gym!_

- [Home Assistant Podcast](https://hasspodcast.io) - Biweekly podcast with the latest news and interesting guests.

### Twitter

_Keep up with the latest news and updates, 280 characters at a time!_

- [@home_assistant](https://twitter.com/home_assistant) - Open source home automation that puts local control and privacy first.
- [@hass_devs](https://twitter.com/hass_devs) - Latest news on the development of Home Assistant for contributors.
- [@balloob](https://twitter.com/balloob) - Founder of the Home Assistant project.
- [@pvizeli](https://twitter.com/pvizeli) - Core developer and creator of the Hass.io project.
- [@frenck](https://twitter.com/frenck) - Creator of this Awesome list and maintainer of the Community Hass.io Add-ons project.
- [@ccostan](https://twitter.com/ccostan) - Blogger of all things Tech. Smart Home, #IOT & other Geeky subjects.
- [@HomeTechHacker](https://twitter.com/HomeTechHacker) - Guy friends call when #tech happens. Tweet 25-50x/week about #smarthome, #homenetwork, #cybersecurity, #Linux, #gadgets, and #life.
- [@hassioaddons](https://twitter.com/hassioaddons) - For all commmunity add-on news and updates.
- [@Dr_Zzs](https://twitter.com/Dr_Zzs) - Great how-to videos and also streams live.

## Uncategorized

_Valuable links, that don't fit in any of the above categories (yet!)._

- [Room Assistant](https://github.com/mKeRix/room-assistant) - A companion client to handle sensors in multiple rooms. :star:333
- [Home Assistant Companion](https://itunes.apple.com/us/app/home-assistant-open-source-home-automation/id1099568401?mt=8) - iPhone/iPad/iOS App to control and monitor your home remotely.
- [Mi Flora via MQTT daemon](https://github.com/ThomDietrich/miflora-mqtt-daemon) - Collect and transfer Xiaomi Mi Flora plant sensor data via MQTT. :star:277
- [hassctl](https://github.com/dale3h/hassctl) - Simple command line utility to help debug your configuration. :star:72
- [rhasspy](https://github.com/synesthesiam/rhasspy) - Toolkit for developing custom voice assistants. :star:95
- [Fully Kiosk Browser](https://www.ozerov.de/fully-kiosk-browser/) - Highly configurable Android Kiosk Browser and App Launcher.
- [Hassio Vagrant](https://github.com/hassio-addons/hassio-vagrant) - Vagrant box original created for developing add-ons. :star:32
- [AppDaemon](https://github.com/home-assistant/appdaemon) - Python Apps for Home Assistant. :star:385
- [Developer Documentation](https://developers.home-assistant.io/) - The official developer documentation.
- [HASS Configurator](https://github.com/danielperna84/hass-configurator) - Browser-based configuration file editor. :star:175
- [HA-Dockermon](https://github.com/philhawthorne/ha-dockermon) - A Node.js service for RESTful switches to control Docker containers. :star:107
- [Python Amazon Dash](https://github.com/Nekmo/amazon-dash) - Hack your Amazon Dash to run what you want. Without welders. :star:567
- [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) - HomeKit to MQTT bridge. :star:226
- [Home Assistant Device Database](https://www.hadevices.com/) - Database of supported/confirmed working devices.
- [Jinja Scripts for Curious Minds](https://github.com/skalavala/mysmarthome/tree/master/jinja_helpers) - Bunch of Jinja2 scripts helping you to understand it better. :star:52
- [WallPanel](https://thanksmister.com/wallpanel-android/) - Android application for web-based dashboards and home automation platforms.
- [Ariela](https://play.google.com/store/apps/details?id=com.surodev.ariela) - Freemium Android client application with widget support.
- [Gitlab CI/CD](https://about.gitlab.com/2018/08/02/using-the-gitlab-ci-slash-cd-for-smart-home-configuration-management/) - How to simplify your smart home configuration with GitLab CI/CD.
- [Monitor](https://github.com/andrewjfreyer/monitor) - Distributed advertisement-based BTLE presence detection reported via MQTT. :star:571
- [HASS-data-detective](https://github.com/robmarkcole/HASS-data-detective) - Explore and analyse your database data. :star:75
- [ADB Intents](https://gist.github.com/mcfrojd/9e6875e1db5c089b1e3ddeb7dba0f304) - List of ADB intents to control Android Devices.
- [Home Assistant Config Helper for VSCode](https://marketplace.visualstudio.com/items?itemName=keesschollaart.vscode-home-assistant) - Visual Studio Code Extension that provides auto-completion, config validation and snippets when editting your configuration.

## Alternative Home Automation Software

_Home Assistant isn't the only home automation framework out there, here
are some alternatives._

- [openHAB](https://github.com/openhab) - Java-based and aims at being a universal integration platform.
- [Domoticz](https://github.com/domoticz/domoticz) - A lightweight Home Automation System. :star:2315
- [Gladys](https://github.com/GladysProject/Gladys) - Open source program which runs on your Raspberry Pi. :star:1268
- [SmartThings](https://www.smartthings.com/) - Commercial home automation hub by Samsung.

## Other Awesome Lists

_Other amazingly awesome lists that can be found on the great and dangerous
interwebs._

- [awesome-smarthome](https://github.com/pfalcon/awesome-smarthome) - Curated list of awesome SmartHome/Home Automation things. :star:185
- [awesome-iot](https://github.com/HQarroum/awesome-iot) - Curated list of awesome Internet of Things projects and resources. :star:1627
- [awesome-open-iot](https://github.com/Agile-IoT/awesome-open-iot) - Curated list of open source IoT frameworks, libraries and software. :star:376
- [awesome-amazon-alexa](https://github.com/miguelmota/awesome-amazon-alexa#readme) - Curated list of awesome resources for the Amazon Alexa platform. :star:408
- [awesome-mqtt](https://github.com/hobbyquaker/awesome-mqtt#readme) - Curated list of MQTT related stuff. :star:1086

## Contributing

This awesome list is an active open-source project and is always open to
people who want to contribute to it. We have set up a separate document
containing our [Contribution Guidelines](https://github.com/frenck/awesome-home-assistant/blob/master/CONTRIBUTING.md).

The original setup of this awesome list is by [Franck Nijhof](https://twitter.com/frenck).

For a full list of all authors and contributors, check the
[contributor's page](https://github.com/frenck/awesome-home-assistant/graphs/contributors).

Thank you for being involved! 😍

## Trademark Legal Notice

This Awesome list is not created, developed, affiliated, supported, maintained
or endorsed by Home Assistant.

All product names, logos, brands, trademarks and registered trademarks are
property of their respective owners. All company, product, and service names
used in this list are for identification purposes only.

Use of these names, logos, trademarks, and brands does not imply endorsement.

## License

Distributed under the Creative Commons Attribution 4.0 license.
See [LICENSE](https://github.com/frenck/awesome-home-assistant/blob/master/LICENSE.md) for
the complete license.

