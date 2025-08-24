# Hangman Game

## Project: Hangman Game in Java

1. Project Overview
As a team of three, we developed a classic Hangman word-guessing game in Java with two play modes:
Player vs. Computer (PvE): A single player guesses a word randomly selected by the computer.
Player vs. Player (PvP): One player enters a word, and the other player attempts to guess it.

2. Key Features

Two gameplay modes (PvE and PvP)
Dynamic word bank with categories (e.g., animals, programming terms)
Graphical ASCII art for hangman stages
Real-time feedback on guesses and game progress
Input validation and error handling

3. OOP Concepts and Techniques Applied

Encapsulation: Used private fields with getter/setter methods to manage game state (e.g., HiddenWord, GuessCount).
Inheritance: Implemented a base GameMode class extended by PvEMode and PvPMode for modular code.
Polymorphism: Overrode methods like startGame() in subclasses to support different modes.
Exception Handling: Custom exceptions for invalid inputs (e.g., repeated guesses, non-letter characters).
Collections Framework: Used ArrayList for storing guessed letters and HashSet for word banks.
File I/O: Read words from text files to populate the game’s word bank.

4. Team Collaboration

Designed UML diagrams for class structure and workflow.
Used Git for version control and collaborative coding.
Divided tasks: one member focused on game logic, another on UI/ASCII art, and the third on input handling and mode switching.

5. Learning Outcomes

Strengthened Java programming skills and OOP design.
Gained experience in collaborative software development.
Improved problem-solving abilities through algorithm design (e.g., word masking, guess validation).
