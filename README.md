# OctoPrint-EspurnaMQTT

This plugin allows the control of [Espurna](https://github.com/xoseperez/espurna) devices from within OctoPrint via [MQTT](https://github.com/xoseperez/espurna/wiki/MQTT) commands.

## Prerequisites

Install the [MQTT](https://github.com/OctoPrint/OctoPrint-MQTT) plugin via the Plugin Manager or manually using this url:

	https://github.com/OctoPrint/OctoPrint-MQTT/archive/master.zip
	
## Setup

Install via the Plugin Manager or manually using this URL:

    https://github.com/jneilliii/OctoPrint-TasmotaMQTT/archive/master.zip

## Configuration

- Once installed your Espurna devices will allow you to customise the topic.  Specify the full topic in the configuration.
- Use the displayed device's topic in the Espurna-MQTT Plugin settings for the individual relays.
- For multiple relay devices enter the index number that matches your desired relay.
- For single relay devices like the [iTead Sonoff S20 Smart Socket](https://www.itead.cc/smart-socket.html), leave Relay # blank.
- Full Topic in plugin settings must match your relay's `Full Topic` pattern.

## Screenshots

![screenshot](navbar.png)

![screenshot](settings.png)

![screenshot](relay_editor.png)

## Support My Efforts
This is forked form Tasmota-MQTT plugin by https://github.com/jneilliii/OctoPrint-TasmotaMQTT.  Please consider supporting him if you find this helpful, or dropping me a message if you prefer Espurna over Tasmota ;-).
