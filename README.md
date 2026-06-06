# smarthome
Detailed Description

This project presents a complete Smart Home Automation System based on the ESP8266 microcontroller. The system communicates with an MQTT broker to remotely control six home appliances through relays and monitor environmental conditions using a DHT22 temperature and humidity sensor. The platform integrates with Node-RED for real-time visualization, automation, and remote management.

The ESP8266 connects to a Wi-Fi network, subscribes to MQTT topics, and controls six relay channels corresponding to different rooms and outdoor lighting zones. Sensor data is periodically transmitted to the MQTT broker, enabling real-time monitoring through dashboards and mobile interfaces. The project also supports OTA (Over-The-Air) firmware updates for easier maintenance and upgrades.

Key Features
Remote control of 6 electrical devices via MQTT.
Real-time temperature monitoring.
Real-time humidity monitoring.
Wi-Fi connectivity using ESP8266.
Node-RED dashboard integration.
MQTT publish/subscribe communication.
Over-The-Air (OTA) firmware updates.
Smart lighting automation.
Low-cost IoT home automation solution.
