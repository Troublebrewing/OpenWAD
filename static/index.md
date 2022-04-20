# About

This repository contains the yaml configuration that is pulled when initially commisioning an OpenWAD device. The device configuration will be imported to your ESPHome dashboard then will show up in the "Devices and Services" or "Integrations" page of Home Assistant. 

The following elements must be in your secrets.yaml file:
* ota_password
* wifi_ssid
* wifi_password
* ap_password

Wifi credentials may also be configured via the Captive Portal or bluetooth Improv tool. 

# Installation

You can use the button below to install the pre-built firmware directly to your device via USB from the browser.

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>

<script type="module" src="https://unpkg.com/esp-web-tools@5.2.0/dist/web/install-button.js?module"></script>
