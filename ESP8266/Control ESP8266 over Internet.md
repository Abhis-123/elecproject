## Project:controlling ESP8266 over internet

in  this project it is explained how can we control a ESP8266 over internet
### Components Required
Arduino UNO (as USB to Serial Converter)
ESP8266 (ESP-01) WiFi Module
Slide Switch (SPDT Switch)
Push Button
1 KΩ Resistor (1/4 Watt)
2.2 KΩ Resistor (1/4 Watt)
330 Ω Resistor (1/4 Watt)
LED
Connecting Wires
Mini Breadboard

#### circuit diagram
![](https://www.electronicshub.org/wp-content/uploads/2018/03/How-to-Control-ESP8266-Over-Internet-Circuit-Diagram.jpg)

#### working 
Firstly code is uploaded and to do this slide the GPIO0 pin to programming mode (connect GPIO0 to GND) and press the RESET Switch. After selecting the correct board and port in the Arduino IDE, upload the code.
After uploading code switch slide the switch to normal mode and push the RESET button once.In serial moniter you can see the details of 
the wifi connection  and Url for controlling the ESP8266 .This is way of controlling ESP8266 over wifi to control over internet we can use 
port forwarding .After port forwarding one can open url from any browser by adding esenssial details(for ip accessing ).
