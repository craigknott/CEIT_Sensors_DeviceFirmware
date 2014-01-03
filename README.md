panstamp_devices
================

modified code to panstamp battery board devices to work with other sensors.

temphumpresslight
=================
 Uses the freetronics light sensor (TEMT6000)
 Installation:
  Connect the sensors VCC to pin D9 on the panstamp
  Connect the sensors GND to GND on the panstamp
  Connect the sensors OUT to pin A0 on the panstamp
  Open the temphumpresslight code in arduino and flash the panstamp with it.

temphumpressspl
=================
 Uses the freetronics microphone
 Installation:
  Connect the sensors VCC to pin D7 on the panstamp
  Connect the sensors GND to GND on the panstamp
  Connect the sensors SPL to pin A5 on the panstamp
  Open the temphumpressspl code in arduino and flash the panstamp with it.
  
For the above ensure any communicating devices have the config files located in the config folder.
