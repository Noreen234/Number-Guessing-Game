# Number-Guessing-Game

## Extensions/Platforms:
[Python 3.x](https://www.python.org/downloads/)

## How to Play:

- Run the Python script, and the game will start.

- The program will generate a random number between 1 and 5 (inclusive) that you need to guess.

- You will be prompted to input your guess. Enter a number between 1 and 5.

- The program will inform you if your guess is correct or incorrect.

- You have a maximum of 7 attempts to guess the correct number.

- Keep guessing until you guess correctly or exhaust all attempts.

- After the game ends, it will display a "Game over!" message if you've used up all your attempts.

- Regardless of the outcome, the program will thank you for playing.

## Description:

- The program uses the random module to generate a random integer between 1 and 5, representing the number to be guessed. The user is prompted to input their guess, and the program compares the input with the random number.

  If the user's guess matches the random number, it displays a success message and ends the game.
  
  If the guess is incorrect, the program allows the user to continue guessing, providing feedback on whether the guess was too high or too low.
  
  The user has a maximum of 7 attempts to guess the correct number. If they don't guess correctly within the allowed attempts, the game ends, and it displays a "Game over!" message.
