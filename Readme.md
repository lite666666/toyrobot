
#### Welcome to the Toy Robot Simulator! ####

The application is a simulation of a toy robot moving on a square tabletop, of dimensions 5 units x 5 units.

The application that can read in commands of the following form:

- PLACE X,Y,F
- MOVE
- LEFT
- RIGHT
- REPORT

The main file is toy.js   
on the node commands prompt window:
```sh
node toy.js
```

then either type in one the above commands per line or copy and paste a set of commands (each command per line) 
if the last command is REPORT, the current state of the toy robot will shown.


Example Input and Output:
1.
    ```sh
    PLACE 0,0,NORTH
    MOVE
    REPORT
    Output: 0,1,NORTH
    ```
2.
    ```sh
    PLACE 0,0,NORTH
    LEFT
    REPORT
    Output: 0,0,WEST
    ```
3.
    ```sh
    PLACE 1,2,EAST
    MOVE
    MOVE
    LEFT
    MOVE
    REPORT
    Output: 3,3,NORTH
    ```
