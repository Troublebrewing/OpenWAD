# About

This repository contains the yaml configuration that is pulled during initial commisioning an OpenWAD device. The device configuration will be imported to your ESPHome dashboard then will show up in the "Devices and Services" or "Integrations" page of Home Assistant. 

The following elements must be in your secrets.yaml file:
* ota_password
* wifi_ssid
* wifi_password
* ap_password

Wifi credentials may also be configured via the Captive Portal or bluetooth Improv tool. 

# Installation

Purchased sensors come pre-installed with the latest OpenWAD firmware. Users who have built their own, or wish to reflash their purchased units can do so using the button below. You will need to connect your OpenWAD device to your computer through a USB-to-serial adapter of some sort. It is recommended to use the Watterott CP2102N-Breakout https://learn.watterott.com/breakouts/cp2102n-breakout/ as the OpenWAD serial pads are designed to directly fit this serial adapter. 

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>

<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script>
