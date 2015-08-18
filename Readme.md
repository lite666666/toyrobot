
#### Welcome to the Toy Robot Simulator! ####

The application is a simulation of a toy robot moving on a square tabletop, of dimensions 5 units x 5 units.

The application that can read in commands of the following form:

- PLACE X,Y,F
- MOVE
- LEFT
- RIGHT
- REPORT

PLACE will put the toy robot on the table in position X,Y and facing *NORTH, SOUTH, EAST or WEST*.
MOVE will move the toy robot one unit forward in the direction it is currently facing.
LEFT and RIGHT will rotate the robot 90 degrees in the specified direction without changing the position of the robot.

The main file is toy.js   
on the node commands prompt window:
```sh
node toy.js
```

then either type in one the above commands per line or copy and paste a set of commands (each command per line) 
if the last command is REPORT, the current state of the toy robot will be shown as Output.


Example Input and Output:


    PLACE 0,0,NORTH
    MOVE
    REPORT
    Output: 0,1,NORTH
    
    PLACE 0,0,NORTH
    LEFT
    REPORT
    Output: 0,0,WEST
   
    PLACE 1,2,EAST
    MOVE
    MOVE
    LEFT
    MOVE
    REPORT
    Output: 3,3,NORTH
    
