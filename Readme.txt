 
- Develop an API that moves a robot around on a grid (flat surface with defined size)
- Grid position (0, 0) should be the upper left corner
- You are given the initial starting point (x,y) of a robot and the direction (N,S,E,W) it is facing.
- The robot receives an array of commands.
- Implement commands that move the robot forward/backward (f,b).
- Implement commands that turn the robot left/right (l,r).
- "If a given sequence of commands encounters an obstacle or is out of bounds, the robot should stop and report the obstacle. For example, if it hits an obstacle or wall it should stop immediately without executing any more commands.
- Implement detection if the new position is inside the bounds before moving to the new position.
- Implement obstacle detection before each move to a new square.
