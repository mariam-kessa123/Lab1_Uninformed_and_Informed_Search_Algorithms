
Lab 1 Part A: OOP Search Algorithms for Drone Pathfinding


Formulate a grid navigation task as a formal search problem.
Explain the roles of state, action, result, path cost, frontier, and reached/explored set.
Implement a reusable Problem interface and a Node class.
Implement and compare:
Breadth-First Search (BFS),
Depth-First Search (DFS),
Depth-Limited Search (DLS),
Iterative Deepening Search (IDS).
Evaluate algorithms using:
solution depth,
path cost,
number of nodes expanded,
maximum frontier/stack size,
completeness and optimality.
Explain when BFS, DFS, DLS, and IDS are complete or optimal on an unweighted grid.





Lab 1 Part B: OOP Informed Search Algorithms for Drone Pathfinding


Explain the difference between uninformed and informed search, in code and in words.
Define and implement heuristic functions h(n) (Manhattan distance, Euclidean distance).
Explain the roles of g(n), h(n), and f(n), and how a priority queue orders the frontier.
Implement a reusable BestFirstSearch framework and derive from it:
Greedy Best-First Search (f(n) = h(n)),
A* Search (f(n) = g(n) + h(n)),
Weighted A* (f(n) = g(n) + W·h(n)),
Uniform-Cost Search (f(n) = g(n)).
Extend the grid problem with non-uniform terrain costs and explain how this changes which path is optimal.
Define admissibility and consistency, verify them for grid heuristics, and demonstrate experimentally what happens when a heuristic overestimates.
Evaluate algorithms using solution cost, nodes expanded, maximum frontier size, completeness, and optimality.
Choose an appropriate informed search strategy for a given speed / optimality / memory trade-off.
