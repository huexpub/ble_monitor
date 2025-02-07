
[![hacs_badge](https://img.shields.io/badge/HACS-Default-green.svg)](https://github.com/custom-components/hacs)

# Passive BLE Monitor integration

![BLE_sensors](https://raw.githubusercontent.com/custom-components/ble_monitor/master/pictures/sensors.jpg)

This custom component for [Home Assistant](https://www.home-assistant.io) passively monitors [many different BLE devices](https://custom-components.github.io/ble_monitor/devices) of several different [brands](https://custom-components.github.io/ble_monitor/by_brand). BLE Monitor can also be used as device tracker for BLE devices with a static MAC address or with the UUID.

## Important announcement about the future of BLE monitor

Home Assistant is going to add (improved) support for passive BLE devices directly in Home Assistant in the upcoming releases (most likely starting from 2022.8). For each brand, a core BLE integration will be developed, such that maintanance can be divided over more people, using the latest Bluetooth packages (bleak). I'm working together with the Home Assistant devs to move sensors from BLE Monitor to Home Assistant core integrations. During the transition, BLE monitor will still be available, but it is likely that the core HA Bluetooth integrations will not work niceley parallel to BLE monitor. So my advise, when all your sensors are available in Home Assistant, make the move. The aim is to have all sensors moved into Home Assistant as core integration. After the move, BLE monitor will probably be deprecated. If you want to help moving sensors from BLE monitor, feel free to help. Check out the links below.

**Some interesting links**

- Pypi packages for the BLE parsing will be developed and collected here: https://github.com/Bluetooth-Devices

**In development**

The following integrations are currently being moved/developed as core integrations. 
- SensorPush (https://github.com/home-assistant/core/pull/75531)
- Inkbird (https://github.com/home-assistant/core/pull/75594)
- Govee
- Xiaomi
- Moat

**Done**

The following integrations are available as official Home Assistant integration.
- None

## More info

- [Documentation](https://custom-components.github.io/ble_monitor/#introduction)
- [Installation instructions](https://custom-components.github.io/ble_monitor/Installation)
- [Configuration](https://custom-components.github.io/ble_monitor/configuration_params)
- [Supported devices](https://custom-components.github.io/ble_monitor/devices)
- [Parse_data from ESPhome](https://custom-components.github.io/ble_monitor/parse_data)
- [DIY sensors](https://custom-components.github.io/ble_monitor/ha_ble)
- [FAQ](https://custom-components.github.io/ble_monitor/faq)
- [New sensor request](https://custom-components.github.io/ble_monitor/sensor_request)
- [Developer documentation](https://custom-components.github.io/ble_monitor/developer_docs)
- [Forum](https://community.home-assistant.io/t/passive-ble-monitor-integration/)
- [Report issues](https://github.com/custom-components/ble_monitor/issues)

## Supported sensor brands

![BLE_sensors](https://raw.githubusercontent.com/custom-components/ble_monitor/master/pictures/sensors_2.png)

- Acconeer
- Air Mentor
- ATC (custom firmware for Xiaomi/Qingping sensors)
- BlueMaestro
- Brifit
- b-parasite
- Govee
- HA BLE
- HHCC
- Inkbird
- iNode
- Jinou
- KKM
- Kegtron
- Mikrotik
- Moat
- Oral-B
- Qingping
- Relsib
- Ruuvitag
- Sensirion
- SensorPush
- SmartDry
- Switchbot
- Teltonika
- Thermoplus
- Thermopro
- Tilt
- Xiaogui (Scale)
- Xiaomi (MiBeacon)
- Xiaomi (MiScale)
