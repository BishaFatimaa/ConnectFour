# Connect 4 Game

This is a simple implementation of the classic Connect 4 game in C++. Below, you'll find a brief overview of the game, its rules, and how to play it.

## Introduction

Connect 4 is a two-player connection game in which the players choose a color and then take turns dropping one colored disc from the top into a seven-column, six-row grid. The pieces fall straight down, occupying the lowest available space within the column. The object of the game is to connect four of one's discs of the same color next to each other vertically, horizontally, or diagonally before your opponent.

## How to Play

1. The game is played on a 7x6 grid.
2. Players take turns to drop their colored discs into a column of their choice.
3. The disc will occupy the lowest available space in that column.
4. The game ends when one player successfully connects four of their discs in a row, either vertically, horizontally, or diagonally.
5. If all 42 spaces are filled without a player connecting four discs, the game ends in a draw.

## Running the Game

To run this Connect 4 game:

1. Make sure you have a C++ compiler installed on your system.
2. Clone this repository or download the source code.
3. Compile the code using your C++ compiler (e.g., `g++ connect4.cpp -o connect4`).
4. Run the compiled program (e.g., `./connect4`).

## Game Controls

1. Players take turns to input the column number (0-6) where they want to drop their disc.
2. The game will display the current state of the board and update after each move.
3. The game will announce the winner or declare a draw when the game ends.

Enjoy this simple and fun implementation of Connect 4!

**Note:** This is a console-based version of Connect 4. It can be enhanced and expanded with graphical interfaces or additional features if desired. Have fun playing and feel free to modify and improve the game as you like!
