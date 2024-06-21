# PRODIGY_SD_04
### Sudoku Solver

This repository contains a Python script that implements a Sudoku solver using the backtracking algorithm. The solver reads an input grid representing an unsolved Sudoku puzzle and fills in the missing numbers, adhering to Sudoku rules. Once solved, the puzzle is printed in a human-readable format.

#### Features:
- **Validation**: Ensures numbers are placed according to Sudoku rules.
- **Backtracking Algorithm**: Efficiently explores possible solutions to solve the puzzle.
- **Readable Output**: Prints the solved Sudoku grid in a formatted manner.

### How It Works

1. **Validation Function**: 
   - `is_valid(board, row, col, num)`: Checks if placing a number in a specific position is valid according to Sudoku rules (row, column, and 3x3 sub-grid).

2. **Sudoku Solver Function**:
   - `solve_sudoku(board)`: Uses backtracking to solve the puzzle by placing numbers 1 to 9 in empty cells and recursively solving the rest of the board.

3. **Finding Empty Cells**:
   - `find_empty(board)`: Locates the next empty cell in the grid.

4. **Board Printing**:
   - `print_board(board)`: Outputs the Sudoku board in a neatly formatted 2D grid.

