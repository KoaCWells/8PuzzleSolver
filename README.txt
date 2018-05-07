Authors: Koa Wells, Henri Thomas, Henry Thomas
CSCE A411 - Artificial Intelligence

----8 Puzzle Solver----
This program is designed to solve the 8-puzzle game using the breadth-first search, greedy best-first search w/ Manhattan Distance heuristic, A-Star w/ misplaced tiles heuristic, and A-Star w/ Manhattan Distance heuristic.

Within the main, change the forth parameter of BoardNodeList boardQueue to change the heuristic used:
1 - Manhattan Distance
2 - Tiles Out of Place

Line 604 and 605 are used to select the search algorithm.
-uncomment 604 to use A-Star
-uncomment 605 to use Breadth First Search