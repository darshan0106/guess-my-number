
# Guessing Number Game

Welcome to the Guessing Number Game repository! This project is a simple game where players try to guess a randomly generated number.

## About the Code

This game is implemented using **JavaScript**, a popular programming language for web development. Here's a brief overview of the code:

- **Random Number Generation**: The secret number that the player needs to guess is generated using the `Math.random()` function provided by JavaScript's Math object.

- **Event Listeners**: The game listens for user input using event listeners. When the player clicks the "Check" button, the game evaluates the guess and provides feedback.

- **Game Logic**: The game logic includes checking if the guess is correct, too high, or too low. It also manages the player's score and high score.

- **DOM Manipulation**: The Document Object Model (DOM) is manipulated to update the game interface in response to user actions and game events.

## How to Play

1. **Objective**: Guess the correct number.
2. **Rules**:
   - You have 20 attempts to guess the number.
   - After each guess, you will be notified if your guess is too high, too low, or correct.
   - The game ends when you either guess the correct number or run out of attempts.
3. **Scoring**:
   - Each correct guess earns you points.
   - Your highest score achieved during a session is recorded as the high score.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/guessing-number-game.git
