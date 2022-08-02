# About
This is a visualizer for the A* pathfinding algorithm. Its a small program ment to show how the algorithm works.

# requirement
Install ***pygame*** if you don't already have it! The easiest way is through the command prompt you can type either of the two below.
<br>
pip install pygame **or** pip3 install pygame
<br>
copy and paste if you want and if that doesn't work make sure your pip is working properly.

## Controls
<hr>

***Left Click*** changes the nodes from white to start, end, or barrier. If start and end doesn't exist yet it will make it first
<br>
***Right Click*** resets the nodes back to there default state
<br>
***Space*** starts the pathfinding algorithm
<br>
***R*** resets all the squares
# Notes
- Once the algorithm starts you can't hit a button until it finishs. 

- Diagonals still find the shortest distance between the two spots it just doesn't look the prettiest since the heuristic function was initally ment for the non diagonal veriation but works pretty much perfectly in the final product.