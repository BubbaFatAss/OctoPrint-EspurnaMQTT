---
layout: plugin

id: espurna_mqtt
title: OctoPrint-EspurnaMQTT
description: Plugin to control Espurna devices via MQTT protocol.
author: jneilliii
license: AGPLv3

date: 2018-01-04

homepage: https://github.com/jneilliii/OctoPrint-EspurnaMQTT
source: https://github.com/jneilliii/OctoPrint-EspurnaMQTT
archive: https://github.com/jneilliii/OctoPrint-EspurnaMQTT/archive/master.zip

follow_dependency_links: false

tags:
- espurna
- mqtt
- power

screenshots:
- url: /assets/img/plugins/espurna-mqtt/navbar.png
  alt: Navbar
  caption: Buttons on navigation bar
- url: /assets/img/plugins/espurna-mqtt/settings.png
  alt: Settings
  caption: Espurna-MQTT Settings
- url: /assets/img/plugins/espurna-mqtt/relay_editor.png
  alt: Relay Editor
  caption: Espurna-MQTT Relay Editor

featuredimage: /assets/img/plugins/espurna-mqtt/navbar.png
---

This plugin allows the control of [Espurna](https://github.com/arendst/Sonoff-Espurna) devices from within OctoPrint via [MQTT](https://github.com/arendst/Sonoff-Espurna/wiki/MQTT-Overview#mqtt-overview) commands.

## Prerequisites

Install the [MQTT](https://github.com/OctoPrint/OctoPrint-MQTT) plugin via the Plugin Manager or manually using this url:

	https://github.com/OctoPrint/OctoPrint-MQTT/archive/master.zip
	
## Setup

Install via the Plugin Manager or manually using this URL:

    https://github.com/jneilliii/OctoPrint-EspurnaMQTT/archive/master.zip

## Configuration

- Once installed your Espurna devices will need to have the FullTopic configured as **%topic%/%prefix%/**
- Use the Espurna device's topic in the Espurna-MQTT Plugin settings for the individual relays.
- For multiple relay devices enter the index number that matches your desired relay.
- For single relay devices like the [iTead Sonoff S20 Smart Socket](https://www.itead.cc/smart-socket.html), leave Relay # blank.
