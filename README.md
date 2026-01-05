# Introduction
PolyominoApp is a simple java Swing application designed to solve and visualize polyominoes tiling.\
[Polyominoes](https://en.wikipedia.org/wiki/Polyomino) are planar polyforms whose cells are squares.

An interesting problem related to polyominoes is the rectangle tiling, an exact cover problem that can be solved efficiently by Donald Knuth's [Dancing Links (DLX) algorithm](https://arxiv.org/abs/cs/0011047).

# Running PolyominoApp
Just run [ant](https://ant.apache.org/) to build and run PolyominoApp application.

# Features
On the left panel, users can:

♦ Set the board size effortlessly using spin controls for rows and columns. \
♦ Choose which polyomino pieces to include from an organized checklist, from small shapes to complex pentominoes. \
♦ Start solving instantly with a prominent "Solve Board" button.

The main workspace on the right showcases the solution in a large, colorful grid where each polyomino is displayed in a distinct color, making it easy to visually identify pieces at a glance.

# Screenshot
This is an example of solution after pushing "Solve Board" button:

![Screenshot](images/polyomino_solver.png)
