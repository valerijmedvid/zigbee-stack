# Zigbee stack

### Hardware
- Raspberry Pi 4 Model B - 4GB RAM
- CC2531 USB Sniffer module
- Zigbee devices (buttons, bulbs, temperature & humidity sensors) -> [List of supported devices](https://www.zigbee2mqtt.io/supported-devices/)


### Software
- **Eclipse Mosquitto** like MQTT broker - [mosquitto](https://mosquitto.org/)
- **Zigbee2MQTT** for communication between antenna and MQTT broker - [zigbee2mqtt](https://www.zigbee2mqtt.io/)
- **Node-RED** creating automation visually - [node-red](https://nodered.org/)
- **Home Assistant** better UI for smartHome. A lot of plugins and integrations - [homeassistant](https://www.home-assistant.io/)
- **MariaDB** saving stats, logs from Home Assistant - [mariadb](https://mariadb.org/)