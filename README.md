# WATTx-Heating-Control
Prototype of a simple heating control

## Description of the problem and solution
Prototype a simple heatin control system. A radiator valve needs to be opened or closed in order to keep the room temperature at 22 ºC.

*Input: periodic temperature readings in json format for a few sensors in the room

*Output: Analogue value for the valve openness in json format

## Technical choices reasoning
An hysterisis comparator is implemented. The value of the sensors is averaged and if the average temperature value is below 21 ºC, the radiator is fully opened. When the average value is higher than 23ºC, the valve is fully closed.

## Future lines of work
*You can imagine that there's also a motion sensor and you want to keep the room warm only when motion is present.

*You can imagine there are a lot of rooms! And the sensors and valves should be controlled on per room basis.

*You can imagine any other limitations you think would be fun to work with.
