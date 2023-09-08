<img src="https://github.com/mahyarmohammadimatin/8-Puzzle-Problem-different-search-Algorithms/blob/main/46.png">

## Repository Contents:

### Problem Components:
1. States: Configuration of tiles in a 3x3 numpy array.
2. Operators (Actions): Moving the blank tile up, down, left, or right.
3. Goal Test: Verify if the puzzle is solved.
4. Path Cost: Count of actions taken to reach the goal state.
5. Transition Model: Describes state changes after an action.

### Heuristic Function:
1. Best heuristic: Manhattan distance with zero distance tiles removed.
2. Admissibility and consistency explained.

### Algorithm Comparison:
1. A* Algorithm: Optimal solution finder using heuristic and path cost.
2. Uniform Cost Search (UCS): Slow and memory-intensive.
3. Iterative Deepening Search (IDS): Slower with lower memory usage.
4. Breadth-First Search (BFS): Slightly slower with higher memory usage.

### A* Performance:
1. Outperforms other algorithms in time and memory efficiency.
2. Uses heuristic and path cost for node priority.
3. Prunes search tree effectively and finds optimal solution.

### Other Algorithms:
1. UCS lacks heuristic guidance, leading to slower search.
2. IDS and BFS also lack heuristic guidance, resulting in even slower search and higher memory usage.
