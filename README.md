# Udacity-Bosch Path Planning Challenge
Your challenge is to design a path planner that creates smooth, safe paths along a 3-lane highway with traffic. Successful path planners will be able to keep inside their lanes, avoid hitting other cars, and pass slower moving traffic - all by using localization, sensor fusion, and map data. Path planners will be ranked by the time it takes them to complete a lap around a test track.

# Udacity Track Release
Go here to download the simulator and original project track: https://github.com/udacity/CarND-Path-Planning-Project

# Bosch Track Release
The Bosch track is a highway that continuously goes down the same direction but with some slight curviness. 

The competitive challenge element added to this project is a brand new highway to test on, along with a timer element that measures how quickly the target 2.75 miles can be completed without incident. 

The guidelines for a valid submission are listed in the rubric below.

# Final Evaluation Track
Your submission will be run on a private evaluation track that will be similar to the Bosch track with the exception that the car placement won't be random.

# Project Rubric 


### Compilation
The code compiles correctly. Code must compile without errors with cmake and make.

### Valid Trajectories
**The car is able to drive at least 2.75 miles without incident**        

The top right screen of the simulator shows the current/best miles driven without incident. Incidents include exceeding acceleration/jerk/speed, collision, and driving outside of the lanes. Each incident case is also listed below in more detail.

----------------------------------------------------------------------------------------------------------------------------------------

**The car drives according to the speed limit**

The car doesn't drive faster than the speed limit of 50 miles per hour.

----------------------------------------------------------------------------------------------------------------------------------------

**Max acceleration and jerk are not exceeded**

The car does not exceed a total acceleration of 10 m/s^2 and a jerk of 10 m/s^3.

----------------------------------------------------------------------------------------------------------------------------------------

**Car does not have collisions**

The car must not come into contact with any of the other cars or objects on the road.

----------------------------------------------------------------------------------------------------------------------------------------

**The car stays in its lane except when changing lanes**

During lane changes, the car doesn't spend more than 3 seconds outside the lane lines. During normal operation the car stays inside the lane lines with the flow of traffic.

----------------------------------------------------------------------------------------------------------------------------------------

**The car completes its trip within 360 seconds**

Any submissions that don't finish within 360 seconds will be considered invalid.

----------------------------------------------------------------------------------------------------------------------------------------

**Submission file must meet naming standards**

Your .zip file must include main.cpp and all the code required to successfully compile. In addition, you must use the following map name in your code: highway_map_bosch1.csv





 # Archival Note 
 This repository is deprecated; therefore, we are going to archive it. However, learners will be able to fork it to their personal Github account but cannot submit PRs to this repository. If you have any issues or suggestions to make, feel free to: 
- Utilize the https://knowledge.udacity.com/ forum to seek help on content-specific issues. 
- Submit a support ticket along with the link to your forked repository if (learners are) blocked for other reasons. Here are the links for the [retail consumers](https://udacity.zendesk.com/hc/en-us/requests/new) and [enterprise learners](https://udacityenterprise.zendesk.com/hc/en-us/requests/new?ticket_form_id=360000279131).