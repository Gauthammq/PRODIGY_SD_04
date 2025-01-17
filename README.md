# PRODIGY_SD_04


# Sudoku Solver GUI

A simple Sudoku solver application built using Python's Tkinter library. This GUI application allows users to input Sudoku puzzles and solve them with the click of a button.

## Features

- **Grid Input:** A 9x9 grid for entering Sudoku puzzles.
- **Solve Button:** Solves the Sudoku puzzle when clicked.
- **Validation:** Ensures the input is a valid Sudoku puzzle before solving.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/sudoku-solver-gui.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd sudoku-solver-gui
   ```
3. **Install the required packages (if any):**
   This project requires Python's Tkinter library, which is typically included with standard Python installations.


1. **Run the application:**
   ```bash
   python sudoku_solver_gui.py
   ```
2. **Input the Sudoku puzzle:**
   - Click on the cells and enter the numbers for the puzzle.
   - Leave empty cells for unknown values.
3. **Solve the puzzle:**
   - Click the "Solve" button to solve the puzzle.
   - The solution will be displayed in the grid.

## Code Overview

- **`SudokuSolverGUI` Class:** This class handles the GUI creation, input retrieval, and Sudoku solving logic.
  - `create_grid()`: Creates the 9x9 input grid.
  - `get_grid()`: Retrieves the current grid state from the input fields.
  - `set_grid(grid)`: Sets the grid with the solved puzzle.
  - `is_safe(grid, row, col, num)`: Checks if a number can be placed in a cell without breaking Sudoku rules.
  - `solve_sudoku(grid)`: Recursively solves the Sudoku puzzle.
  - `solve()`: Wrapper method that gets the grid, solves the puzzle, and updates the UI.

## Author

 - [Gautham Krishna R](https://github.com/Gauthammq)
- **Contributions:** Developed the GUI and implemented the Sudoku solving logic.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Python Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
- [Sudoku Solving Algorithm](https://en.wikipedia.org/wiki/Sudoku_solving_algorithms)
```

