# Sudoku Game in Python

A classic Sudoku game implemented in Python, featuring a graphical user interface built with Pygame.  
This project allows users to play Sudoku puzzles of varying difficulty levels, providing an engaging and interactive experience.

## 🧩 Features

- **Sudoku Puzzle Generation**: Generate puzzles of varying difficulty levels (easy, medium, hard).  
- **Backtracking Solver**: Automatically solve puzzles using the backtracking algorithm.  
- **Graphical Interface**: Interactive grid with mouse and keyboard support for input.  
- **Timer**: Track time taken to solve the puzzle.  
- **Highlighting**: Highlight selected cells and invalid entries.  

## 📂 Project Structure

The project is organized into the following Python files:

- **`cell.py`**: Defines the structure and behavior of individual cells in the Sudoku grid.  
- **`clock.py`**: Manages the timer functionality for the game.  
- **`main.py`**: Entry point of the game, initializing the game and handling the main loop.  
- **`setting.py`**: Contains configuration settings, including difficulty levels and board dimensions.  
- **`sudoku.py`**: Implements the Sudoku puzzle generation and solving logic.  
- **`table.py`**: Handles the rendering of the Sudoku grid and user interactions.  
- **`__pycache__`**: Python bytecode cache directory (auto-generated).  
- **`.idea`**: IDE project configuration files (for PyCharm or other JetBrains IDEs).  


## 🛠️ Installation & Run

```bash
# Step 1: Clone the repository
git clone https://github.com/bhavneet08/Sudoko.git
cd Sudoko

# Step 2: Install dependencies
pip install pygame requests

# Step 3: Run the game
python main.py





