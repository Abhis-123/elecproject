
## Project:Internet Speedometer
Plan:-
In this project we are measuring speed with latency.Latency is the time delay between sending the request and getting the response and 
so it cannot be the actual representation of the internet speed.We will do this by SNMP (simple Network Management Protocol) it is way to communicate with wifi and we are using NodeMCU to connect to the WiFi Router.
steps:-
1.Send a request to the router 'requesting' the required data
2.Get the response from the router
3.Analyse the response and parse the required data from it
4.Convert the 'raw' data into understandable information
5.Generate voltage proportional to the internet speed for the meter
6.Repeat

we can use DAC or Digital to Analog Converter for controlling the meter.
the final look(or prototype):
![](https://content.instructables.com/F19/3Y5J/K9D1OJCV/F193Y5JK9D1OJCV.LARGE.jpg?auto=webp&frame=1&width=875&height=1024&fit=bounds)
