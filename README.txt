To use my program, unfortunately the command prompt is to be used. The start of the program is slow because of the iterrows method of the pandas library. Thus the calculation of each grid's crime rate is unfortunately slow. Due to my inexperience i my language and the lack of time i could not ammend it. But i have a function for where if you put the appropriat txt files containing the grid vaues, the program is much much faster.

HOW TO USE:
To use it, first we need to inpput the grid size and threashol in the command prompt. As stated earlier, the grid input is fairly long. Afterwards, 4 inputs are required. The first 2 are for the start coordinates and the last 2 are for the end coordinates. After theses inputs the program will complete execution and will find the shortesta nd most optimal path. But unfortunately my path tracing is not good. If we look closely at the traced paths, it is a nice quick path.

Heurstic:
the heuristic function used is a simple subtraction of the length and width difference of the 2 coordinates. I chose this because of the admissibilty property this heuristic grants.

A*
Uses area locations and mathematics to check new pints of interest. Explored points are listed in a closed set while points of interests are located in an open set. A while loop is used in the implementation of this algorithm.