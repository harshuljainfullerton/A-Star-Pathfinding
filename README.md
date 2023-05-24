# A-Star-Pathfinding
### Made A-Star Pathfinding algorithm in Python with pygame

Project Description:

A* Path Finding Algorithm is a Python program that demonstrates the A* search algorithm to find the shortest path between two points on a grid. The program utilizes the Pygame library to create a graphical user interface for visualizing the algorithm's execution.

The program starts by defining the dimensions of the grid and initializing the Pygame window. The grid consists of individual spots, each representing a cell in the grid. The spots can have different colors to indicate their status, such as start, end, barrier, open, closed, and path.

The A* algorithm is implemented using a priority queue to efficiently explore the grid. It iteratively evaluates spots based on their cost and heuristic values to determine the most promising path. The algorithm continues until it reaches the end spot or exhausts all possible paths.

Users can interact with the program by clicking on the grid to set the start spot, end spot, and barriers. Left-clicking sets the start and end spots, while right-clicking clears a spot or removes barriers. Pressing the space bar triggers the execution of the A* algorithm, which calculates and visualizes the shortest path between the start and end spots.

The program provides a visually appealing representation of the algorithm's progress, with spots changing colors to indicate their status during the search. Once the algorithm completes, the shortest path is highlighted in a different color.

Overall, the A* Path Finding Algorithm project demonstrates the implementation of the A* search algorithm and provides an interactive visualization of its execution. It showcases skills in Python programming, algorithmic problem-solving, and graphical user interface development with Pygame.
