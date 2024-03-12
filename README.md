Welcome to the Sudoku Solver project! This Java program is capable of solving any given Sudoku puzzle using efficient algorithms.

It aims to solve solve sudoku puzzles with a variety of different constraints while making it easy to explore the solution space including:

- Iterating over the solutions.
- Seeing all possible values a cell can take.
- Stepping through the solving process.




To demonstrate the usage of the Sudoku solver, let's solve the following puzzle:

5 3 . | . 7 . | . . .
6 . . | 1 9 5 | . . .
. 9 8 | . . . | . 6 .
------+-------+------
8 . . | . 6 . | . . 3
4 . . | 8 . 3 | . . 1
7 . . | . 2 . | . . 6
------+-------+------
. 6 . | . . . | 2 8 .
. . . | 4 1 9 | . . 5
. . . | . 8 . | . 7 9

Welcome to the Sudoku Solver project! This Java program is capable of solving any given Sudoku puzzle using efficient algorithms.

## Table of Contents
I. Introduction  
II. Usage
III. Example 
IV. License

## I. Introduction
This project provides a Java implementation of a Sudoku solver. The solver uses a backtracking algorithm to efficiently find the solution for any valid Sudoku puzzle.

## II. Usage
To use the Sudoku solver, you can follow these steps:

1. Clone the repository to your local machine: 
   git clone https://github.com/shaquib82/SudokuSolver.git
   
2. Navigate to the project directory: 
   cd SudokuSolver

3. Compile the Java files: 
   javac SudokuSolver.java

4. Run the solver with a Sudoku puzzle input file: 
   java SudokuSolver <input_file>
   Replace `<input_file>` with the path to your Sudoku puzzle input file.

## III. Example
To demonstrate the usage of the Sudoku solver, let's solve the following puzzle:

5 3 . | . 7 . | . . .
6 . . | 1 9 5 | . . .
. 9 8 | . . . | . 6 .
------+-------+------
8 . . | . 6 . | . . 3
4 . . | 8 . 3 | . . 1
7 . . | . 2 . | . . 6
------+-------+------
. 6 . | . . . | 2 8 .
. . . | 4 1 9 | . . 5
. . . | . 8 . | . 7 9



[Example puzzle goes here]

Run the solver with the input file containing the above puzzle: 
java SudokuSolver input.txt

The solution will be printed to the console.

## IV. License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.







