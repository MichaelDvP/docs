---
title: EMS-ESP Documentation
description: Open-source firmware for the Espressif ESP32 microcontroller that communicates with EMS (Energy Management System) based equipment from manufacturers like Bosch, Buderus, Nefit, Junkers, Worcester and Sieger.
hide:
  - toc
---

# ESP32 Firmware to communicate with EMS heating appliances

<img style="margin: 10px 10px; float:right; width:20%" src="_media/logo/boiler.svg" alt="EMS-ESP Logo"></img>
**EMS-ESP** is an open-source firmware for the Espressif ESP32 microcontroller that communicates with **EMS** (Energy Management System) based equipment from manufacturers like Bosch, Buderus, Nefit, Junkers, Worcester and Sieger

![license](https://img.shields.io/github/license/emsesp/EMS-ESP.svg)
[![donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://www.paypal.com/paypalme/prderbyshire/2)
[![chat](https://img.shields.io/discord/816637840644505620.svg?style=flat-square&color=blueviolet)](https://discord.gg/3J3GgnzpyT)

<span style="font-size: 1.5rem">Current Releases<BR><a href="https://github.com/emsesp/EMS-ESP32/releases/tag/v3.4.4">v3.4.4 Stable</a>
<BR><a href="https://github.com/emsesp/EMS-ESP32/releases/tag/latest">v3.5.0 Development</a></span>

## New Features coming soon in v3.5

The next major release v3.5 is in development and close to final release.

One major new enhancement is the multi language support and we currently have translations for the WebUI and device entities in German, Dutch, French, Swedish, Polish and Norwegian. We are looking for volunteers to help translate to other languages so if you want to help please get in contact with us on Discord.
![login page](_media/screenshot/web_login.png){ width=300, align=right }

Plus there is a new entity customization feature to change the entities that get displayed and sent to home automation systems.

See a [live demo](https://ems-esp.derbyshire.nl/) and the full list of features in the [change log](Version-Release-History#350-current-development-version).

### :warning: Breaking Changes in v3.5 :warning:

!!! warning

    When upgrading to v3.5 for the first time from v3.4 on a BBQKees Gateway board you will need to use the [EMS-EPS Flasher](https://github.com/emsesp/EMS-ESP-Flasher/releases) to correctly re-partition the flash. Make sure you backup the settings and customizations from the WebUI (`System->Upload/Download`) and restore after the upgrade.

## Join Our Community

For feedback, questions, live troubleshooting or just general chat

<a href="https://discord.gg/Ks2Kzd4"><img src="https://discordapp.com/api/guilds/816637840644505620/widget.png?style=banner2"></a>

## Contribute

Everybody is welcome and invited to contribute to the EMS-ESP Project by:

- providing Pull Requests (Features, Proof of Concepts, Language files or Fixes)
- testing new released features and report issues
- donating to acquire hardware for testing and implementing or out of gratitude
- contributing missing [documentation](Contributing.md) for features and devices

## Report bugs and suggest features

Open a new topic on [EMS-ESP discussions](https://github.com/emsesp/EMS-ESP32/discussions)

Report a bug in [EMS-ESP issues](https://github.com/emsesp/EMS-ESP32/issues)