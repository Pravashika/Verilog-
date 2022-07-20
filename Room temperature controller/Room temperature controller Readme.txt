Design & simulation of controller blocks using verilog:

The aim of project is to develop a Verilog behavioral model for a room
environment controller with the following specifications:
1. It turns on a heater when the room temperature drops below 15 degrees Celsius.
2. Once the room heater is turned on, it is turned off only when the room temperature exceeds 18
degrees Celsius. Once turned off, the heater is turned on again only when the temperature drops
below 15 degrees Celsius.
3. If the room temperature exceeds 23 degrees Celsius, then the fan is switched on.
4. Once the fan is switched on, it is switched off only when the temperature drops below 22 degrees
Celsius. Once switched off, it is switched on again only when the temperature exceeds 23 degrees
Celsius
5. If the temperature exceeds 27 degrees Celsius then the Air Conditioner (AC) is turned on.
6. If the temperature drops below 23 degrees Celsius, then the AC is switched off. Once the AC is
switched off, it is switched on again only when the temperature exceeds 27 degrees Celsius.
Note: The temperature, in degrees Celsius, is provided as a 6-bit unsigned binary input to the
controller
Expectation: 
a). Draw the Venn diagram for the controller (a Moore machine)
b). Develop a purely behavioral Verilog module for the controller 
c). Write a functional verification test bench for the controller to test the correctness of the
functionality of the controller against the natural language description of the controller provided
above