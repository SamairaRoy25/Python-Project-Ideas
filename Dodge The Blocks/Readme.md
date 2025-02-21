Dodge the Falling Blocks Game
This is a simple arcade-style game built using Python and the Pygame library. The objective of the game is to control a red player block and avoid falling blue enemy blocks. As you progress, the game becomes faster, making it more challenging.

Game Features
Player Movement:

Use the arrow keys to move the red player block left or right.
Falling Blocks:

Blue blocks fall from the top of the screen, and you must dodge them.
Dynamic Difficulty:

The speed of falling blocks increases as your score increases.
Scoring System:

You earn points as you survive, with your score displayed on the screen.
Gameplay Instructions
Run the Game:

Ensure you have Python and Pygame installed.
Execute the game by running the Python script:
bash
Copy
Edit
python game.py
Controls:

Left Arrow Key: Move the player block to the left.
Right Arrow Key: Move the player block to the right.
Goal:

Avoid collisions with the blue blocks to keep the game running.
The game ends when a blue block collides with the red player block.
Setup and Installation
Requirements:

Python 3.x
Pygame library
Install Pygame: Run the following command in your terminal or command prompt to install Pygame:

bash
Copy
Edit
pip install pygame
Download the Code:

Clone or download this repository to your local machine.
Run the Game:

Execute the script using:
bash
Copy
Edit
python game.py
Code Overview
Main Components
Player Movement:

Handles the player's horizontal movement using the left and right arrow keys.
Enemy Blocks:

Enemy blocks are randomly generated and fall from the top of the screen.
Collision Detection:

The game checks if the player block collides with any enemy block to end the game.
Dynamic Speed Adjustment:

The speed of the falling blocks increases as the player's score increases.
File Structure
game.py - The main script containing the game logic.
Potential Enhancements
Add more enemy types with different sizes and speeds.
Include power-ups for the player, such as temporary invincibility or slow motion.
Add a leaderboard to store high scores.
Introduce sound effects and music for a more engaging experience.