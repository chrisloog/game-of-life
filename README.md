# Game of Life

This is a simple implementation of the Game of Life in Java. The Game of Life is a cellular automaton created by John Conway in 1970. It consists of a grid of cells, each of which can be in one of two states: alive or dead. The game progresses in discrete steps, where the state of each cell at each step is determined by the states of its eight neighbors according to a set of rules.

Installation

To run the Game of Life, you will need to have Java installed on your computer. You can download the latest version of Java from the official website.

Once you have Java installed, you can compile and run the Game of Life using the following commands:

> javac GameOfLife.java
> java GameOfLife

# Usage

When you run the Game of Life, a window will appear showing a grid of cells. You can click on a cell to toggle its state between alive and dead. From then you can click Start which continues until there are no more cells or you can click Next Frame.

# Rules

The rules of the Game of Life are simple:

Any live cell with fewer than two live neighbors dies, as if by underpopulation.
Any live cell with two or three live neighbors lives on to the next generation.
Any live cell with more than three live neighbors dies, as if by overpopulation.
Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.