# Awesome Node-RED with stars

> Curated list of useful resources for Node-RED.

[Node-RED](https://nodered.org/) is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

It provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that can be deployed to its runtime in a single-click.

## Contents

* [Installation](#installation)
* [Documentation](#documentation)
* [Nodes](#nodes)
  * [Analysis](#analysis)
  * [Database](#database)
  * [Development](#development)
  * [Function](#function)
  * [Hardware](#hardware)
  * [I/O](#io)
  * [Image processing](#image-processing)
  * [Parsers](#parsers)
  * [Smarthome](#smarthome)
  * [Social](#social)
  * [System](#system)
  * [Time](#time)
  * [Utility](#utility)
  * [UI](#ui)
* [Community](#community)

## Installation

* [Running under Docker](https://github.com/node-red/node-red-docker) ⭐ 538 | 🐛 22 | 🌐 Shell | 📅 2026-07-30
* [RedMatic](https://github.com/rdmtc/RedMatic/wiki/Installation) ⭐ 532 | 🐛 178 | 🌐 HTML | 📅 2026-07-18 - Install Node-RED on a CCU3, smart home automation hardware from the manufacturer eQ-3, popular especially in Germany.
* [c't-Smart-Home](https://github.com/ct-Open-Source/ct-Smart-Home) ⭐ 171 | 🐛 26 | 🌐 Shell | 📅 2023-09-12 - A ready-to-use setup for home automation maintained by [german computer magazine c't](https://www.ct.de/smarthome).
* [ioBroker node-red Adapter](https://github.com/ioBroker/ioBroker.node-red) ⭐ 53 | 🐛 26 | 🌐 JavaScript | 📅 2026-08-15 - Starts an instance within ioBroker and communicates with it.
* [Running locally](https://nodered.org/docs/getting-started/local)
* [Home Assistant Community Add-on](https://community.home-assistant.io/t/home-assistant-community-add-on-node-red/55023) - Starts an instance within Home Assistant and communicates with it.
* [openHAB running on openHABian](https://www.openhab.org/docs/installation/openhabian.html#optional-components) - Install Node-RED using openhab-config from command line, choose it from "Optional Components".

## Documentation

* [Getting Started](https://nodered.org/docs/getting-started/)
* [FAQ](https://nodered.org/docs/faq/)
* [Tutorials](https://nodered.org/docs/tutorials/)
* [User Guide](https://nodered.org/docs/user-guide/)

## Nodes

### Analysis

* [badwords](https://github.com/node-red/node-red-nodes/tree/master/analysis/swearfilter) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Analyses the payload and tries to filter out any messages containing bad swear words. This only operates on payloads of type string. Everything else is blocked.
* [wordpos](https://github.com/node-red/node-red-nodes/tree/master/analysis/wordpos) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Analyses the payload and classifies the part-of-speech of each word. The resulting message has msg.pos added with the results. A word may appear in multiple categories (eg, 'great' is both a noun and an adjective).

### Database

* [leveldb](https://github.com/node-red/node-red-nodes/tree/master/storage/leveldb) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses LevelDB for a simple key value pair database.
* [mysql](https://github.com/node-red/node-red-nodes/tree/master/storage/mysql) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Allows basic access to a MySQL database.
* [sqlite](https://github.com/node-red/node-red-nodes/tree/master/storage/sqlite) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Supports read and write to a local sqlite database.
* [influxdb](https://github.com/mblackstock/node-red-contrib-influxdb) ⭐ 66 | 🐛 37 | 🌐 HTML | 📅 2026-04-02 - Save and query data from an InfluxDB time series database.
* [mssql-plus](https://github.com/bestlong/node-red-contrib-mssql-plus) ⭐ 32 | 🐛 21 | 🌐 HTML | 📅 2026-05-13 - Execute queries, stored procedures and bulk inserts in Microsoft SQL Server and Azure Databases SQL2000 \~ SQL2019.
* [stackhero-influxdb-v2](https://github.com/stackhero-io/node-red-contrib-stackhero-influxdb-v2) ⭐ 31 | 🐛 16 | 🌐 HTML | 📅 2023-03-02 - Save and query data from an InfluxDB v2 time series database.
* [stackhero-mysql](https://github.com/stackhero-io/node-red-contrib-stackhero-mysql) ⭐ 19 | 🐛 1 | 🌐 HTML | 📅 2025-10-06 - Connect to a MySQL or a MariaDB database, using TLS (SSL) and compatible with "Caching SHA2 password" authentication method (MySQL >= 8).

### Development

* [typescript-starter](https://github.com/alexk111/node-red-node-typescript-starter) ⭐ 90 | 🐛 1 | 🌐 Mustache | 📅 2026-08-04 - Quick-start template repository for creating new node sets in TypeScript.

### Function

* [datagenerater](https://github.com/node-red/node-red-nodes/tree/master/function/datagenerator) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Generate dummy data in various formats, names, addresses, emails, numbers, words, etc.
* [pidcontrol](https://github.com/node-red/node-red-nodes/tree/master/function/PID) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - A PID control node for numeric inputs - provides simple controll loop feedback capability.
* [random](https://github.com/node-red/node-red-nodes/tree/master/function/random) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Random number generator - can generate integers for x to y - or floats between x and y.
* [rbe](https://github.com/node-red/node-red-nodes/tree/master/function/rbe) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Provide report by exception and deadband / bandgap capability for simple inputs.
* [smooth](https://github.com/node-red/node-red-nodes/tree/master/function/smooth) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Provide various functions across several previous values, including max, min, mean, high and low pass filters.

### Hardware

* [arduino](https://github.com/node-red/node-red-nodes/tree/master/hardware/Arduino) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses firmata protocol to talk to the board.
* [beaglebone](https://github.com/node-red/node-red-nodes/tree/master/hardware/BBB) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Nodes for the [Beaglebone Black](https://beagleboard.org/black).
* [blink1](https://github.com/node-red/node-red-nodes/tree/master/hardware/blink1) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - [Blink1](https://blink1.thingm.com/) USB LED from ThingM.
* [blinkstick](https://github.com/node-red/node-red-nodes/tree/master/hardware/blinkstick) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - [BlinkStick](https://www.blinkstick.com/) USB LED device.
* [digirgb](https://github.com/node-red/node-red-nodes/tree/master/hardware/digiRGB) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - DigiSpark RGB USB LED.
* [heatmiser](https://github.com/node-red/node-red-nodes/tree/master/hardware/heatmiser) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Temperature and frost protection for Heatmiser thermostats.
* [intel-galileo](https://github.com/node-red/node-red-nodes/tree/master/hardware/intel) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - A collection for the Intel Galileo and Edison.
* [ledborg](https://github.com/node-red/node-red-nodes/tree/master/hardware/LEDborg) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - [LEDborg](https://www.piborg.org/ledborg) plug on module.
* [makeymakey](https://github.com/node-red/node-red-nodes/tree/master/hardware/makey) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Read from a [MakeyMakey](http://www.makeymakey.com/) input device.
* [pi-gpiod](https://github.com/node-red/node-red-nodes/tree/master/hardware/pigpiod) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - An alternative to the default PI GPIO nodes that allows remote access.
* [pi-mcp3008](https://github.com/node-red/node-red-nodes/tree/master/hardware/mcp3008) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Read from MCP300x series Analogue to Digital Converter chips via the SPI bus.
* [pi-neopixel](https://github.com/node-red/node-red-nodes/tree/master/hardware/neopixel) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Drive a strip of NeoPixels directly.
* [pi-unicorn-hat](https://github.com/node-red/node-red-nodes/tree/master/hardware/unicorn) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Controls a Pimorini Unicorn HAT 8x8 LED display.
* [pibrella](https://github.com/node-red/node-red-nodes/tree/master/hardware/Pibrella) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Controls a [Pibrella](https://pibrella.com/) add-on board.
* [piface](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiFace) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - [PiFace](https://www.piface.org.uk/) interface module.
* [piliter](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiLiter) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Controls a Pimorini Pi-LITEr 8 LED add-on board.
* [sensortag](https://github.com/node-red/node-red-nodes/tree/master/hardware/sensorTag) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Reads data from the Ti Bluetooth Low Energy SensorTag device.
* [wemo](https://github.com/node-red/node-red-nodes/tree/master/hardware/wemo) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Drive a [WeMo](https://www.belkin.com/us/Products/home-automation/c/wemo-home-automation/) socket and switch.
* [scanBLE](https://github.com/node-red/node-red-nodes/tree/master/hardware/scanBLE) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Scans for a particular Bluetooth Low Energy device.

### I/O

* [discovery](https://github.com/node-red/node-red-nodes/tree/master/io/mdns) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Discovers other Avahi/Bonjour services on the network.
* [emoncms](https://github.com/node-red/node-red-nodes/tree/master/io/emoncms) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Post to an [Emoncms](https://emoncms.org/) server.
* [mqlight](https://github.com/node-red/node-red-nodes/tree/master/io/mqlight) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Adds nodes to send and receive using MQlight.
* [ping](https://github.com/node-red/node-red-nodes/tree/master/io/ping) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Pings a machine and returns the trip time in mS.
* [serialport](https://github.com/node-red/node-red-nodes/tree/master/io/serialport) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Send messages to and receive messages from a physical serial port.
* [snmp](https://github.com/node-red/node-red-nodes/tree/master/io/snmp) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - SNMP receivers for single OIDs or OID tables.
* [stomp](https://github.com/node-red/node-red-nodes/tree/master/io/stomp) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Publish and subscribe to and from a [STOMP server](https://stomp.github.io/implementations.html#STOMP_Servers).
* [wol](https://github.com/node-red/node-red-nodes/tree/master/io/wol) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Sends a Wake-On-LAN magic packet to the mac address specified.
* [modbus](https://github.com/biancoroyal/node-red-contrib-modbus) ⭐ 346 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-14 - All in one Modbus TCP and Serial package.
* [s7](https://github.com/st-one-io/node-red-contrib-s7) ⭐ 133 | 🐛 45 | 🌐 HTML | 📅 2026-01-15 - Interact with Siemens S7 PLCs.
* [mindconnect](https://github.com/mindsphere/node-red-contrib-mindconnect) ⭐ 50 | 🐛 20 | 🌐 TypeScript | 📅 2024-09-06 - Upload timeseries, files and events to MindSphere.
* [xiaomi-ble](https://github.com/eschava/node-red-contrib-xiaomi-ble) ⭐ 20 | 🐛 13 | 🌐 JavaScript | 📅 2021-01-19 - Single "Xiaomi BLE" node that gets all known data from Xiaomi BLE (Bluetooth 4).
* [noble-bluetooth](https://github.com/clausbroch/node-red-contrib-noble-bluetooth) ⭐ 11 | 🐛 12 | 🌐 JavaScript | 📅 2021-07-13 - Based on noble for interaction with Bluetooth Low Energy devices.

### Image processing

* [image-output](https://github.com/rikukissa/node-red-contrib-image-output) ⭐ 15 | 🐛 6 | 🌐 HTML | 📅 2023-08-05 - Simple image output node. Useful for previewing images (of face detecting, object recognition etc.) inside the flow editor.
* [image-tools](https://flows.nodered.org/node/node-red-contrib-image-tools) - Editing images, building and decoding 2D and 3D barcodes.

### Parsers

* [base64](https://github.com/node-red/node-red-nodes/tree/master/parsers/base64) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Converts a payload to/from base64 encoded format.
* [geohash](https://github.com/node-red/node-red-nodes/tree/master/parsers/geohash) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Converts a lat, lon payload to/from geohash format.
* [msgpack](https://github.com/node-red/node-red-nodes/tree/master/parsers/msgpack) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Converts a payload to/from msgpack binary packed format.
* [what3words](https://github.com/node-red/node-red-nodes/tree/master/parsers/what3words) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Encodes or Decodes a lat, lon position into what3words text format.
* [buffer-parser](https://flows.nodered.org/node/node-red-contrib-buffer-parser) - Converts values to and from buffer/array. Supports Big/Little Endian, BCD, byte swapping and much more.

### Smarthome

* [home-assistant-websocket](https://github.com/zachowj/node-red-contrib-home-assistant-websocket) ⭐ 597 | 🐛 49 | 🌐 TypeScript | 📅 2026-08-19 - Various nodes using websockets to assist in setting up communication with Home Assistant.
* [homekit-bridged](https://github.com/NRCHKB/node-red-contrib-homekit-bridged) ⭐ 443 | 🐛 28 | 🌐 TypeScript | 📅 2026-06-21 - Imitate HomeKit devices.
* [huemagic](https://github.com/Foddy/node-red-contrib-huemagic) ⭐ 202 | 🐛 0 | 🌐 HTML | 📅 2026-08-19 - Controls Philips Hue bridges, lights, groups, scenes, rules, taps, switches, buttons, motion sensors, temperature sensors and Lux sensors.
* [knx-ultimate](https://github.com/Supergiovane/node-red-contrib-knx-ultimate) ⭐ 178 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-13 - Controls KNX intallation. With optional ETS group address importer and gateway simulation.
* [smartnora](https://github.com/andrei-tatar/node-red-contrib-smartnora) ⭐ 114 | 🐛 1 | 🌐 HTML | 📅 2026-05-12 - Google smart home Action integration via Smart NORA.
* [alexa-remote2-applestrudel](https://github.com/bbindreiter/node-red-contrib-alexa-remote2-applestrudel) ⭐ 106 | 🐛 44 | 🌐 HTML | 📅 2026-07-08 - Interacting with the Alexa API. Emulates routine behaviour, control and query your devices.
* [zigbee2mqtt](https://github.com/andreypopov/node-red-contrib-zigbee2mqtt) ⭐ 101 | 🐛 44 | 🌐 JavaScript | 📅 2026-03-26 - Zigbee2mqtt connectivity.
* [homebridge-automation](https://github.com/NorthernMan54/node-red-contrib-homebridge-automation) ⭐ 100 | 🐛 10 | 🌐 JavaScript | 📅 2026-08-05 - Integrate Homebridge Accessories into flows.
* [deconz](https://github.com/deconz-community/node-red-contrib-deconz) ⭐ 84 | 🐛 0 | 🌐 JavaScript | 📅 2024-12-02 - Access Zigbee 3.0 (Z30), Zigbee Home Automation (ZHA) and Zigbee Light Link (ZLL) lights via deCONZ.
* [zigbee](https://github.com/hobbyquaker/node-red-contrib-zigbee) ⚠️ Archived - Controls Zigbee Devices via a CC253x Module.
* [sonos-plus](https://github.com/hklages/node-red-contrib-sonos-plus) ⭐ 81 | 🐛 7 | 🌐 JavaScript | 📅 2026-06-11 - Controls Sonos player in your local network.
* [loxone](https://github.com/codmpm/node-red-contrib-loxone) ⭐ 78 | 🐛 22 | 🌐 HTML | 📅 2024-04-19 - Connect to the Loxone Miniserver.
* [home-assistant](https://github.com/AYapejian/node-red-contrib-home-assistant) ⭐ 77 | 🐛 37 | 🌐 HTML | 📅 2018-09-30 - Connect with Home Assistant.
* [ccu](https://github.com/rdmtc/node-red-contrib-ccu) ⭐ 69 | 🐛 62 | 🌐 JavaScript | 📅 2026-07-18 - Connect with Homematic, a series of smart home automation hardware from the manufacturer eQ-3, popular especially in Germany.
* [lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) ⭐ 59 | 🐛 48 | 🌐 JavaScript | 📅 2023-10-11 - Controls LG webOS Smart TVs.
* [fritz](https://github.com/bashgroup/node-red-contrib-fritz) ⭐ 52 | 🐛 15 | 🌐 HTML | 📅 2024-01-26 - Provides easy access to your AVM Fritz!Box. Read and write the configuration including the VoIP and Dect configuration.
* [zwave-js](https://github.com/zwave-js/node-red-contrib-zwave-js) ⭐ 51 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-09 - Integrates Z-Wave node based on Z-Wave JS.
* [tuya-smart](https://github.com/hgross/node-red-contrib-tuya-smart) ⭐ 45 | 🐛 6 | 🌐 TypeScript | 📅 2020-09-07 - Interface with smart plugs, bulbs, etc. from tuya.
* [homee](https://github.com/stfnhmplr/node-red-contrib-homee) ⭐ 38 | 🐛 10 | 🌐 JavaScript | 📅 2026-05-24 - Access the homee api and create virtual devices for homee.
* [alexa-home](https://github.com/mabunixda/node-red-contrib-alexa-home) ⭐ 35 | 🐛 6 | 🌐 JavaScript | 📅 2026-06-22 - Connect with Alexa just wihtin the local network - no extra cloud stuff is required.
* [tado-client](https://github.com/mattdavis90/node-red-contrib-tado-client) ⭐ 26 | 🐛 18 | 🌐 HTML | 📅 2025-11-07 - Connect to the Tado Web API.
* [tasmota](https://github.com/DaveMDS/node-red-contrib-tasmota) ⭐ 24 | 🐛 4 | 🌐 HTML | 📅 2024-01-04 - Tasmota devices integration for building automation.
* [avr-yamaha](https://github.com/krauskopf/node-red-contrib-avr-yamaha) ⭐ 21 | 🐛 5 | 🌐 JavaScript | 📅 2021-10-09 - Integrate and control YAMAHA™ audio/video receiver via YNCA protocol.
* [fritzapi](https://github.com/dnknth/node-red-contrib-fritzapi) ⚠️ Archived - Controls smart home DECT devices and guest wifi through an AVM Fritz!Box.
* [tahoma](https://github.com/nikkow/node-red-contrib-tahoma) ⭐ 19 | 🐛 21 | 🌐 TypeScript | 📅 2026-07-08 - Controls a Somfy Tahoma box (Roller shutters, etc.).
* [alexa-home-skill-v3](https://github.com/coldfire84/node-red-contrib-alexa-home-skill-v3) ⭐ 18 | 🐛 7 | 🌐 JavaScript | 📅 2022-03-21 - Controls things via Alexa and Google Home.
  * [alexa-home-skill-v3-web](https://github.com/coldfire84/node-red-alexa-home-skill-v3-web) ⭐ 52 | 🐛 34 | 🌐 JavaScript | 📅 2022-12-23 - Web Service for Alexa and Google Home.
  * [alexa-home-skill-v3-lambda](https://github.com/coldfire84/node-red-alexa-home-skill-v3-lambda) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2020-11-30 - Lambda function for node-red-alexa-home-skill-v3-web.
* [hubitat](https://github.com/fblackburn1/node-red-contrib-hubitat) ⭐ 18 | 🐛 7 | 🌐 JavaScript | 📅 2026-06-15 - Connect with Hubitat.
* [harmony](https://github.com/Aietes/node-red-contrib-harmony) ⭐ 16 | 🐛 18 | 🌐 HTML | 📅 2025-12-10 - Controls devices connected to a Logitech™ Harmony Hub.
* [openhab3](https://github.com/jeroenhendricksen/node-red-contrib-openhab3) ⚠️ Archived - Integration of openHAB item states and commands.
* [power-saver](https://power-saver.smoky.no/) - Automatically save money on variable electricity prices.

### Social

* [dweetio](https://github.com/node-red/node-red-nodes/tree/master/social/dweetio) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses [dweetio](https://dweet.io/) to send/receive messages.
* [email](https://github.com/node-red/node-red-nodes/tree/master/social/email) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Sends and receives simple emails from services like gmail or smtp or imap servers.
* [feedparser](https://github.com/node-red/node-red-nodes/tree/master/social/feedparser) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Reads messages from an atom or rss feed.
* [irc](https://github.com/node-red/node-red-nodes/tree/master/social/irc) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Connect to an IRC server to send and receive messages.
* [notify](https://github.com/node-red/node-red-nodes/tree/master/social/notify) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses [Growl](https://growl.info/) to provide a desktop popup. Only useful on the local Apple machine.
* [prowl](https://github.com/node-red/node-red-nodes/tree/master/social/prowl) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses [Prowl](https://www.prowlapp.com/) to push to an Apple device that has the Prowl app installed.
* [pushbullet](https://github.com/node-red/node-red-nodes/tree/master/social/pushbullet) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses [PushBullet](https://www.pushbullet.com/) to push an Android device that has the app installed.
* [pusher](https://github.com/node-red/node-red-nodes/tree/master/social/pusher) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Publish-Subscribe to a [Pusher](https://pusher.com/) channel/event.
* [pushover](https://github.com/node-red/node-red-nodes/tree/master/social/pushover) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Sends alerts via [Pushover](https://pushover.net/).
* [twilio](https://github.com/node-red/node-red-nodes/tree/master/social/twilio) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses [Twilio](https://www.twilio.com/) service to send/receive text messages.
* [xmpp](https://github.com/node-red/node-red-nodes/tree/master/social/xmpp) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Connect to an XMPP server to send and receive messages.
* [chatbot](https://github.com/guidone/node-red-contrib-chatbot) ⭐ 982 | 🐛 32 | 🌐 HTML | 📅 2026-06-30 - Full featured chat bot for Telegram, Facebook Messenger, Viber, Twilio and Slack.
* [telegrambot](https://github.com/windkh/node-red-contrib-telegrambot) ⭐ 301 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-18 - Contains a receiver and a sender node which act as a Telegram Bot.
* [discord-advanced](https://github.com/Markoudstaal/node-red-contrib-discord-advanced) ⭐ 56 | 🐛 21 | 🌐 JavaScript | 📅 2024-09-01 - Interact with Discord, via Discord.js.
* [slack](https://github.com/yayadrian/node-red-slack) ⭐ 24 | 🐛 11 | 🌐 JavaScript | 📅 2025-04-06 - Interact with the Slack API.
* [open-wa (whatsapp)](https://github.com/open-wa/node-red-contrib-wa-automate) ⭐ 13 | 🐛 3 | 🌐 TypeScript | 📅 2023-04-06 - Efficiently connect to remote instances of your open-wa whatsapp automate servers.
* [whin](https://github.com/inUtil-info/node-red-contrib-whin) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2022-11-03 - Send and receive whatsapps from within a nodered flow.
* [sms77](https://github.com/sms77io/nodered-contrib-sms77) ⭐ 2 | 🐛 8 | 🌐 HTML | 📅 2026-06-20 - Uses [sms77](https://www.sms77.io/) service for SMS, text-to-speech calls and number lookups.
* [PushStaq](https://github.com/pantchox/node-red-contrib-pushstaq) ⭐ 0 | 🐛 2 | 🌐 JavaScript | 📅 2022-10-08 - Send real time alerts using Push Notifications from your Node-Red flows to any device with [PushStaq](https://www.pushstaq.com).

### System

* [aedes](https://github.com/martin-doyle/node-red-contrib-aedes) ⭐ 71 | 🐛 11 | 🌐 JavaScript | 📅 2026-08-16 - MQTT Broker based on Aedes.
* [dockerode](https://github.com/naimo84/node-red-contrib-dockerode) ⭐ 35 | 🐛 8 | 🌐 TypeScript | 📅 2024-05-19 - Connect to Docker daemon.
* [os](https://github.com/Argonne-National-Laboratory/node-red-contrib-os) ⭐ 12 | 🐛 2 | 🌐 HTML | 📅 2021-07-06 - Obtain system information.

### Time

* [suncalc](https://github.com/node-red/node-red-nodes/tree/master/time/suncalc) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Uses the suncalc module to generate an output at sunrise and sunset based on a specified location.
* [timeswitch](https://github.com/node-red/node-red-nodes/tree/master/time/timeswitch) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Lets the user set simple repeating timers for example for simple heating control, etc.
* [sun-position](https://github.com/rdmtc/node-red-contrib-sun-position) ⭐ 111 | 🐛 94 | 🌐 JavaScript | 📅 2026-06-24 - Timer based flow control with dusk, dawn (and variations) and much more. Additional you can get sun and moon position or to control a flow by sun or moon position.
* [blindcontroller](https://github.com/alisdairjsmyth/node-red-contrib-blindcontroller) ⭐ 24 | 🐛 15 | 🌐 HTML | 📅 2020-05-05 - Automate the control of household roller blinds based on the current position of the sun.
* [simpletime](https://github.com/Paul-Reed/node-red-contrib-simpletime) ⭐ 4 | 🐛 1 | 🌐 HTML | 📅 2025-11-03 - Adds time and date payloads with various formatting options, which can be retreived and used later in the flow.
* [bigtimer](https://github.com/scargill/node-red-contrib-bigtimer) ⭐ 2 | 🐛 1 | 🌐 HTML | 📅 2023-04-14 - Timing node with support for dusk/sunset dawn/sunrise and variations also day/week/month (and special days) control. The node offers outputs suitable for MQTT, speech and databases.
* [cron-plus](https://flows.nodered.org/node/node-red-contrib-cron-plus) - A flexible scheduler (cron, solar events, simple dates) node with full dynamic control and Timezone support.

### Utility

* [daemon](https://github.com/node-red/node-red-nodes/tree/master/utility/daemon) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Starts up (calls) a long running system program and pipes STDIN, STDOUT and STDERR to and from that process.
* [exif](https://github.com/node-red/node-red-nodes/tree/master/utility/exif) ⭐ 1,083 | 🐛 162 | 🌐 JavaScript | 📅 2026-07-21 - Extracts GPS and other EXIF information from a passed in jpeg image.
* [watson](https://github.com/watson-developer-cloud/node-red-node-watson) ⭐ 81 | 🐛 38 | 🌐 HTML | 📅 2022-03-28 - Interact with the IBM Watson services in IBM Cloud.
* [ical-events](https://github.com/naimo84/node-red-contrib-ical-events) ⭐ 49 | 🐛 32 | 🌐 TypeScript | 📅 2024-11-19 - Get events from an ical-URL, a caldav-server or from iCloud via [kalender-events](https://github.com/naimo84/kalender-events) ⭐ 20 | 🐛 18 | 🌐 TypeScript | 📅 2026-02-16.
* [actionflows](https://github.com/Steveorevo/node-red-contrib-actionflows) ⭐ 44 | 🐛 6 | 🌐 JavaScript | 📅 2022-02-07 - Brings easy to use loops and OOP (object oriented programming) features.
* [self-healing](https://github.com/jpdias/node-red-contrib-self-healing) ⚠️ Archived - Making Node-RED more resilient by adding self-healing capabilities.
* [moment](https://github.com/totallyinformation/node-red-contrib-moment) ⭐ 34 | 🐛 4 | 🌐 JavaScript | 📅 2023-07-16 - Produces a nicely formatted Date/Time string using the Moment.js library.
* [alarm](https://github.com/Anamico/node-red-contrib-alarm) ⭐ 25 | 🐛 17 | 🌐 HTML | 📅 2026-04-02 - Build your own home alarm system with any number of panels, zones, sensors, triggers and automations.
* [string](https://github.com/steveorevo/node-red-contrib-string) ⭐ 23 | 🐛 4 | 🌐 HTML | 📅 2023-02-10 - Provides native and extended chainable JavaScript string parsing and manipulation methods.
* [state-machine](https://github.com/DeanCording/node-red-contrib-state-machine) ⭐ 18 | 🐛 5 | 🌐 HTML | 📅 2025-01-06 - Wraps around the JavaScript State Machine to implement a finite state machine.
* [persist](https://github.com/DeanCording/node-red-contrib-persist) ⭐ 17 | 🐛 12 | 🌐 HTML | 📅 2023-08-31 - Persist data over Node-RED restarts and deploys.
* [users](https://github.com/SenseTecnic/node-red-contrib-users) ⭐ 15 | 🐛 7 | 🌐 HTML | 📅 2021-05-18 - Quickly build a very simple user access control for HTTP-based flows.
* [german-holidays](https://github.com/rdmtc/node-red-contrib-german-holidays) ⭐ 11 | 🐛 6 | 🌐 JavaScript | 📅 2023-07-18 - Getting german holidays or information if today/tomorrow is a holiday.
* [twc-weather](https://github.com/johnwalicki/node-red-contrib-twc-weather) ⭐ 11 | 🐛 3 | 🌐 HTML | 📅 2026-05-07 - The Weather Company and Weather Underground Personal Weather Station APIs.
* [owntracks](https://github.com/hardillb/node-red-contrib-owntracks) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2016-07-16 - Converts Owntrack Messages into standard geo message and deals with encrypted locations.
* [interval-length](https://github.com/bartbutenaers/node-red-contrib-interval-length) ⭐ 5 | 🐛 7 | 🌐 JavaScript | 📅 2022-04-09 - Measure the (time) interval length between successive messages.
* [bool-gate](https://flows.nodered.org/node/node-red-contrib-bool-gate) - Boolean logic gates.

### UI

* [node-red-dashboard](https://github.com/node-red/node-red-dashboard) ⭐ 1,406 | 🐛 93 | 🌐 HTML | 📅 2025-08-07 - Create a live data dashboard.
  * [https://flows.nodered.org/collection](https://flows.nodered.org/collection/590bc13ff3a5f005c7d2189bbb563976) - Dashboard extra nodes.
  * [ui-svg](https://flows.nodered.org/node/node-red-contrib-ui-svg) - Show interactive SVG (vector graphics) in the dashboard.
  * [ui-contextmenu](https://flows.nodered.org/node/node-red-contrib-ui-contextmenu) - Show a popup contextmenu in the dashboard.
* [uibuilder](https://github.com/TotallyInformation/node-red-contrib-uibuilder) ⭐ 524 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-11 - Create dynamic web interfaces using any (or no) front end libraries for convenience.
* [web-worldmap](https://github.com/dceejay/RedMap) ⭐ 119 | 🐛 9 | 🌐 JavaScript | 📅 2026-06-11 - Provide a world map web page for plotting "things" on.
* [browser-utils](https://github.com/ibm-early-programs/node-red-contrib-browser-utils) ⭐ 17 | 🐛 2 | 🌐 JavaScript | 📅 2022-09-23 - Add browser functionality such as file upload, camera & microphone.
* [flow-manager](https://flows.nodered.org/node/node-red-contrib-flow-manager) - Separates flow json to multiple files.
* [iglass](https://www.npmjs.com/package/iglass-nodes) - Interaction with [iGlass Automation](https://iglass.international) blocks.

## Community

* [HomeAssistant Forum](https://community.home-assistant.io/c/third-party/node-red/31)
* [Node-RED Forum](https://discourse.nodered.org/)
* [Node-RED Blog](https://nodered.org/blog/)
* [Node-RED User Group Japan](https://nodered.jp/)
* [Reddit](https://www.reddit.com/r/nodered/)
* [Redmatic Forum](https://homematic-forum.de/forum/viewforum.php?f=77)
* [Slack](https://nodered.org/about/community/slack)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/node-red)
* [Steves Node-RED Guide](https://stevesnoderedguide.com/)
* [Twitter](https://twitter.com/NodeRED)
* [YouTube](https://www.youtube.com/channel/UCQaB8NXBEPod7Ab8PPCLLAA)

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
