[[2023-06-14]] - [[2023-06-28]]


### Branding
We started our brainstorming ideas for our [[Branding]].

As two high-schoolers looking to brand their passion project, we had multiple criteria for the aesthetic of our brand. We decided on Project Palsy since it was simple and reflected our goals at their core motives.

Some ideas:

![[logo1.png]]
*minimalistic aesthetic*
![[logo2.png]]
*futuristic aesthetic*

### Hardware

The IMU we chose for this project was the MPU6050 since it struck a good balance between features, accuracy, and price. It has the ability to sense acceleration as well as rotation in six axis, affording us creative freedom in designing our therapy game. 

![[mpu6050.png]]
*3 Axis Accelerometer Gyroscope Module 6 DOF 6-axis Accelerometer*

For our first prototype, we decided to the the Arduino Uno R3, which allowed us to easily prototype our first iteration of the circuit. However, it comes with the drawback of missing the ability to USB output which limits it's use to just serial outputs. 
![[mcus.jpg]]
*Arduino Uni, Metro Mini, Pi Pico, Pro Micro*

In order to interface with the IMU, we used Adafruits MPU6050 library which made gathering the data from the sensor easier.
![[imutest.gif]]
*IMU testing with serial monitor*

### Software
