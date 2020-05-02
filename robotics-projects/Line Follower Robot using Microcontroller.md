
## Project: Line Follower Robot using Microcontroller
### Components in the circuit
8051 Microcontroller
Development Board for 8051 Microcontroller (preferred)
10KΩ Resistors X 2
10µF Capacitor
11.0592MHz Crystal
33pF Capacitors X 2
Push Button
Motor driver Module (L298N)
Robot Chassis with Motors
IR Sensors x 2

#design
8051 microcontroller is the main component of the project. It is an 8 bit microcontroller with 32 programmable I/O pins. The DC motors of the robot are connected to the controller using a motor driver IC because the output produced by m.controller is very small it cannot drive the motors. So, to amplify this voltage motor driver IC is used. L298N can drive motors up to 36v and can provide a drive current of 3A.The driver IC has 15 pins and is usually available in multiwatt15 Package. These ICs are easily available in the market as Modules. The inputs to the Motor Driver Module are connected to PORT2 pins P2.0, P2.1, P2.2 and P2.3.The two IR sensors are connected to P2.6 and P2.7 pins of the microcontroller.



circuit diagram:


![](https://www.electronicshub.org/wp-content/uploads/2015/10/Line-Follower-Robot-using-Microcontroller-Circuit-Diagram.jpg)


![](https://www.electronicshub.org/wp-content/uploads/2015/10/Line-Follower-Robot-using-Microcontroller-Image-3.jpg)

link:https://www.electronicshub.org/wifi-controlled-robot-esp8266-arduino/
