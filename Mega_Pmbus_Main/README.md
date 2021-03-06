# Mega Nano Board for monitoring PMbus data

* Base on [Mega128L Nano Board](https://github.com/Dafeng1980/AtmegaBoards).  <br/>
* Install the [Andunio IDE](https://www.arduino.cc/en/software "https://www.arduino.cc/en/software") <br/>
* Arduino [Mega128L HW Install](https://github.com/MCUdude/MegaCore "https://github.com/MCUdude/MegaCore").  <br/> 

* Add the Pmbus.ino / Smbus.ino / Twii2c.ino inspired by [Linduino libraries](https://www.analog.com/en/design-center/evaluation-hardware-and-software/evaluation-development-platforms/linduino.html "https://www.analog.com/en/design-center/evaluation-hardware-and-software/evaluation-development-platforms/linduino.html") <br/>

* Modify the "Wire.h", Wire.cpp", add the [Wire.requestFromS](https://github.com/Dafeng1980/PSU_PMbusMonitor/tree/master/doc/Wire "https://github.com/Dafeng1980/PSU_PMbusMonitor/tree/master/doc/Wire") to Support SMbus Wire.requestFrom. 
 > \>  in folder "%USERPROFILE%\AppData\Local\Arduino15\packages\MegaCore\hardware\avr\2.1.3\libraries\Wire\src" <br/>


* [Serial USB Terminal APP](https://play.google.com/store/apps/details?id=de.kai_morich.serial_usb_terminal&hl=en "https://play.google.com/store/apps/details?id=de.kai_morich.serial_usb_terminal&hl=en") for Android Phone.   <br/>

 ### Use Cell Phone to Monitor PMbus with Serial USB Terminal APP: <br/>
![image](https://github.com/Dafeng1980/PowerPMbusTools/raw/master/doc/crps.JPG)
![image](https://github.com/Dafeng1980/PowerPMbusTools/raw/master/doc/crps1.JPG) <br/> 



