# sudoku-solver
A Python program to solve Sudoku puzzles

Team: 2-4 people

Challenge: Intermediate/Hard

Sudoku puzzles are 9x9 grids divided into 9 3x3 subgrids with simple rules for solution: each 
row, each column, and each subgrid must contain the numbers 1-9 without repetition.  Properly 
constructed Sudoku puzzles have unique solutions and can be determined algorithmically from 
the initial "clue" numbers provided by the constructor.

This program should accept a Sudoku puzzle (that is, the value and position of clue numbers) as 
input and produce its solution as output.

In broad terms, the program should consist of 
* A gridlike GUI for the user to specify the initial puzzle with clue numbers
* An implementation of one or more strategies for determining what number belongs in each empty cell.  (Depending on how mathematically thorough you wish to be, this step can take the challenge from 'Intermediate' to 'Hard'!)
* Logic for applying these strategies in sequence to solve the puzzle with reasonable efficiency
* A 9x9 grid output to display the solution

As an added challenge, you should make sure the program can handle "trick" input, such as puzzles 
that have no solution or which have multiple solutions.
