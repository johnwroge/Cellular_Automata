# Cellular Automata - Conway's Game of Life


This project is an implementation of **Conway's Game of Life**, a cellular automaton that simulates the life cycle of cells on a grid based on simple rules. Each cell can be either "alive" or "dead" and evolves based on its neighboring cells:

- A live cell with fewer than two neighbors dies from loneliness.
- A live cell with two or three neighbors survives.
- A live cell with more than three neighbors dies from overpopulation.
- A dead cell with exactly three neighbors becomes alive.

The game was built using **Pygame** and **NumPy**.

## Installation and Usage

1. Install dependencies:  
```
   pip install pygame numpy
```

2. Run the Game:

```
python GameOfLife.py

```
