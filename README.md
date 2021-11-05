# plant-monitor-project
## Overview

## Keywords

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
---                      
### Software
* Arduino IDE Arduino IDE 
* CP210*VCPDriver CP210Driver 
* MQTT Explorer MQTT Explore 
* Raspberry pi imager Raspberry 
* Telegraf Telegraf 
* InfluxDB InfluxDB 
* Grafana
## Step
1.Setting up Feather Huzzah ESP8266 Wifi
* Installing the Arduino IDE 1.6.8 or greater
* Installing CP210*VCPDriver
* Installing the ESP8266 Board Package
* Setup ESP8266 Support:CPU frequency-80 MHz, Upload Speed-115200, matching COM port-"SLAB_USBtoUART"
* Connecting via WiFI TestWifi

2.Setting the time on the Feather Huzzah ESP8266
* Installing ezTime library on Arduino
* Printing the time TestTime

3.Schematics and building a plant monitor 
Picture source:Connected environment course

4.Connecting to the MQTT server and publishing soil data to an MQTT server
* Installing MQTT Explorer
* Installing PubSubClient library on Arduino
* Uploading MQTT with nails sketch to send data to MQTT server MQTT with nails
* Connecting MQTT server to see the real time data from your plant monitor

5.Storing data on a RPI gateway
* Installing Raspberry Pi imager
* Select sd card and setup some of the SSH / SSID info
* Insert the card into the RPi and power it up
* Log into the device using SSH

6.Visualising time series data
* Installing the Influx, Telegraf and Grafana
* Setting up Telegraf configuration Telegraf configuration
* Going the address http://hostname.local:3000
* Adding your first datasource-InfluxDB
* Create Dashboard and seeing the data
* Soldering
## Problem and Solution
## Code Improvement
