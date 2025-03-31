# Connect 4 - Player Management System

This project is an implementation of the classic Connect 4 game, extended with user management capabilities. It was developed in C++ as part of the Programming I course at CUNEF University (Bachelor's Degree in Computer Engineering, 2022/2023 academic year).

## Features

- Two-player Connect 4 game (6 rows x 8 columns)
- Player registration and login using a nickname
- Persistent storage of player statistics (wins and losses) in a text file (`jugadores.txt`)
- Console-based graphical display of the game board
- Menu-driven interface:
  - Play a game
  - View current player information
  - View all registered players
  - Search for a specific player

## Technical Details

- Use of `struct` and `enum` for data management
- Modular implementation with clearly separated functions
- Input/output operations with `fstream`
- Console color output using the Windows API (`Windows.h`)
- Input validation and basic error handling

## Compilation and Execution

This program is designed to run on Windows systems due to its dependency on the Windows console API.

