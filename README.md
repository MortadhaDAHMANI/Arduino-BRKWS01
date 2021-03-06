Arduino-BRKWS01
========
MAMDSig Library is made for Breakout Sigfox BRKWS01 kit and support WISOL SFM10R1 chip. 
This library lets you connect to the Sigfox network

## Supported devices
* BRKWS01 module (using WISOL SFM10R1 chip)

## Hardware
#### Breakout Sigfox BRKWS01
* [Breakout Sigfox](https://yadom.fr/carte-breakout-sfm10r1.html "Breakout Sigfox")

<p align="center">
<img src="https://raw.githubusercontent.com/MortadhaDAHMANI/Arduino-BRKWS01/master/yadom.jpg">
</p>

* [Pinout Sigfox]

<p align="center">
<img src="https://raw.githubusercontent.com/MortadhaDAHMANI/Arduino-BRKWS01/master/pinout.png">

</p>

#### BRKWS01 Circuit Diagram
* [Circuit Diagram](https://yadom.fr/downloadable/download/sample/sample_id/160/ "Circuit Diagram")

![Alt Text](https://raw.githubusercontent.com/MortadhaDAHMANI/Arduino-BRKWS01/master/wiring.png)

#### BRKWS01 AT Commands
* [AT Commands](https://yadom.fr/downloadable/download/sample/sample_id/199/ "AT Commands")

## Software
#### 1. Install MAMDSig Library
##### Arduino IDE 1.8.x

* Download all files and extract onto the "My Documents\Arduino\libraries\" folder in your project in sketch.

Or (recommended)

* To use a library in a sketch, select it from Sketch > Import Library (Zip file).

#### 2. AT Commands
```
AT$T?              // Get the current temperature
0272               // 27.2°C

AT$V?              // Get the current Voltage
3305               // 3.305V current Voltage
3325               // 3.325V last transmission Voltage


```

## Revision History
* Initial Release : 11 June 2018
* This version has been adapted: Mr Med Ali Mortadha DAHMANI, 2018.
