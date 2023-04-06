# A* Pathfinding Visualisation

This is my first attempt at A* pathfinding. You can modify all major features of my algorithm through the graphics interface. Here I will go through the major features of my program.

## Basic Controls
You must create a map to start the pathfinding. The start node is blue, end node is red and the walls are black. 

To create nodes:
  - Start: hold 's' + left click
  - End: hold 'e' + left click
  - Wall: left click
  
To delete nodes:
  - same as creation, except right click!

### Diagonal
My algorithm supports both diagonal and non diagonal pathfinding.

Simply check the "diagonal" box at the bottom left of the screen.

### Variable Speed
You may change the speed of the visualisation during runtime. 
  - By default, speed is 50%. 

Notice: speed only works when showSteps is true. 

if showSteps is false, well, that leads into the next section.

### Show Steps or Timed Efficiency
You may choose to view a step-by-step process of the algorithm by selecting "showSteps" box at the bottom left. 
  - If showSteps is false, the algorithm will skip visuals until the end, and process as fast as possible. 
  
This is useful for when you want to analyze the efficiency of my algorithm in different coniditons.

### Zoom
You can (kind of) zoom in and out. I wouldn't really advise it. It does not zoom into your mouse, only towards the top left corner, and making the map too big will crash the program. This needs some work. However, If you zoom in far enough you can view each nodes information. The top left is the "F cost", bottom left is "G cost" and bottom right is "H cost". I will work on properly implementing a zoom feature soon.
