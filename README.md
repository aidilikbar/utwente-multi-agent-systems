# utwente-multi-agent-systems
Multi Agent System's code repository

## WHAT IS IT?

In this model the turtles are cars traveling through an intersection.  The user has the ability to control the frequency of cars coming from each direction, the speed of the cars, and the timing of the light at the traffic intersection.  Once the frequency and speed of cars is selected, the user should run the simulation and adjust the timing of the traffic light so as to minimize the amount of waiting time of cars traveling through the intersection.

## HOW IT WORKS

The rules for each car are:

- I can only go in the direction I started in, or stop.

- I stop for cars in front of me and red lights, and I stop for a yellow light if I'm not already on it.

## CONTROL SETTINGS

CLOCK shows how many ticks have elapsed.

Use the FREQ-EAST slider to select how often new eastbound cars travel on the road. Default: 100.

Use the FREQ-NORTH slider to select how often new northbound cars travel on the road. Default: 100.

Use the SPEED-LIMIT slider to select how fast the cars will travel. Default: 5.

Use the MAX-ACCEL slider to determine how fast the cars can accelerate. Default: 2.

Use the MAX-BRAKE slider to determine how fast the cars can decelerate. Default: 4.

Use the GREEN-LENGTH slider to set how long the light will remain green. Default: 12.

Use the YELLOW-LENGTH slider to set how long the light will remain yellow. Default: 4.

Press GO ONCE to make the cars move once.

Press GO to make the cars move continuously.

To stop the cars, press the GO button again.

## CONDITIONS

NORMAL
- FREQ-EAST 100
- FREQ-NORTH 100
- GREEN-LENGTH 12

ODD-EVEN POLICY
- FREQ-EAST 50
- FREQ-NORTH 50
- GREEN-LENGTH 12

SMART TRAFFIC MANAGEMENT
- FREQ-EAST 50
- FREQ-NORTH 50
- GREEN-LENGTH 24

## MEASUREMENT

WAITING OVERALL shows how many cars are waiting during the given clock tick.

WAITING EASTBOUND shows how many eastbound cars are waiting during the given clock tick.

WAITING NORTHBOUND shows how many northbound cars are waiting during the given clock tick.

COUNT CARS OVERALL shows how many cars in the simulation.

COUNT CARS EASTBOUND shows how many eastbound cars in the simulation.

COUNT CARS NORTHBOUND shows how many northbound cars in the simulation.

AVERAGE SPEED OVERALL shows the average speed of cars in the simulation. It calculates the speed (ticks) of cars divided by the number of cars.

AVERAGE SPEED EASTBOUND shows the average speed of eastbound cars in the simulation. It calculates the speed (ticks) of eastbound cars divided by the number of eastbound cars.

AVERAGE SPEED NORTHBOUND shows the average speed of northbound cars in the simulation. It calculates the speed (ticks) of northbound cars divided by the number of northbound cars.

## THINGS TO TRY

Try all three conditions: NORMAL, ODD-EVEN POLICY, and SMART TRAFFIC MANAGEMENT


## COPYRIGHT AND LICENSE

2024 Aidil Ikbar a.aidilikbar@student.utwente.nl.
This model is part of an assignment project of Multi Agent Sistems course conducted in University of Twente.

This works is modified from original version of 1998 Uri Wilensky uri@northwestern.edu.
* Wilensky, U. (1998). NetLogo Traffic Intersection model. http://ccl.northwestern.edu/netlogo/models/TrafficIntersection. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.
* Wilensky, U. (1999). NetLogo. http://ccl.northwestern.edu/netlogo/. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.
