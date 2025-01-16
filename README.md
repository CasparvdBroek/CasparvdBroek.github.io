# Developer 
	Hi - I am Caspar van den Broek an enginner from Russell New Zealand. I have listed some of my projects which maybe of use to others. The hope is that additional users will help improve the projects for all.
	
# Project -   [BLEtoMQTT](https://github.com/CasparvdBroek/BLEtoMQTT/)
	Android Application BLE MQTT IOT HomeAssistant	
	
Android foreground service to provide a bidirectional bridge between BLE devices and an MQTT broker. A setup.json file defines MQTT parameters and BLE MAC addresses to scan for.

For each BLE device detected BLEtoMQTT will discover all exposed services and characteristics creating MQTT topics for each. Those characteristics which are writeable will automatically be 'subscribed' from the MQTT broker.

Two external libraries are used :

org.eclipse.paho:org.eclipse.paho.client.mqttv3:1.2.5
com.github.weliem:blessed-android
The author uses this application to connect remote custom ESP32 devices to his Home Assistant server via a Zerotier VPN. The GitHub repository contains an example setup.json and a prebuilt apk used to monitor/control a boat on a mooring or at anchor.

The app has been tried on Samsung S6, S9, S9+ and 'Galaxy Tab A'. Running Android 7.0, 10 and 11.	

