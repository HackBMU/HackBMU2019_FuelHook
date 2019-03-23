# HackBMU2019_FuelHook

Fuel Hook is an IOT based comprehensive vehicle fuel monitoring system. 
The device accurately tracks the fuel transactions/exchanges taking place within the vehicle. 
This helps the user identify fuel theft occurring during refills and otherwise. 
This involves a systematic approach which includes measuring the fuel 
supplied to the automobile and comparing it with the self-proclaimed readings of the distributor. 
The system compares the readings instantaneously and provides the consumer with the amount of stolen fuel.
We intend to keep track of the GPS location of the times when the consumer refills his/her vehicle. 
This way the user will be able to access the exact location as well.

Main Hardware Components:
1.	Flow Sensor
2.	GPS Module
3.	Arduino
4.	GSM Module
5.	7-segment display array

Main Software Components:
1.	Arduino IDLE
2.	ThingSpeak

We have used flow sensor(YFS 201)by which we are measuring the quantity of the flowing liquid. This has been connected to Wifi Module: NodeMCU(ESP 8266) which uploads the data on ThingSpeak(an online open-source platform on which we can store this data). We have experimented upon the flow sensor and the readings obtained are seen through the NodeMCU and this reading can also be seen upon the serial monitor as well as online on ThingSpeak website.This code is in file FLOW_SENSOR_ONLINE_UPLOAD.ino file
We are taking readings from GPS(Global Positioning System) Module and printing them on serial moniter in Arduino IDLE software. This code is in GPS_MODULE.ino file
