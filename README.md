# Game-of-Life
## Introduction
In game of Life there are no players and there’s no way to win or lose the game. Life takes place on a two-dimensional grid of square cells. Each square cell can be either alive (1) or dead (0) depending on the state of their neighbors.

If the cell is dead:

i. Birth: If exactly three of its neighbors are alive, the cell will become alive at the next step.

If the cell is already alive:

ii. Survival: If the cell has two or three live neighbors, the cell remains alive. Otherwise, it will die.
iii. Death by loneliness: If the cell has only zero or one live neighbors, the cell will become dead.
iv. Death by overcrowding: If the cell is alive and has more than three live neighbors, the cell dies.
