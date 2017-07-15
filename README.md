# Maze_Game
This is a maze game implemeted using java.
File Data and Explanation 
1. CreateMaze.txt 
This file contains a set of numbers in Matrix format (Rows and Cols)
There are 5 columns.
The first column represents the room numbers.
The columns 2 through 5 of each row represents what surrounds the room to the
directions EAST, WEST, NORTH, SOUTH respectively.
If it’s a WALL, then it is indicated by a “0”.If it’s a Door that leads to another room, then it is indicated by the “room_number”
that the door leads you to.
The number of rows is equal to the number of rooms that we want the maze to
have.
Each row represents one room and defines its surroundings.
The example at the end will clarify this in pictorial format.
2. TraverseMaze.txt 
This file contains a set of lines with “numbers”.
The count of numbers in each line could be different.
The number of lines in this file is the number of traversals that we want the
students to do in that maze.
Each line is a different traversal and has no dependency to the other lines.
The first number in each line indicates the “Starting room” for that traversal.
The corresponding numbers indicates the direction the Student has to traverse in
the maze.
At the end of traversal of each line, the Student will be in a particular destination
room.
The student will write each row’s traversal result into another file called
Destinations.txt which has just one number in each line.
The number of lines in Destinations.txt will be the same as TraverseMaze.txt
because each line will lead to some location.
