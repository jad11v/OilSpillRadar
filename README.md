# OilSpillRadar
## Radar System for Oil Spill Analysis 
### A PHP, Javascript, and MySQL web application to present data from, and interact with a series of python and bash scripts to detect the presence of oil on the surface of ocean water. 

#### Project Hardware:
+ Transmit antenna
+ 1 recieve antenna 
+ 2 coaxial cables 
+ 1 weatherproof circut case with.
  - 1 router
  - 1 Raspberry Pi
  - 1 AC/DC variable power adapter.
  - 1 fully assembled circuit
+ 2 linear actuators
+ 2 jrk motor drivers
+ 1 wave tank
+ 1 wave tank support frame
+ 2 magnetitic digital levels
+ 12-V motor 


#### Basic Use:
 + To start running tests, select 'Acquire Data' on the GUI
 + Fill in required fields and submit.
 + Select 'Import Data' to import the values from the test to the database. 
 + Linear actuator that controls the angle of the antenna can be controled on from the Actuator Page.
   - the actuator calls a c++ executable that changest the angle of the actuator with respect to the ground.
   - a linear plot was created to match input to the actuator with desired angles from the user.
