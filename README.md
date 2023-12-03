# Maze Generation &amp; Solver
Maze Generation &amp; Solver - Automatically generate a maze with user inputting size and solve the maze using Breadth-First Search (BFS) and Depth-First Search (DFS).

## Example 
```
Input the size for the maze: 10
-------------------------------------------------------------------

+   +---+---+---+---+---+---+---+---+---+
|   |       |                           |
+   +   +   +   +---+---+---+   +---+   +
|       |   |   |   |       |       |   |
+---+---+   +   +   +   +   +---+---+   +
|       |   |       |   |   |           |
+---+   +   +---+---+   +   +   +---+   +
|       |               |       |       |
+   +   +---+---+---+---+---+---+   +---+
|   |   |               |       |   |   |
+   +---+   +---+   +---+   +   +   +   +
|           |   |           |   |       |
+   +---+---+   +---+---+---+   +---+   +
|       |               |       |       |
+---+   +   +---+---+   +   +---+   +---+
|   |       |           |   |       |   |
+   +---+---+   +---+---+   +   +---+   +
|       |       |       |   |       |   |
+   +   +   +---+---+   +   +---+   +   +
|   |                   |               |
+---+---+---+---+---+---+---+---+---+   +
String Representation of Generated 10x10 Maze

+   +---+---+---+---+---+---+---+---+---+
| 0 | 3   4 | 7   6   5   4   3   2   1 |
+   +   +   +   +---+---+---+   +---+   +
| 1   2 | 5 | 8 | 1 | 2   3 | 2   3 | 0 |
+---+---+   +   +   +   +   +---+---+   +
| 0   9 | 6 | 9   0 | 1 | 4 | 7   8   9 |
+---+   +   +---+---+   +   +   +---+   +
| 6   7 | 7   8   9   0 | 5   6 | 5   4 |
+   +   +---+---+---+---+---+---+   +---+
| 5 | 8 | 1   0   9   6 | 5   4 | 6 | 9 |
+   +---+   +---+   +---+   +   +   +   +
| 4   3   2 | 5 | 8   7   6 | 3 | 7   8 |
+   +---+---+   +---+---+---+   +---+   +
| 1   2 | 5   6   7   8 | 1   2 | 1   0 |
+---+   +   +---+---+   +   +---+   +---+
| 9 | 3   4 | 1   0   9 | 0 | 3   2 |   |
+   +---+---+   +---+---+   +   +---+   +
| 7   6 | 3   2 | 4   3 | 9 | 4   5 |   |
+   +   +   +---+---+   +   +---+   +   +
| 8 | 5   4   0   1   2 | 8   7   6   7 |
+---+---+---+---+---+---+---+---+---+   +
String representation of DFS Maze

+   +---+---+---+---+---+---+---+---+---+
| 0 | 3   4 | 7   5   2   9   6   4   2 |
+   +   +   +   +---+---+---+   +---+   +
| 1   2 | 5 | 9 | 5 | 2   3 | 8   1 | 0 |
+---+---+   +   +   +   +   +---+---+   +
|       | 6 | 1   3 | 1 | 4 | 7   8   9 |
+---+   +   +---+---+   +   +   +---+   +
|       | 7   8   9   0 | 5   6 | 3   1 |
+   +   +---+---+---+---+---+---+   +---+
|   |   |               |       | 5 | 3 |
+   +---+   +---+   +---+   +   +   +   +
|           |   |           |   | 7   0 |
+   +---+---+   +---+---+---+   +---+   +
|       |               |       | 6   4 |
+---+   +   +---+---+   +   +---+   +---+
|   |       |           |   | 0   8 |   |
+   +---+---+   +---+---+   +   +---+   +
|       |       |       |   | 2   4 |   |
+   +   +   +---+---+   +   +---+   +   +
|   |                   |         6   7 |
+---+---+---+---+---+---+---+---+---+   +
String representation of BFS Maze

+   +---+---+---+---+---+---+---+---+---+
| # | #   # |                           |
+   +   +   +   +---+---+---+   +---+   +
| #   # | # |   |   | #   # |       |   |
+---+---+   +   +   +   +   +---+---+   +
|       | # |       | # | # | #   #   # |
+---+   +   +---+---+   +   +   +---+   +
|       | #   #   #   # | #   # | #   # |
+   +   +---+---+---+---+---+---+   +---+
|   |   |               |       | # |   |
+   +---+   +---+   +---+   +   +   +   +
|           |   |           |   | #   # |
+   +---+---+   +---+---+---+   +---+   +
|       |               |       | #   # |
+---+   +   +---+---+   +   +---+   +---+
|   |       |           |   | #   # |   |
+   +---+---+   +---+---+   +   +---+   +
|       |       |       |   | #   # |   |
+   +   +   +---+---+   +   +---+   +   +
|   |                   |         #   # |
+---+---+---+---+---+---+---+---+---+   +
Hash Single Path
```

## License
All parts of Maze Generation &amp; Solver are free to use and abuse under the open-source MIT license.

## Acknowledgement
Maze Generation &amp; Solver was created by [Nhat Nguyen](https://github.com/nguyen-nhat) and [Jasmine Mai](https://github.com/jasminemai97).