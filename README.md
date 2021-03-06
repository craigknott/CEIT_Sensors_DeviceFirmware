CEIT_Sensors_DeviceFirmware
================
New firmware by Craig Knott, panStamp devices created by Daniel Berenguer www.panstamp.com

This repository contains firmware for modifications made to panStamp battery boards already containing TEMT6000 temperature sensors.

temphumpresslight
===
This is a temperature sensor and light intensity sensor using the freetronics light sensor (TEMT6000)

Installation:
```
  Connect the sensors VCC to pin D9 on the panstamp
  Connect the sensors GND to GND on the panstamp
  Connect the sensors OUT to pin A0 on the panstamp
  Open the temphumpresslight code in arduino and flash the panstamp with it.
```
temphumpressspl
===
This is a temperature and sound pressure level sensor using the freetronics microphone

Installation:
```
  Connect the sensors VCC to pin D7 on the panstamp
  Connect the sensors GND to GND on the panstamp
  Connect the sensors SPL to pin A5 on the panstamp
  Open the temphumpressspl code in arduino and flash the panstamp with it.
```
PIR motion detector
===
This is a motion detector using the SEN-08630 PIR motion detector

Installation:
```
  Connect the sensors VCC to pin D9 on the panstamp
  Connect the sensors GND to GND on the panstamp
  Connect the sensors OUT to pin D8 on the panstamp
  Solder a jumper wire from the Vin to the Vout of the voltage regulator
  Solder a resistor (4K+) from VCC to OUT.
  Open the PIR code in arduino and flash the panstamp with it.
```  
  
For the above ensure any communicating devices have the config files located in the config folder.
