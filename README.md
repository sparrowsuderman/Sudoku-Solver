# Sudoku-Solver
The development of code to complete a sudoku.
The first step I took towards my final goal was to produce a function to check a potential solution is valid. (ie: Each row, column and 3 by 3 group has all the numbers 1 to 9 appearing once.

Next, I worked on the solver itself. My initial version utilised a series of functions to complete the sudoku. The key idea of the code was to find the empty cells in the sudoku (zeros in the array) and determine the possible values which could go there. If a cell was found to have only one possible value, then that value was assigned and the next empty cell is found. This is looped thorugh until the entire board is filled.

The final alteration to the solver was to add classes. Instead of a series of function, classes were created with the correspoding functions were included. 

