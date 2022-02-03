# Grid Tile Game 💠

## Introduction

This game is an exercise in CSS Grid.

## Rules

- Click on a tile to cause its neighbours to show a different symbol.
- The aim of the game is to make all tiles display the same symbol.
- Difficulty can be increased. this adds more symbols to the mix.
- Symbols do not change randomly. They follow the following sequence:
  1. Circle (one line)
  2. 2 curved lines (two lines)
  3. Triangle (three lines)
  4. Square (four lines)
  5. Star (five points)
  6. After displaying a star, the tile loops back to displaying a circle.

## Techniques

- CSS Grid will be used to create the game board.
- Each tile will have a reference number consisting of two integers.
- Javascript will be used to manage click events:
  - Event listeners will be used to detect click events.
  - On clicking a tile the references of the neighbouring tiles will be calculated.
  - The neighbouring tiles' state will then be updated to show the next symbol in the sequence
  - All tiles will then be checked to see if they have a common symbol. If they all match, the game will end.

## Current Status

- The project has been created and roughly planned.
