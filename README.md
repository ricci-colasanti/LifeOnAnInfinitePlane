LifeOnAnInfinitePlane
=====================

This project is a Python implementation of Conway's Game of Life using an infinite plane to represent the game space. Instead of using a grid, this implementation uses a dictionary to represent the game space, allowing for an infinite and dynamic game space that can create new areas as needed.

Getting Started
---------------

To get started, clone this repository to your local machine:

```
git clone https://github.com/yourusername/LifeOnAnInfinitePlane.git
```

Once you have the code on your local machine, you can run the game by executing the `life_on_an_infinite_plane.py` file:

```
python life_on_an_infinite_plane.py
```

Game Rules
----------

The Game of Life is a cellular automaton that follows a set of rules:

1. Any live cell with fewer than two live neighbors dies, as if by underpopulation.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

In this implementation, the game space is represented as a dictionary where the keys are tuples representing the coordinates of the cells and the values are either `0` (dead) or `1` (alive).

Running the Game
----------------

To start the game, simply run the `life_on_an_infinite_plane.py` file. You will be prompted to enter the initial state of the game space by providing a string representation of the dictionary. For example:

```
{'0,0': 1, '0,1': 1, '1,0': 1}
```

This will create a game space with three live cells in a row.

After entering the initial state, the game will begin and you will be shown the state of the game space after each generation. Press `Ctrl+C` to exit the game.

Contributing
------------

We welcome contributions to this project! If you have an idea for a new feature or have found a bug, please submit an issue or pull request.

License
-------

This project is licensed under the MIT License - see the `LICENSE` file for details.

Privacy
-------

This project does not collect any personal information. All interactions with the game are anonymous.

Acknowledgments
---------------

