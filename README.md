# plant-monitor-project
## Overview
* Through this module, learn how to make sensors and receive real-time data in arduino, as well as upload real-time data to the cloud platform（MQTT）, finally visualisation in Grafana
## Things used in this project
### Hardware
* Arduino Feather Huzzah ESP8266	
* DHT22	                          
* Raspberry pi	                  
* Resistor-100	                  
* Resistor-200	                  
* Resistor-10k	                  
* Transistor	                    
* Nails	                    
### Software
* Arduino IDE Arduino IDE 
* CP210*VCPDriver CP210Driver 
* MQTT 
* Raspberry pi 
* Telegraf
* InfluxDB
* Grafana
## Steps
1.Setting up Feather Huzzah ESP8266 Wifi
* Installing the Arduino IDE 1.6.8 or greater
* Installing CP210*VCPDriver
* Installing the ESP8266 Board Package
* Setup ESP8266 Support:CPU frequency-80 MHz, Upload Speed-115200, matching COM port-"SLAB_USBtoUART"
* Connecting via WiFI

2.Setting the time on the Feather Huzzah ESP8266
* Installing ezTime library on Arduino
* Printing the time TestTime

3.Schematics and building a plant monitor 
* my plant monitor![341636197287_ pic_hd](https://user-images.githubusercontent.com/92298865/140608101-f6cbfec5-fe52-49c5-aad9-4bb1de5e615e.jpg)


* my data in arduino![261636131463_ pic](https://user-images.githubusercontent.com/92298865/140608105-6ee165a0-7ec5-4864-aea4-5af5b30f101c.jpg)



4.Connecting to the MQTT server and publishing soil data to an MQTT server
* Installing MQTT Explorer
* Installing PubSubClient library on Arduino
* Uploading MQTT with nails sketch to send data to MQTT server MQTT with nails
* Connecting MQTT server to see the real time data from your plant monitor
![my data in MQTT](https://user-images.githubusercontent.com/92298865/140607624-f70a3f16-63ab-4993-8c94-df3ef6e89c0f.jpg)

5.Storing data on a RPI gateway
* Installing Raspberry Pi imager
* Select sd card and setup some of the SSH / SSID info
* Insert the card into the RPi and power it up
* Log into the device using SSH

6.Visualising time series data
* Installing the Influx, Telegraf and Grafana
* Setting up Telegraf configuration Telegraf configuration
* My address http://stud-pi-ucfncui.local
* Adding my first datasource-InfluxDB
* Create Dashboard and seeing the data
* ![351636197756_ pic](https://user-images.githubusercontent.com/92298865/140608025-c9ee9b75-5acb-4b25-92b1-6253a7cce9ed.jpg)
## Code Improvement
