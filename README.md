#Project:  I2CArduino

###Description

I2C is a convenient communication protocol for peripheral sensors and actuators connected to a RoboRio.  Many industrial sensors and actuators are packaged as I2C devices.  However, some devices, like the HC-SR04 distance sensor, is not packaged in a way that is compatible with the RoboRio.  The motivation for this project is to enable a the team to use Arduino boards as an interface to these devices where the communcation with the RoboRio is established through I2C protocol.  This project is a base project to program an Arduino to be an I2C device that can be controlled by a RoboRio controller.  

###Typical Use
Typically, this project would be forked and the forked project would address a specific use for a particular season.

   note: __Project not yet ready for forking__

###Credits & Additional reference Material
This project is based on an awesome tutorial  by Wayne Truchsess that was published in 2012.  This tutorial can be found at http://dsscircuits.com/articles/arduino-i2c-slave-guide and is well worth the read.  It explains basic concepts.  I will assume the reader is familiar with the tutorial and basic I2C concepts. 

###Arduino Models
The project has been compiled and tested on the following Arduino boards: 
+   Uno
+   MiniPro

See [MDHS Wiki](https://github.com/MDHSRobotics/TeamWiki/wiki/) for instructions.
