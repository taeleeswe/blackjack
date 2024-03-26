# Blackjack Game

This Python script implements a simple text-based version of the popular card game, Blackjack. Below is a brief overview of the project's functionality and usage.

## Project Structure:

- **`blackjack.py`**: This is the main Python script containing the game logic. It includes functions for dealing cards, calculating scores, comparing scores, and playing the game.
- **`art.py`**: This module contains ASCII art used for the game's logo.

## Features:

- **Unlimited deck size**: The deck of cards used in the game is unlimited in size, ensuring that cards are not removed as they are drawn.
- **Standard rules**: The game follows standard Blackjack rules, with face cards (Jack, Queen, King) valued at 10 and Aces valued at either 1 or 11.
- **User interaction**: Players are prompted to decide whether to draw another card ('hit') or pass ('stand') based on their current hand.
- **Computer dealer**: The computer serves as the dealer, following a simple set of rules for drawing cards.
- **Game outcome**: The game determines the winner based on Blackjack rules and prints the result.

## How to Run:

1. Ensure you have Python installed on your system.
2. Download or clone the project repository.
3. Navigate to the directory containing the Python scripts.
4. Run the `blackjack.py` script using the command: `python blackjack.py`.
5. Follow the on-screen prompts to play the game.

## Dependencies:

- The script uses the `random` module for card shuffling and dealing.
- It also utilizes the `os` module to clear the terminal for better user experience.
- ASCII art for the game's logo is stored in a separate module (`art.py`).

## Screenshot

![Screenshot 2024-03-26 at 9 59 15 AM](https://github.com/taeleeswe/blackjack/assets/123449246/8badd486-25ec-4a0b-a8a4-f001d27a44ba)
