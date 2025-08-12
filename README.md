# Hand-Gesture-Controlled-Car
Designed using Arduino Nano and Arduino Uno, integrated with NRF24L01 and L298N  and MPU9252 for gesture-based wireless control.

Where The One Side Was  Transmitter Side in which Arduinoa Nano  connected  MPU9250  Which is Gyroscopic accelerometer  also connectedto nRF24L01 For Transmitting Data . 
The Other Side Was Arduino Uno connected with  nRF24L01 which gives The data sent From transmitter side and  L298N motor driver is connected to Uno .
So when The Tranmitter side is moved The coordinates are changed and accordingly this data is given to arduino nano by MPU9250 then this data is forwarded to nRF24l01 of Transmitter's side.
then This data is transmitted to nRF24l01 of receiver's side then this data is given to arduino uno and after processing this data is forwarded to L298N Motor Driver and 4 dc motors are connected to L298N are moving in differnt Directions as Instructed . 
here also battery of 3.7v x 3 are connected on receiver's side for power supply and transmitter side is connected to laptop for power supply
