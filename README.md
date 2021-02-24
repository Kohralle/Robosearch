# Robosearch
The system modeled here is a platform called ROBOSEARCH that allows non-technical
operators to use swarms of rovers for searching items within indoor environments.
Robot rovers are special kinds of robots that are specifically designed for autonomously
moving within an environment, sensing information, and actuating accordingly. Rovers
are very good candidates for starting to experiment with autonomous robots, i.e., robots
that can move, act, and decide actions without the human intervention.  In
ROBOSEARCH each rover has bumpers for sensing the presence of obstacles or other
rovers by touching them, sonars for sensing the surroundings within a certain range,
cameras mounted on the upper side of the rover itself, wheels for moving, and a
networking device for communicating with either other rovers or a central station. In
ROBOSEARCH, the mission of the robots is to move around the environment (by
following any strategy) and search for boxes of a given color. The color of the boxes
must be passed as parameter to the system at the beginning of the mission. Once a
mission is started, each rover of the swarm will start to move within the area in order to
search for the target boxes. Possible actions that a single rover can perform may be: go
towards a specific direction, read from a sensor, send feedback to a central station,
send/receive a notification to/from other rovers, etc. To avoid obstacles, a rover
uses heuristics, and it may even exploit the information coming from other rovers
(e.g., if they have overcome or not encountered the obstacle), if needed.
The mission finishes when the area has been fully covered.

<img width="474" alt="robophoto" src="https://user-images.githubusercontent.com/35265374/109069948-30ee0300-76f2-11eb-8533-df79b2dbab26.png">

# Modeling
This project was initially designed using UML graphs to create the ROBOSEARCH system,
together with a detailed descriptions about the design decisions
made when constructing those models. The project includes one use case diagram,
one class diagram, one state diagram and two sequence diagrams. All documentation can
be found in the pdf files.
