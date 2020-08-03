# Turtlebot_lawnmover
This program moves the turtlebot in lawnmover pattern using the turtlesim node on ROS. The distance of motion is scaled due to turtlesim node contraints,
we can create a new turtle at the bottom left of the turtlesim node by using rosservice call /spawn 1.0 1.0 0 t2  or at any spot required by changing the coordinates. 
The command rosservice call/ kill (name_of_turtle) to make the turtle disappear.
![](/lawnmover1.png)
![](/lawnmover2.png)
