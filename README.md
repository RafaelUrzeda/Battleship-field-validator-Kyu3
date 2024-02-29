# Instruction

Write a method that takes a field for the well-known board game "Battleship" as an argument and returns true if it has a valid disposition of ships, false otherwise. The argument is guaranteed to be a 10x10 two-dimensional array. Elements in the array are numbers, 0 if the cell is free and 1 if occupied by a ship.

Battleship (also known as Battleships or Sea Battle) is a guessing game for two players. Each player has a 10x10 grid containing several "ships," and the objective is to destroy the enemy's forces by targeting individual cells on their field. The ship occupies one or more cells in the grid. The size and number of ships may differ from version to version. In this kata, we will use the Soviet/Russian version of the game.

Before the game begins, players set up the board and place the ships according to the following rules:

1. There must be a single battleship (size of 4 cells), 2 cruisers (size 3), 3 destroyers (size 2), and 4 submarines (size 1). Any additional ships are not allowed, as well as missing ships.
2. Each ship must be in a straight line, except for submarines, which are just a single cell.
3. The ship cannot overlap or be in contact with any other ship, neither by edge nor by corner.

This is all you need to solve this kata.
