# Number_Guessing_Game using Python

Number Guessing Game is a beginner-friendly Python project that helps you test your intuition by guessing a randomly generated number within a specified range.

## Features

* Randomly generates a hidden number for every game session.
* Keeps track of the total number of attempts made by the player.
* Provides helpful hints telling you if your guess is too high or too low.
* Great project for learning Python random module, loops, and conditional logic.

## Technologies Used

* Python 3
  * Built-in libraries (`random`)

## How It Works

The script utilizes Python's built-in `random` module to select a secret number. It runs a `while` loop to repeatedly prompt the user for input, checking each guess against the secret number and giving instant feedback until the correct number is found.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com
   ```

2. Navigate to the project folder:
   ```bash
   cd Number-_Guessing_Game
   ```

3. Run the program:
   ```bash
   python guessing_game.py
   ```

   ## Example GamePlay

   ```text
Welcome to the Number Guessing Game!
Enter your guess (1-100): 50
Too low! Try again.
Enter your guess (1-100): 75
Too high! Try again.
Enter your guess (1-100): 63
Correct! The number was 63.
You guessed it in 3 attempts.
```






