This Python code implements two pathfinding algorithms, A* and Uniform Cost Search, in the context of a grid-based environment. 
Agents navigating the grid have an associated battery level that decreases as they move through the grid. The goal is to find a path from the starting point to the destination while considering battery limitations.
PriorityQueue:
A custom priority queue implementation for efficient frontier management in pathfinding algorithms.
Node:
Represents a state in the search space, containing information such as the current state, parent node, action taken, path cost, and battery level.
Environment:
Defines the grid-based environment with obstacles, the initial position, and the goal position. It provides functions to retrieve possible actions, calculate the result of an action, and check if a state is the goal.
Agent:
Implements A* and Uniform Cost Search algorithms. The A* algorithm considers both the path cost and a heuristic function, while the Uniform Cost Search only considers the path cost. The agents have a battery level that decreases with each movement.
Visualization:
Provides a visualization function to display the grid, the path taken, starting and goal positions, and indicates positions with 0% battery level.
The visualize_grid_and_path_with_battery function displays the grid, path, starting and goal positions, and marks positions with 0% battery level. 
The code can be adapted for use in scenarios where battery-aware pathfinding is essential, such as in robotics or autonomous navigation systems.
