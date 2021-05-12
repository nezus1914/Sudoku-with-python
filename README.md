# Sudoku-with-python
 how we are going to go about solving the problem and discuss the algorithm known as backtracking
 
 Sudoku originally called (Number Place) is a logic-based combinatorial number-placement puzzle. In classic sudoku, the objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid (also called "boxes", "blocks", or "regions") contains all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.
 
 Backtracking is simply reverting back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. We will use this principle of backtracking to implement the following algorithm.
 
 Algorithm

Starting with an incomplete board:

1.Find some empty space
2.Attempt to place the digits 1-9 in that space
3.Check if that digit is valid in the current spot based on the current board
4.If the digit is valid, recursively attempt to fill the board using steps 1-3.
5.If it is not valid, reset the square you just filled and go back to the previous step.
6.Once the board is full by the definition of this algorithm we have found a solution.

link description of tech with Tim:https://www.techwithtim.net/tutorials/python-programming/sudoku-solver-backtracking/
 
 
