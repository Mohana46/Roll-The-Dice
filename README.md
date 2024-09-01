# Two-Player Dice Game

## Overview

This is a two-player dice game built with HTML, CSS, and JavaScript. The objective of the game is to be the first player to reach or exceed a certain score (default is 10 points). Players take turns rolling a dice to accumulate points. Rolling a 1 causes the player to lose their turn, and they can choose to "hold" their score to add it to their total. The game can be reset to start a new round.
## Demo

You can try out the game by visiting the following link:

[Live Demo](https://roll-rush.onrender.com)

## How to Play

1. **Roll the Dice**: The active player clicks the "Roll Dice" button to roll the dice.
   - If the roll is anything other than 1, the number is added to the current score.
   - If the roll is 1, the current score is lost, and the turn passes to the other player.
2. **Hold the Score**: The active player can click the "Hold" button to add the current score to their total score and pass the turn to the other player.
3. **Winning the Game**: The first player to reach or exceed 10 points wins the game.
4. **Start a New Game**: Click the "New Game" button to reset the scores and start a new round.

## Features

- **Two-Player Gameplay**: Alternates between two players, allowing each to roll the dice or hold their score.
- **Score Management**: Tracks both the current score for each turn and the total score for each player.
- **Win Condition**: Automatically ends the game and declares a winner once a player reaches the target score.
- **Game Reset**: A "New Game" button allows players to reset the game at any time.

## Technologies Used

- **HTML**: Provides the structure for the game.
- **CSS**: Styles the game elements for a better user experience.
- **JavaScript**: Handles the game logic, including dice rolls, score management, and player turns.

## Project Structure

```plaintext
two-player-dice-game/
│
├── index.html      # The main HTML file
├── style.css       # The CSS file for styling
└── script.js       # The JavaScript file containing game logic


