# Home Assistant Configuration

That's nothing more but my [Home Assistant](https://www.home-assistant.io/) configuration for the smart home playground. It is a kind of hobby fun project without any advanced value or automation, but maybe things would change some day. 

In my setup, Home Assistant runs in Docker on my old Mac Mini Late 2012 (Core i7, 16 GB RAM, 256 GB SSD). See [docker-compose.yaml](docker-compose.yaml) for details. Host network mode is needed for UDP multicast discovery used by several devices.

## Devices 

Below you can find the list of all devices I have in my Home Assistant setup at the moment.

* 5 x [Amazon Echo](https://www.amazon.com/smart-home-devices/b?ie=UTF8&node=9818047011);
* 1 x [Netatmo Smart Thermostat](https://www.netatmo.com/en-eu/energy/thermostat);
* 1 x [Netatmo Smart Home Weather Station](https://www.netatmo.com/en-eu/weather/weatherstation);
* 1 x [Apple TV 4K](https://www.apple.com/apple-tv-4k/);
* 1 x [Hikvision DS-2CD2112-I](https://hikvision.ru/product/ds_2cd2112_i);
* 1 x [TP-Link TL-NC250](https://www.tp-link.com/latam/home-networking/cloud-camera/nc250/);
* 1 x [Broadlink RM Pro](https://www.ibroadlink.com/products/ir+rf) which controls: 
    * 1 x Samsung AC;
    * 1 x LG TV;
    * 1 x LG Soundbar;
    * 7 x [Livolo RF Switch](https://www.livoloeurope.eu/);
* 1 x [Mikrotik 951Ui-2HnD](https://mikrotik.com/product/RB951Ui-2HnD);
* 1 x [Apple Airport Extreme](https://support.apple.com/airport);
* 1 x [SmartMAC D101-21](https://smart-mac.com/en/) Energy Monitor;
* 2 x [SmartMac D105](https://smart-mac.com/en/) Universal Meter via MQTT for:
    * Natural gas;
    * Cold water;
* 2 x [Broadlink SP3-EU](https://broadlink.ru/broadlink-sp3-) Plug;
* 1 x [Xiaomi Roborock S5 Max](https://us.roborock.com/pages/roborock-s5-max);
* 1 x Zigbee CC2531 USB Stick](https://www.itead.cc/cc2531-usb-dongle.html) which controls:
    * 1 x [Xiaomi Door Sensor](https://xiaomi-mi.com/sockets-and-sensors/xiaomi-mi-door-window-sensors/);
    * 2 x [Xiaomi Occupancy Sensor](https://xiaomi-mi.com/sockets-and-sensors/xiaomi-mi-occupancy-sensor/);
    * 1 x [Xiaomi Wireless Switch](https://xiaomi-mi.com/sockets-and-sensors/xiaomi-mi-wireless-switch/);
