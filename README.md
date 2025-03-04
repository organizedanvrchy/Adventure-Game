# Text-Based Adventure Game (CLI)

## Summary
This Python script is a simple text-based adventure game where the player wakes up on a mysterious island and must make choices to navigate through the environment. The game presents the player with multiple decision points, each leading to different outcomes, including finding treasure, escaping the island, or meeting an untimely end. The game uses a loop to manage the player's choices and tracks the number of attempts remaining.

## Features
- **User Input Handling**: The game uses `input()` to capture player choices and `.upper()` to standardize the input.
- **Conditional Statements**: The game employs `if`, `elif`, and `else` statements to handle different player decisions and direct the flow of the game.
- **Loop Control**: A `while` loop is used to manage the game's flow, allowing the player to make multiple choices until the game ends.
- **Nested Conditionals**: The game features nested conditional statements to handle complex decision trees, such as choosing to swim across a river or continue along a path.
- **Game State Management**: A `counter` variable is used to track the player's progress and determine the game's outcome (e.g., finding treasure, surviving, or game over).
- **Text-Based Storytelling**: The game uses `print()` statements to narrate the story and provide feedback based on the player's choices.
- **Multiple Endings**: The game offers different endings based on the player's decisions, including finding treasure, escaping the island, or meeting an unfortunate fate.

## How to Play
1. Run the script in a Python environment.
2. Follow the on-screen prompts to make choices (e.g., type `R` to go right or `L` to go left).
3. Explore the island and make decisions to uncover the treasure or escape the island.

## Requirements
- Python 3.x

## Running the Game
To run the game, simply execute the script in your Python environment:
```bash
python adventure_game.py
