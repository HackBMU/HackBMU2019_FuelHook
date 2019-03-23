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
1.	Flow Sensor—to measure the amount of fuel filled in the automobile.
2.	GPS Module—to provide real time location of the automobile.
3.	Arduino—accepts data from Flow Sensor and GPS Module. 
4.	GSM Module—takes input from Arduino and sends the data to the registered mobile number of the user.
5.	7-segment display array—real time display of the amount of petrol filled as measured through the device.

Main Software Components:
1.	Arduino IDLE—Open-source Arduino Software (IDE).
2.	ThingSpeak—Open Source IOT platform.
