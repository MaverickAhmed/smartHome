# Project Asani
A dual-mode IoT control hub (cloud + local) using ESP32/MQTT, integrating AWS IoT Core
while maintaining offline operation for resilience.

# Installation Steps
Follow the steps below to get a local copy of the project up and running on your machine.

---------
### 1. Cloning
```
git clone https://github.com/MaverickAhmed/smartHome.git
```
Alternatively you can download the ZIP from the top of this page.

### 2. Arduino IDE
Download and then install the Arduino IDE from [here](https://www.arduino.cc/en/software/)

### 3. ESP-8266 Module Setup on IDE

Start Arduino IDE, go to File > Preferences
Add the following link to the Additional Boards Manager URLs: 
```
http://arduino.esp8266.com/stable/package_esp8266com_index.json
```
```
Click Tools > Boards menu > Boards Manager, search for ESP8266 and install ESP8266 platform from ESP8266 community (and don't forget to select your ESP8266 boards from Tools > Boards menu after installation)
```
To install additional ESP8266WiFi library:
```
Click Sketch > Include Library > Manage Libraries, search for ESP8266WiFi and then install with the latest version.
```
