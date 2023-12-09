# AI Search Algorithms
This repository contains Python implementations of various search algorithms commonly used in artificial intelligence for solving pathfinding and optimization problems. The algorithms included in this repository are:

Best-First Search
Branch and Bound
A* (A-star) Algorithm
Breadth-First Search (BFS)
Overview
These search algorithms are fundamental in AI and can be applied to solve various problems, including pathfinding in graphs, optimization in search spaces, and more. Each algorithm has its specific characteristics, advantages, and use cases, contributing to different strategies for exploring search spaces efficiently.
Graph Restrictions
Graph Type: The implemented algorithms are designed for undirected, non-negative weighted graphs.
Constraints: These algorithms assume finite branching factors in the graphs they operate on.
Algorithms
Best-First Search
Best-First Search Algorithm Implementation
This repository contains a Python implementation of the Best-First Search algorithm used for traversing a graph from a start vertex to an end vertex while employing heuristics to guide the search strategy.

Overview
The Best-First Search algorithm is an informed search technique that explores a graph by prioritizing nodes based on heuristic information. It systematically explores nodes in the search space, aiming to efficiently reach the goal vertex while using heuristics to guide the traversal.

Features
Heuristic Guidance: Uses heuristics to guide the search strategy towards the goal vertex.
Graph Traversal: Explores the graph from the start vertex to the end vertex using a systematic prioritization of nodes.
Subroute Display: Prints the progress of explored subroutes during the traversal for analysis.
Algorithm Details
The provided implementation of the Best-First Search algorithm employs heuristics to guide the exploration of the graph from the start vertex towards the goal vertex. It prioritizes nodes based on heuristic values, systematically traversing the graph while avoiding revisiting already explored vertices.

Usage
To use the Best-First Search algorithm implementation:

Input: Provide the graph structure, heuristics, start vertex, and end vertex as parameters.
Algorithm Execution: Call the best_first_search() function with the specified inputs.
Result: The algorithm returns the optimal path or indicates if no path exists between the specified start and end vertices.
Branch and Bound
Branch and Bound Algorithm Implementation
This repository contains a Python implementation of the Branch and Bound algorithm used for finding an optimal solution in an optimization problem, particularly applied to a specific scenario of graph traversal between two vertices.

Overview
The Branch and Bound algorithm is a technique used in combinatorial optimization to systematically explore the search space by dividing it into smaller subspaces. It aims to efficiently find the best solution within a feasible region while avoiding exploring subspaces that cannot contain an optimal solution.

Features
Optimization: Seeks the best solution within a feasible region by systematically exploring the search space.
Graph Traversal: Explores the graph from the start vertex towards the end vertex using a systematic search strategy.
Subroute Display: Prints the progress of explored subroutes during the traversal for analysis.
Algorithm Details
The provided implementation of the Branch and Bound algorithm explores the graph from the start vertex towards the goal vertex, evaluating and prioritizing the most promising paths while avoiding the exploration of redundant or unpromising paths. It systematically refines the search space to find the optimal path efficiently.

Usage
To use the Branch and Bound algorithm implementation:

Input: Provide the graph structure, start vertex, and end vertex as parameters.
Algorithm Execution: Call the branch_and_bound() function with the specified inputs.

A* Algorithm Implementation
This repository contains a Python implementation of the A* (A-star) search algorithm used for finding the optimal path between two vertices in a weighted graph. The implementation includes functionalities to print the progress of subroutes explored during the traversal and handles specified edge cases.

Overview
The A* algorithm is a widely used informed search algorithm that efficiently finds the shortest path from the start to the goal in a graph by incorporating heuristics. This implementation aims to provide an optimal path and display the progression of subroutes during the traversal for visibility and analysis.

Features
Optimal Pathfinding: Searches for the most efficient path between the start and end vertices in a weighted graph using the A* algorithm.
Subroute Display: Prints the progress of subroutes explored during the traversal for better visibility and analysis of the algorithm's execution.
Edge Case Handling: Handles specified edge cases for a more robust search process, accounting for particular constraints in the graph.
Algorithm Details
The provided implementation of the A* algorithm explores the graph from the start vertex towards the goal vertex, utilizing heuristics to guide the search efficiently. During traversal, the algorithm prints the explored subroutes and progresses towards finding the optimal path based on specified constraints.

Usage
To use the A* algorithm implementation:

Input: Provide the graph structure, heuristics, start vertex, and end vertex as parameters.
Algorithm Execution: Call the A_star() function with the specified inputs.
Result: The algorithm returns the optimal path between the specified start and end vertices while displaying the current possible subroutes.
Breadth-First Search (BFS)
DBreadth-First Search (BFS) Algorithm Implementation
This repository contains a Python implementation of the Breadth-First Search algorithm used for traversing a graph from a start vertex to an end vertex while systematically exploring vertices in layers.

Overview
The Breadth-First Search algorithm is an algorithmic technique employed to systematically explore and traverse a graph. It begins at the start vertex and explores all neighboring vertices at the present depth level before moving on to the vertices at the next depth level.

Features
Graph Traversal: Explores the graph from the start vertex to the end vertex using a layer-by-layer approach.
Optimal Pathfinding: Seeks the shortest path between two vertices in an unweighted graph.
Path Display: Prints the progression of visited vertices during the traversal for analysis.
Algorithm Details
The provided implementation of the Breadth-First Search algorithm systematically explores the graph by traversing through vertices layer by layer. It maintains a queue to keep track of the vertices to be visited and explores neighboring vertices in breadth-first fashion.

Usage
To use the Breadth-First Search algorithm implementation:

Input: Provide the graph structure, start vertex, and end vertex as parameters.
Algorithm Execution: Call the breadth_first_search() function with the specified inputs.
Result: The algorithm returns the shortest path between the specified start and end vertices or indicates if no path exists.
