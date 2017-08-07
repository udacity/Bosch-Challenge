# Bosch-Path-Planning-Challenge
Race down a highway with a path planner that best decides how to pass other traffic and manuever the car.

# Test Track Release
The first test track of a highway that continuously goes down the same direction but with some slight curviness. The target is to drive down 2.75 miles of the track as fast as possible without going over the speed limit, crashing into other cars, violating acceleration more than 10 m/s^2 and jerk more than 10 m/s^3, and not driving between the dashed lines for more than 3 seconds or going off the ride side of the road.

# This challenge is based off of the Self-Driving Car Term 3 Project 1: Path Planing.
https://github.com/udacity/CarND-Path-Planning-Project
The competive challenge element added to this project is a brand new highway to test on, along with a timer element that measures how quickly the target 2.75 miles can be completed without incident. If the car takes longer than 360 seconds to complete 2.75 miles then it will be an incomplete. It will also be an incomplete for any violation listed above.

# Project Rubric 


### Compilation
The code compiles correctly. Code must compile without errors with cmake and make.

### Valid Trajectories
The car is able to drive at least 2.75 miles without incident.        

The top right screen of the simulator shows the current/best miles driven without incident. Incidents include exceeding acceleration/jerk/speed, collision, and driving outside of the lanes. Each incident case is also listed below in more detail.

----------------------------------------------------------------------------------------------------------------------------------------

The car drives according to the speed limit.

The car doesn't drive faster than the speed limit. Also the car isn't driving much slower than speed limit unless obstructed by traffic.

----------------------------------------------------------------------------------------------------------------------------------------

Max Acceleration and Jerk are not Exceeded.

The car does not exceed a total acceleration of 10 m/s^2 and a jerk of 10 m/s^3.

----------------------------------------------------------------------------------------------------------------------------------------

Car does not have collisions.

The car must not come into contact with any of the other cars on the road.

----------------------------------------------------------------------------------------------------------------------------------------

The car stays in its lane, except for the time between changing lanes.

The car doesn't spend more than a 3 second length out side the lane lanes during changing lanes, and every other time the car stays inside one of the 3 lanes on the right hand side of the road.






