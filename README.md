# Sudoku-GUI  ![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)

![python License](https://img.shields.io/badge/MADE%20WITH-Pygames-green.svg)

This Sudoku Game Is Made in Python3 using Bracktracking algorithm
This repo consists of two files It includes a graphical GUI as well as a text based version.

Run `sudokuGUI.py` to play sudoku.<br>
And `sudokusolver.py` for text based version.

**BACKTRACKING** is simply reverting back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. We will use this principle of backtracking to implement the following algorithm.

## ALGORITHM

Starting with an incomplete board:

1. Find some empty space
2. Attempt to place the digits 1-9 in that space
3. Check if that digit is valid in the current spot based on the current board
4. *a.* If the digit is valid, recursively attempt to   fill the board using steps 1-3.<br>
 *b.* If it is not valid, reset the square you just filled and go back to the previous step.
5. Once the board is full by the definition of this algorithm we have found a solution.

we will finish the algorithm and continue to understand by running through our code step by step. We will use a recursive function to implement the algorithm 
In part 2 (look below) we will implement the entire algorithm with the GUI to show the visuall implimentaion of the game.

Hope You Will Like The Game. also u can use the code to make your own version of game.

### DEMO - sudokuGUI.py
![sudokudemo](https://user-images.githubusercontent.com/91308138/161383210-7c0cf10f-9c40-4ab7-b92c-473c09a99f5d.gif)

###  DEMO - sudokusolver.py
```
7 8 0  | 4 0 0  | 1 2 0
6 0 0  | 0 7 5  | 0 0 9
0 0 0  | 6 0 1  | 0 7 8
---------------------
0 0 7  | 0 4 0  | 2 6 0
0 0 1  | 0 5 0  | 9 3 0
9 0 4  | 0 6 0  | 0 0 5
---------------------
0 7 0  | 3 0 0  | 0 1 2
1 2 0  | 0 0 7  | 4 0 0
0 4 9  | 2 0 6  | 0 0 7
________xxxxxxx SOLVED xxxxxxxxxxxx_____
7 8 5  | 4 3 9  | 1 2 6
6 1 2  | 8 7 5  | 3 4 9
4 9 3  | 6 2 1  | 5 7 8
---------------------
8 5 7  | 9 4 3  | 2 6 1
2 6 1  | 7 5 8  | 9 3 4
9 3 4  | 1 6 2  | 7 8 5
---------------------
5 7 8  | 3 9 4  | 6 1 2
1 2 6  | 5 8 7  | 4 9 3
3 4 9  | 2 1 6  | 8 5 7
```
PLEASE FEEL FREE TO FORK THE PROJECT AND START CONTRIBUTING. :)

### Module used
python modules
```
import pygame
```
### How to Play the game:
Click a box and hit the number on your keybaord to pencil in a number. To confirm that value press the `ENTER key` on that box. To delete a pencil in you can click `DELETE` or `BACKSPACE key`. Finally to solve the board press `SPACEBAR`, sit back and watch the algorithm run.

## PRE-REQUISITES
Your laptop with python 3.6.x (onwards) installed.

**NOTE:** Those with Linux and MacOSX would have Python installed by default, no action required.

Windows: Download the version for your laptop via https://www.python.org/downloads/

**NOTES**
In your preferred editor, make sure indentation is set to "4 spaces".

* Make sure you have **pygame** installed in python otherwise code may fail, to install pygame in your machine > open python in your terminal then type `pip install pygame` to install. :warning:

---

## Run using Python3.8+
1. Clone or download repositiory: https://github.com/arevish/Sudoku-solver-GUI.git
2. In source folder, run `python3 'sudokuGUI.py'` to start program, optionally, run with `--help` argument to see other runtime options.
 
### ThankYou!
