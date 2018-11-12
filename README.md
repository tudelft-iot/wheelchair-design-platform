# Wheelchair Design Platform

The Wheelchair Design Platform is a set of hardware and software component which facilitate the deployment of  sensing and actuating capability on a Wheelchair. It aims at supporting designer through the exploration of relevant and novel products and services around wheelchairs.

This platform uses two programming languages, Python on computers and C on micro-controllers. While descriptions and examples of code should help you get started, you can find some additional resources [here](https://github.com/tudelft-iot/wheelchair-design-platform/blob/master/doc/software-resources.md "Python and C resources") .

Note: the design of this platform focus on flexibility and technology exploration rather than optimisation.

## Main Components

The main design includes an Arduino Mega and a Raspberry Pi on the main frame.

The Arduino Mega is a microcontroller. Fixed on the main frame of the wheelchair, it can collect data from sensors (e.g. forces, accelerometers) and trigger actions (e.g. LEDs, vibration motors).

More on the Arduino Mega here.

The Raspberry Pi is a small computer. Also fixed on the main frame of the wheelchair, it can
* interact with the Arduino Mega via USB to receive data and transmit command
* interact with the Internet to receive data and transmit command
* store data locally in files;
* run (machine learning) algorithms.

More on the Raspberry Pi here.

## 