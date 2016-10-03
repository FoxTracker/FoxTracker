# FoxTracker
--
## Introduction

This is the readme of my hobby-project FoxTracker, which is a headTracking device, which can be used in many games, such as Elite or racing games. It uses a MPU(9axis) to track the position of your head and sends it wireless over wifi to your computer. The device has to be mounted to your head, in best cases your headphones.
**Im a hobbyist, always check for possible mistakes. Im not responsible if anything goes wrong.**
---
##Hardware
*NodeMCU (developmentboard with ESP8266, which can be programmed per USB
*MPU 9255 (9axis gyro) Be aware, there are also MPU9150 and MPUI 9250. I choose MPU925*5*
*TP4056 (Lipo-charging circuit) 
*Lipo Baterie. I chose 100mA. I think 200 would be better
*Switch

###Wiring
Test your circuit on a breadboard first!
* NodeMCU D1 -> MPU9255 SCL
* NodeMCU D2 -> MPU9255 SDA
* NodeMCU 3.3V -> MPU9255 VCC
* NodeMCU GND -> MPU9255 GND
Be careful to wire the charging circuit the right way. Also  change the resistor of this charging service to fit your needs of your Lipo
* NodeMCU GND -> TP4056 OUT-
* NodeMCU Vin -> TP4056 OUT+
 * I attached a switch beween the above connection to switch the device on and off
 
 
 
