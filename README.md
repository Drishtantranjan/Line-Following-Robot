
# Line Following Robot (Arduino)

The line follower robot is an automated vehicle that follows a visual black line or path on the surface. This visual line is a path on which the line follower robot moves. It uses a black line on a white surface, or you can also adjust it as a white line on a black surface as per your need.




## Images
![alt text](https://i.ytimg.com/vi/5xP51VIVvyM/maxresdefault.jpg)
## Circuit Working

The concept of the line follower robot is related to the transmitting and receiving of light. The white colour reflects all the light that falls on it whereas the black colour absorbs all the light.

In this line follower robot, we have used IR transmitters and receivers ( also known as photodiodes). When IR light falls on a white surface, it gets reflected back towards the IR receiver, generating some voltage changes that are analyzed by the Arduino.

When IR light falls on a black surface, it gets absorbed by the black surface, and no rays are reflected back thus, the IR receiver doesn’t receive any rays.

In this project, when the IR sensor senses a white surface, an Arduino gets HIGH as input, and when it senses a black line, an Arduino gets LOW as input. Based on these inputs, an Arduino Uno provides the proper output to control the line follower. 

![alt text](https://www.electrovigyan.com/wp-content/uploads/2021/04/Circuit-diagram-1116x628.jpg)


## Components Used

- Arduino Board (UNO)
- USB –A to micro-USB cable
- Car chassis
- L298 motor driver module
- IR sensor module
- 12V Battery
- On-Off- Switch
- DC Female Connector Jack 
- Connecting wires
- Soldering iron
- Solder wire
- Hot Melt Glue Gun

## Software

- Arduino IDE

## Language Used
- C++
- Embeded C


