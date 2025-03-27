# CHECKERS/DRAUGHT GAME USING C
This repository contains a complete implementation of the classic Checkers (Draughts) board game written in C. The program features a console-based interface with color-coded game pieces and supports all standard Checkers rules, including mandatory jumps, king promotions, and win condition detection.

# Key Features
A multiplayer game which supports human vs. human gameplay with customizable player names.
It has a visual board representation includes Color-coded ASCII display with coordinate system (A-H columns, 1-8 rows).
Error handling for Input validation which includes comprehensive checks for valid moves and positions

# Game logic
Standard movement rules for regular pieces (forward diagonal movement only)
King piece implementation with bidirectional movement.
Mandatory jump captures.
Automatic king promotion when reaching the opposite end of the board.
Game automatically ends when one player captures all opponent pieces.

# Technical Implementation
Structured using modular functions for game logic, display, and input handling.
Utilizes a global struct to maintain game state and player information.
Implements recursive functions for position validation and move processing.
Features ANSI color codes for enhanced visual distinction between pieces.
Includes proper boundary checking and error handling.

# How to Play
Players enter their names and choose symbols (X/O).
Player 1 (top pieces) moves first.
Players take alternate turns entering the Current piece position (e.g., "A3") and Movement direction (numbered options).
The game continues until one player captures all opponent pieces

This project uses C programming concepts including structures, recursion, array manipulation, and console I/O handling. The code follows procedural programming principles while maintaining clear separation of concerns between game logic, display, and input processing.
