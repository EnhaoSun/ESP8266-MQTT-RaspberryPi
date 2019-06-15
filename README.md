# ESP8266-MQTT-RaspberryPi
Use ESP8266MOD AI-THINKER as client sending data collected by DHT22 sensor to Raspberry pi.
And use Python Flask to dynamically display the received data in a web page.

P.S: I did this project in 2017 summer. The code was almost lost now. If I have time, I will do it again and try to upload it.

## To do this you will need:
* Raspberry Pi desktop setup
* One DHT22 sensor
* Some jumper
* Breadboard

## The process is below:
1.	Wire esp8266 with DHT22 sensor on breadboard
2.	Configure Raspbian
3.	Run server program on Raspbian
4.	Upload scratch to esp8266 using Arduino IDE
5.	Raspbian receive message from esp8266

## STEP 1: Connect a DHT22 sensor to ESP8266
In this section, use the breadboard and jumper wires to make the connection as follows.

![](ESP8266-DHT22.png)

For sensor pins, use following wiring:
| Sensor | ESP8266 | Cable |
| VCC(3.3-5v) | VCC(3V) | Blue |
| DATA | GPIO 2 | Red |
| GND | GND | Black |
