# Temperature Node
Distributed node that runs on battery and sends temperature wirelessly via 
Bluetooth. 

## Requirements
These are the requirements that the unit should fulfill.

1. Shall run on battery power.
2. Shall work for at least two weeks.
3. Shall speak wirelessly via bluetooth.
4. Shall tell temperature with a simple serial message.

## Needed modules
These are the abstract units needed.

1. Power supply unit.
2. Microprocessor.
3. Temperature sensor.
4. Bluetooth module.

## Hardware
This is the hardware available.

1. DC-DC switching regulator MC33063 ([Datasheet](http://www.farnell.com/datasheets/1862376.pdf?_ga=1.207761298.1201322026.1473664451)).
2. Atmel Atmega 328P ([Datasheet](http://www.atmel.com/images/Atmel-8271-8-bit-AVR-Microcontroller-ATmega48A-48PA-88A-88PA-168A-168PA-328-328P_datasheet_Complete.pdf)).
3. Temperature and humidity sensor LMT84 ([Datasheet](http://www.ti.com/lit/ds/symlink/lmt84.pdf)).
4. HC-05 bluetooth module ([Datasheet](http://elecfreaks.com/store/download/datasheet/Bluetooth/HC-0305%20serail%20module%20AT%20commamd%20set%20201104%20revised.pdf)).
