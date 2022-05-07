# cub3D
## The goal: 
Creation a “realistic” 3D graphical representation of the inside of a maze from a first-person perspective, using the Ray-Casting.
## Rules:
* Program must use the miniLibX.
* The management of window must remain smooth: changing to another window, minimizing, etc.
* Display different wall textures that vary depending on which side the wall is facing (North, South, East, West).
* Program must be able to set the floor and ceiling colors to two different ones.
* The program displays the image in a window and respects the following rules:
    * The left and right arrow keys of the keyboard must allow you to look left and right in the maze.
    * The W, A, S, and D keys must allow you to move the point of view through the maze.
    * Pressing ESC must close the window and quit the program cleanly.
    * Clicking on the red cross on the window’s frame must close the window and quit the program cleanly.
* Program must take as a first argument a scene description file with the .cub extension.
* The map must be composed of only 6 possible characters: 
    * 0 for an empty space
    * 1 for a wall
    * N,S,E or W for the player’s start position and spawning orientation.
    * The map must be closed/surrounded by walls, if not the program must return an error.
* This is a simple valid map:
```
111111
100101
101001
1100N1
111111
```
## Launch:
```
%>make
%>./cub3D maps/map.cub
```

![screen](https://github.com/Marina-28/cub3d/blob/main/textures/screen.png)
