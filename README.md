# MazeSolver
Project that can read a maze from a file and find the end. '3' is the starting number, '4' is the ending number, '1's are traversable paths and '0's are walls.
This project uses a Right, Down, Left, Up priority for solving the maze, meaning the application will check if it can move right first, and will move right if available, before proceding to check if it can move down. 
This is not a shortest path algorithm but due to the set priority, will solve the maze without back-tracking.
