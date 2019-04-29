# Sudoku-Solver
A python script containing a backtracking solver and a CSP solver.

I created a Sudoku solver agent class which has 3 types of solving methods.
1- Backtracking
2- Constraint satisfaction problem (CSP)
3- Constraint satisfaction problem with forward checking and heuristic function (CSPFH)

I used different heuristics that you can view the results in SudokuReports.txt. The basic idea was the MRV heuristics which stands for minimum remaining values.
The goal is trying to minimize the number of nodes expanded in the tree. 