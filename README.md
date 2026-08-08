Rotting Oranges

BFS (Breadth-First Search)
Multi-Source BFS 
Queue
Level-by-Level Traversal
Each BFS level = 1 minute
4-Directional Movement
Fresh Orange Counter
Unreachable Oranges → -1
Time: O(m × n)
Space: O(m × n)

Eg:

Input:

3 3
2 1 1
1 1 0
0 1 1

Minute 0

2 1 1
1 1 0
0 1 1

Minute 1

2 2 1
2 1 0
0 1 1

Minute 2

2 2 2
2 2 0
0 1 1

Minute 3

2 2 2
2 2 0
0 2 1

Minute 4

2 2 2
2 2 0
0 2 2

All fresh oranges are rotten.

Answer = 4 minutes
