
# Pyramid Descent Puzzle Solver

## Description

The Pyramid Descent Puzzle involves a pyramid of integers where the goal is to find a path from the top of the pyramid to the bottom. The path must traverse adjacent numbers in each row such that the product of the numbers in the path equals a given target value.

For each step in the path, you can either move to the left or to the right in the next row. The solver must find the correct sequence of moves (left 'L' or right 'R') that results in the target product.

### Example:

For the pyramid below and a target value of 720:

  2
4   3


The correct path is `LLR`, leading to the product `2 * 4 * 3 * 2 * 15 = 720`.

## Features

- The program accepts any pyramid of integers and a target value.
- It uses a depth-first search (DFS) approach to explore possible paths.
- Outputs the correct path or reports if no valid path is found.

## How to Run

1. Ensure you have Python installed on your machine.
2. Clone this repository to your local machine.
3. Run the program using the following command:

```bash
python pyramid_descent.py

