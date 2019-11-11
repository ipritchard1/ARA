# ARA

The AnthroDrive Robotic Actuator (ARA) is an all-in-one (AIO) solution for actuating walking robots. ARA has been developed with the goal of actuating bipedal anthropomorphic robots, but could be adapted for use on other platforms such as quadrupeds.

The unit is comprised of a brushless gimbal motor, 8:1 planetary reducer, and a controller board. 3D-printed components allow for rapid prototyping and low cost, while keeping the overall weight of the actuator low.

ARA will be utilized on my upcoming anthropomorphic robot platform.

The reducer element is a modified version of the OpenTorque Actuator developed by Gabrael Levine (https://hackaday.io/project/159404-opentorque-actuator). A carrier-driven compound planetary (CDCP) version is also in development, with the aim being to reduce the footprint of the actuator.

The controller board is a modified version of the DirectServo BLDC motor driver (https://hackaday.io/project/28512-bldc-motor-driver-for-robotics). A high-current model is in development, with the goal of supporting higher power BLDCs and multicopter motors, as well as the gimbal motors it was designed for.
