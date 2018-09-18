# Awesome Homematic [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Homematic related links

[Homematic](http://www.homematic.com/) is a series of Smart Home devices from the manufacturer [eQ-3](http://www.eq-3.de), popular especially in Germany.


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


## Community Ressources (mostly german language)

* [Homematic Forum](https://homematic-forum.de/) - Diskussions-Foren
* [Homematic Forum Link/Skript-Sammlung](https://homematic-forum.de/forum/viewtopic.php?f=26&t=27907) - Curated link list by AndiN.
* [Homematic Guru](https://homematic-guru.de/) - News, Blog, Tutorials und mehr.
* [Homematic Inside](https://www.homematic-inside.de/) - News, Blog, Tutorials und mehr.
* [Technikkram](https://technikkram.net) - News, Blog, Tutorials und mehr.
* [OwnSmartHome](https://ownsmarthome.de/category/homematic/) - News, Blog, Tutorials und mehr.
* [Wikimatic](http://www.wikimatic.de/wiki/Hauptseite) - Community Wiki.


## Documentation

* [Dissecting HomeMatic AES](https://git.zerfleddert.de/hmcfgusb/AES/) - BidCos Protocol AES Handshake description.
* [Direktverknüpfungen im Expertenmodus](https://www.youtube.com/watch?v=1B4iwtK1Rmo) - Vortrag von Frank Grass.
* [Virtuelle Aktorkanäle](https://www.youtube.com/watch?v=Cwxwtig6Q1I) - Vortrag von Frank Grass.
* [Script Documentation](http://www.wikimatic.de/wiki/Script_Dokumentation) - Inoffizielle Homematic Script Referenz.

## Mobile Apps

* [HistClient](https://www.sa-com.de/smarthome-special/histclient-handbuch/) - **$** (inApp-Purchase) - CCU-Historian Client mit erweitereten Features für iOS und Android
* [Home-24](http://www.home-24.net/index.php?page=sites/home.php&app=home24) - **$** Android 
* [HomeControl](http://www.ksquare.de/myhomecontrol/) - **$** iOS
* [TinyMatic](http://tinymatic.de/) - **$** Android (ehemals: HomeDroid)
* [HomeNOW](http://homenow.at) - **$** Android
* [Orbylon](https://www.orbylon.de/orbylon) - **$** iOS, Android, Windows Phone
* [Pocket Control](https://www.penzler.de) - **$** iOS


## CCU Alternatives

* [Anleitung zur Installation der CCU auf einem x86 system](https://homematic-forum.de/forum/viewtopic.php?t=39240) - OCCU Installation auf x86 Systemen
* [Homegear](https://www.homegear.eu/index.php/Main_Page) - Free and open source program to interface your smart home devices with your home automation software or your own scripts.
* [piVCCU](https://github.com/alexreinert/piVCCU) - Install the original Homematic CCU2 firmware inside a virtualized container (lxc) on a Raspberry Pi running Raspbian Jessie or Stretch.
* [RaspberryMatic](https://github.com/jens-maus/RaspberryMatic) - Lightweight, OCCU and Linux/buildroot-based distribution for running a HomeMatic CCU on embedded devices like the RaspberryPi.


## Alternative Sensors, Actuators and Hardware Modifications

* [Beispiel_AskSinPP](https://github.com/jp112sdl/Beispiel_AskSinPP) - Beispiel für die Verwendung der [AskSinPP](https://github.com/pa-pa/AskSinPP) Bibliothek
* [HAUS-BUS.DE](http://www.haus-bus.de/) - **$** Homematic Wired kompatible Geräte.
* [Homematic Wired Hombrew Hardware](https://github.com/jfische) - Verschiedene Homebrew Sensoren/Aktoren für Homematic Wired.
* [stall.biz](https://www.stall.biz/) - **$** Alternative Antennen, Multi Sensor für das Wohnzimmer, Wetterstation, ...


## CCU Addons

* [CCU Historian](http://www.ccu-historian.de/) - Langzeit Archiv und Graphen.
* [CUxD](https://www.homematic-inside.de/software/cuxdaemon) - Der "Leatherman" für die CCU. Verbindet FS20, ... (**$** EnOcean, ...), stellt virtuelle Geräte und hilfreiche Tools zur Verfügung.
* [CUxD-Highcharts](https://github.com/hobbyquaker/cuxd-highcharts) - Visualisiert CUxD Logs mit Highcharts.
* [Email](https://github.com/jens-maus/hm_email) - HomeMatic CCU Addon für den Email Versand.
* [Hm-print](https://github.com/litti/hm-print) - CCU Programme drucken.
* [Hm-tools](https://github.com/fhetty/hm-tools) - Sammlung von Tools für RaspberryMatic.
* [Homeputer](https://www.contronics.de/shop/HomeMatic-System/Zentralen-und-Software.html) - **$**
* [Homematic-addon-hue](https://github.com/j-a-n/homematic-addon-hue) - HomeMatic Addon für Philips Hue.
* [homematic_check_mk](https://github.com/alexreinert/homematic_check_mk) - Addon for the Homematic CCU2 or a Raspberrymatic device which acts as an check_mk_agent.
* [jq](https://github.com/hobbyquaker/ccu-addon-jq) - jq packaged as Addon for the Homematic CCU3.
* [Mosquitto](https://github.com/hobbyquaker/ccu-addon-mosquitto) - Mosquitto packaged as Addon for the Homematic CCU3 and RaspberryMatic
* [rmupdate](https://github.com/j-a-n/raspberrymatic-addon-rmupdate) - RaspberryMatic Addon das RaspberryMatic selbst aktualisieren kann, vereinfacht die WLAN Konfiguration mit GUI und kann andere Addons ohne Zwangsreboot installieren und aktualisieren
* [Redis](https://github.com/hobbyquaker/ccu-addon-redis) - Redis packaged as Addon for the Homematic CCU3 and RaspberryMatic
* [RedMatic](https://github.com/hobbyquaker/RedMatic) - [Node-RED](https://nodered.org/) packaged as Addon for the Homematic CCU3 and RaspberryMatic.
* [WebMatic](http://webmatic.lmdsoft.de/tiki-index.php) - WebUI für die Homematic CCU.
* [XML-API](https://github.com/hobbyquaker/xml-api) - Vereinfachter CCU Zugriff via HTTP/XML.


## Interfacing Software

* [Homebridge-homematic](https://github.com/thkl/homebridge-homematic) - Supports the Homematic System on [HomeBridge](https://github.com/nfarina/homebridge) Platform.
* [Homematic-Virtual-Interface](https://github.com/thkl/Homematic-Virtual-Interface) - Virtual Interface for Homematic CCU with plugins to connect other devices to your CCU (e.g. Philips Hue).
* [Hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js) - Interface between Homematic and MQTT.
* [Node-red-contrib-ccu](https://github.com/hobbyquaker/node-red-contrib-ccu) - [Node-RED](https://nodered.org) Nodes for the Homematic CCU.


## Misc Software

* [Check_homematic](https://github.com/hobbyquaker/check_homematic) - Nagios/Icinga Plugin for checking Homematic CCU.
* [Hm-simulator](https://github.com/hobbyquaker/hm-simulator) - Simulates (partly) a Homematic CCU.
* [Hmcfgusb](https://git.zerfleddert.de/cgi-bin/gitweb.cgi/hmcfgusb) - Utilities to use the HM-CFG-USB(2) on Linux/Unix.
* [HMXMLBIN](https://github.com/leonsio/HMXMLBIN) - Converter between BINRPC and XMLRPC.
* [Homematic-manager](https://github.com/hobbyquaker/homematic-manager) - Manage homematic interface processes (rfd/hs485d/homegear).
* [Language-homematic](https://github.com/Ayngush/language-homematic) - Adds syntax highlighting and snippets to HomeMatic Script files in Atom.
* [occu-test](https://github.com/hobbyquaker/occu-test) - Automated System Tests of ReGaHss - the HomeMatic (O)CCU "Logic Layer".

## Software Modules

* [Binrpc](https://github.com/hobbyquaker/binrpc) - Xmlrpc_bin protocol client and server Node.js module.
* [Homematic-rega](https://github.com/hobbyquaker/homematic-rega) - Node.js Homematic CCU ReGaHSS Remote Script Interface.
* [Homematicip-rest-api](https://github.com/coreGreenberet/homematicip-rest-api) - Python wrapper for the homematicIP REST API (Cloud / Access Point Based).
* [Homematic-xmlrpc](https://github.com/hobbyquaker/homematic-xmlrpc) - Xmlrpc client and server Node.js module.
* [Pmatic](https://github.com/LarsMichelsen/pmatic) - Python API for Homematic. Easy to use.
* [Pyhomematic](https://github.com/danielperna84/pyhomematic) - Python 3 Interface to interact with Homematic devices.

## Smart Home Software supporting Homematic

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
