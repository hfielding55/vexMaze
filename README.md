# vexMaze
TASK ONE + TWO: SOLVE MAZE AND FIND MOST EFFICIENT PATH
The robot solves the maze following the right hand wall. While doing this, it records the coordinates it passes over. If it goes back on itself it will delete down to that point in the array, with the exception of junctions since they could still be part of the correct track. Incorrect junctions will be deleted anyways when the robot goes back on itself further.

TASK FOUR: RETURN TO HOME
Once the maze is completed, the pathing array leftover is a list of coordinates to solve the maze in the most efficient path and it will follow it back to the start, drawing a line.

TASK THREE: MAP THE MAZE
The robot, now back at the start, will check how many routes there are from the start position. By following the right wall of each of these paths it will ensure it covers the entirety of the maze. Since we can assume the maze has outer walls, the robot will only check the upper and right wall of each coordinate, recording it in a 2d array.
After completing its route of the maze it then constructs an ASCII maze using the information it has gathered. It then prints that in the text area.
