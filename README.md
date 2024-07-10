# Number Guessing Game

This project is a simple number guessing game implemented in C. The program generates a random number between 1 and 100, and the user tries to guess the number with hints provided by the program.

## Features

- Generates a random number between 1 and 100.
- Provides hints if the guessed number is higher or lower than the generated number.
- Counts the number of attempts taken to guess the number correctly.

## Technologies Used

- **C**: The programming language used to implement the game.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vishwas567917/number-guessing-game.git
2. Navigate to the project directory:
   ```bash
   cd number-guessing-game
3. Compile the code using a C compiler:
   ```bash
   gcc -o guessGame guessGame.c
4. Run the executable:
   ```bash
   ./guessGame
Usage
1. Run the program.
2. Follow the prompt to guess the number between 1 and 100.
3. The program will provide hints if your guess is higher or lower than the generated number.
4. Keep guessing until you find the correct number.
5. The program will display the number of attempts taken to guess the number correctly.

File Structure
guessGame.c: Main C file containing the number guessing game implementation.
Example Output
Guess the number between 1 to 100
50
Lower number please!
25
Higher number please!
30
Higher number please!
35
You guessed in 4 attempt

Additional Code
Included in this repository is another simple program to generate and print a random number between 1 and 100.

Example
1. Compile the code:
   ```bash
   gcc -o generateNumber generateNumber.c
2. Run the executable:
   ```bash
   ./generateNumber
3.The program will print a randomly generated number between 1 and 100.

