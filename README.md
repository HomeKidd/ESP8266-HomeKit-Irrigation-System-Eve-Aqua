# Native  Homekit support for ESP8266 based [Wi-Fi Smart Valves](https://s.click.aliexpress.com/e/_ANIf7J) that acts like a real Eve Aqua 💦🚰
------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-Irrigation-System-Eve-Aqua/total?color=green)](https://github.com/HomeKidd/ESP8266-HomeKit-Irrigation-System-Eve-Aqua/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-Irrigation-System-Eve-Aqua?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-Irrigation-System-Eve-Aqua/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>

# For usage and more information please read the [Wiki page](https://github.com/HomeKidd/ESP8266-HomeKit-Irrigation-System-Eve-Aqua/wiki/)!

**This HomeKit enabled Valve works the same as [Elgato Aqua](https://www.evehome.com/en/eve-aqua)!** 

# Currently in beta phase! So HomeKit code is 111-11-111 and LED's GPIO changed for GPIO2 -> ESP12 built-in LED!! 👷‍

**Features:**

* **Irrigation Valve HomeKit accessory**
* Turning the Irrigation ON/OFF
* Watering duration from 10 seconds to 4 hours
* Water Consumption _(via Eve app)_
* Flow rate _(used for calculating water consumption)_
* Child Lock _(via Eve app)_
* ~~Watering history _(via Eve app)_~~ Still work in progress 👷‍
* ~~Schedules _(via Eve app)_~~ Still work in progress 👷‍
* Downloadable user manual _(via Eve app)_
* Power / Reset button
* **Supported Device(s): [BQ-05 Smart Valve](https://s.click.aliexpress.com/e/_ANIf7J), [Sonoff Basic](http://s.click.aliexpress.com/e/cXfl15k4)**

**Demo:**

[![](http://img.youtube.com/vi/TG9xq7itfwh0k/0.jpg)](http://www.youtube.com/watch?v=TG9ffxq7ith0k "Demo Video")
<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Irrigation-System-Eve-Aqua/raw/main/images/irrigation.jpg" class="center" width="500"/>

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2020 Apple Inc. All rights reserved.
