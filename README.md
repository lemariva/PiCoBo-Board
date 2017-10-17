# PiCoBo-Board 

**PiCoBo** is a multi-target board. I designed it using the **MSP430G2553** (20/28 pin version), which is part of the MSP430 Texas Instruments family of ultra-low-power microcontrollers. 

The board includes also a **CP2102** which can be used for communication over UART. 

The board can be supplied using a C2032 battery, over USB or external DC source up to 10V. It uses a **TPS77301DGK** to regulate the max. voltage of 3.6V needed for the MSP430. 

Up to three **IRLL2705** can be soldered to the board to switch on/off directly (or using PWM) voltages up to 55V and 3.8A. Additionall multiple pinouts are available to connect external sensors (e.g. **DHT11**), servo motors, leds etc. For testing uses it can be programmed using the MSP430G2553 LaunchPad.

Applications
-------------------
* Ultra-low-power sensor: 
	* Temperature
	* Humidity
	* Air quality
	* Light condition
	* Door or window open/close status
	* etc
* Servo controller
* RGB LED controller
* X actuator
* etc

PCB Boards
-----
![PCB Boards](https://raw.githubusercontent.com/lemariva/PiCoBo-Board/master/pics/PiCoBo_boards.png)

More Info: 
-------------------

* Blog article related to this project: https://goo.gl/yuvsjp
* Code example: https://goo.gl/CPGcYK
* Datasheet MSP430G2553: http://www.ti.com/product/MSP430G2553

Changelog
-------------------
* Revision: 1.1v

License
--------------------
Apache 2.0