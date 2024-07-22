# Maze Solver

This project is a simple maze solver using Python's `tkinter` library for graphical display. The maze is generated and solved using depth-first search. The project includes several components:

- `main.py`: The entry point of the application, which creates and solves the maze.
- `graphics.py`: Contains the graphical window setup and classes for drawing lines and points.
- `cell.py`: Defines the `Cell` class that represents each cell in the maze with walls and drawing methods.
- `maze.py`: Contains the `Maze` class that handles maze generation and solving.
- `test.py`: Unit tests for the `Maze` class to ensure functionality.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Abderrahmanehocine/Maze-solver
    cd Maze-solver
    ```

2. Install any required dependencies (if applicable). For this project, `tkinter` is included with Python by default.

### Running the Application

To run the maze solver application, execute the `main.py` file:

```bash
python main.py

### Application output

The application will open a window displaying the generated maze and attempt to solve it. The maze and solution will be visualized in the window.

### Running Tests

To run the unit tests for the Maze class, execute the test.py file:

```bash
python test.py