
### Project:How to Update Flash ESP8266 Firmware
link:https://www.electronicshub.org/update-flash-esp8266-firmware/

Circuit:
Circuit Diagram for Flashing the Firmware to ESP8266:
![](https://www.electronicshub.org/wp-content/uploads/2017/12/Flash-ESP8266-Firmware-Image-11.jpg)

Checking the Current Firmware Version:
we will first check the existing firmware in the ESP8266 Module using serial communication.For this, we need to disconnect the GPIO0 pin from GND. *IMPORTANT*.  
In Arduino IDE, select the correct COM Port and open the Serial Monitor. Set the baud rate to 115200 and select Both NL and CR option in the serial monitor. After this press the RST Button of the ESP8266 for a second and release. The ESP8266 Module will reset and display “ready” after some garbage data on the serial monitor.
![](https://www.electronicshub.org/wp-content/uploads/2017/12/Flash-ESP8266-Firmware-Image-1.jpg)

To check version type AT(AT+GMR) command and hit enter .it will return the firmware version of the ESP8266 Module.
![](https://www.electronicshub.org/wp-content/uploads/2017/12/Flash-ESP8266-Firmware-Image-2.jpg)


 ### To Update 
 first dowenload latest firmwere.In order to flash the firmware in ESP8266, first open the Flash Download Tool or the Flasher Software of ESP8266.you need to select the firmware files that you need to install. You need to upload four files at four different addresses 
 to further steps visit :https://www.electronicshub.org/update-flash-esp8266-firmware/#Installing_the_Firmware_in_ESP8266
