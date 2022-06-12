# Distributed-Sensor-Network-PCB-Files
PCB files in eagle PCB format and Gerber for the sensor board of the DSN 
This repository contains the PCB design files for a simple raspberry PI expansion board. 
This design does not comply with the specifications of a RaspberryPi Hat but does support contain the following items:

•	OLED Display to indicate system status: the OLED provides a way to display a simple menu based user interface
•	RFM9x LoRa radio: Provides a network connection to LoRaWAN or other LoRa nodes
•	Global Position System GPS receiver: Allows the node to accurately collect UTC time and date as well as location information of other data captured (GPS)
•	DC power supply input connector: To supply regulated 5VDC to the system
•	LED: Status LED – shows system status at a glance
•	GPIO: 5 of the RaspberryPI GPIO pins have been broken out in a Signal-Voltage-Ground (SVG) layout for connecting to external devices. These can include relays, sensors, switches and so forth.
•	Keypad: A three button keypad for interacting with the OLED menu user interface.
