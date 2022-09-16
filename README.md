# AI-Automated-Vechile
How to program an automated Disinfectant Spraying Robot

Aim: To build an autonomous disinfecting robot with advance functionalities.
Components: To achieve this design, the following components will be used;

1. Arduino Mega: Micro controller for storing codes for robot functionalities. 
2. Raspberry Pi: Will be connected to Arduino Mega using serial communication RX and TX pins.
3. Camera: It will be used for facial recognition. Raspberry Pi will be used in the coding of camera, using an open source library called Open CV.
4. Motor Driver (x3) Functionality: Two of which will be for Controlling the DC motors for the wheels and the other for the alcohol sprayer pump. 
5. Voltage Regulators (x2): Functionality: Maintains the voltage of the power source within acceptable limits for the arduino and motor drivers. 
6. DC Pump: For passing the disinfectant to the sprayer.
7. Cables: LIDAR cable (105cm x 3) Gyro Cable (53cm x 5).

Sensors
In the implementation of this design the following sensors will be used;

1. LIDAR
Functionality: To detect every structure and obstacle around the robot and detect
their distances.
Types:LIDAR LiteV3,V4 common types
Voltage Consumption:4.75V-5.25V DC
Current Consumption: <700mA

2. Gyro Sensor
Functionality:With gyro sensor we will make our robot turn at any angle. We can also
calculate the angular and linear velocity of the robot.( linear X and angular Z Features
Sensor type: MPU6050
Voltage consumption:3-5 Volt
Communication Protocol:I2C

3. DC motor
Functionality: DC motor will be put under the LIDAR to make it turn 360.Thus,
LIDAR can detect objects in front and behind.

4. IR Sensors (x2): To detect obstacles that are close and short.
Sensor range: Approximately 10cm.
