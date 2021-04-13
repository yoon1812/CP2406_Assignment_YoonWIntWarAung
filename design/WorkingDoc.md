###Problem specification
The problem area lies on creating traffic simulator where roads, traffic lights and vehicles are put into place. In the program, vehicles will move forward, turn right or left and traffic lights will be changing its colour randomly. 

###Problem decomposition
The problem will be functionally broken down into classes and this is well described in UML diagram.

###User story (1)
As a user, I want to change how the roads are crossing each other so that I can model different city roads scenarios.
Priority:  Medium
Estimate:  3 hours
Test: change the position of the roads before simulator runs

###User story (2)
As a user, I want to be able to control where to put in place the traffic lights so that I can well understand how traffic lights location may affect the traffic. 
Priority: Medium
Estimate: 4 hours
Test: move the traffic lights to different locations 

###User story (3) 
As a user, I want to save the map where I allocates roads and traffic lights so that I can easily modify or reuse it to see how changes can affect or improve the traffic. 
Priority: Low
Estimate: 2 hours
Test: save the map of the city after allocating roads and traffic lights

 
###User story (4)
As a user, I want to see how many vehicles and traffic lights are on the map and the average speed of the vehicles so that I can understand how they can collectively affect road traffic conditions and collisions. 
Priority: High
Estimate: 5 hours
Test: display the statistics about the number of vehicles, their average speed and traffic lights.

###User
-	Create their map and save the map to be able to modify and reuse it.
-	Allocate roads and traffic lights to see how they affects the traffic.
-	Can edit the map to compare before and after changes traffic situation.
-	Can see the statistics of vehicles and traffic lights.
-	To be able to run and stop the simulator when they want. 


###System
-	Two modes: City and Simulation, will be included.
-	To provide the user with roads and traffic lights.
-	Randomly change the colour of the traffic lights. 
-	Statistics about the number of vehicles and traffic lights, the average speed of the vehicles will be displayed. 
-	All vehicles will be moving along the lanes and decide if it is good to move depending on the distance between the vehicles.
-	Vehicles will disappear when they reach at the edges of the map.
-	At intersection, vehicle randomly selects to go straight or turn.
