# VITYARTHI-PROJECT-01-GAME
# Rock-Paper-Scissors 🎮

A simple command-line **Rock-Paper-Scissors** game written in Python.

I made this project as a small and beginner-friendly Python program to
practice things like user input, `if-elif-else` conditions, loops,
lists, and Python's built-in `random` module. The idea is simple: you
choose Rock, Paper, or Scissors, and the computer randomly makes its
choice. The program then tells you who won.

## How the Game Works

The rules are the usual Rock-Paper-Scissors rules:

-   🪨 Rock beats Scissors
-   📄 Paper beats Rock
-   ✂️ Scissors beats Paper
-   If both choices are the same, it's a tie

The game keeps running until the player chooses **N** when asked whether
they want to play again.

## Features

-   Simple command-line interface
-   Computer makes a random choice each round
-   Checks whether the user's input is valid
-   Displays both the user's and computer's choices
-   Detects wins, losses, and ties
-   Allows the player to play multiple rounds

## Technologies Used

-   **Python 3**
-   Python's built-in `random` module

No external libraries are required.

## How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

You can check by running:

``` bash
python --version
```

### 2. Run the program

Open a terminal in the folder containing the Python file and run:

``` bash
python "#rock-paper scissor.py"
```

## How to Play

When the game starts, you'll see the three available options:

``` text
1 - Rock
2 - Paper
3 - Scissors
```

Enter the number for your choice.

For example:

``` text
Enter your choice: 1

User choice is: Rock
Now it's Computer's Turn...
Computer choice is: Scissors
Rock vs Scissors
<== User wins! ==>
```

After each round, the program asks:

``` text
Do you want to play again? (Y/N):
```

Enter `Y` to continue playing or `N` to stop.

## Input Validation

The program also handles incorrect input. If you enter something that
isn't a number, it asks you to enter a valid number.

It also makes sure the selected number is between **1 and 3**.

## Project Structure

``` text
.
├── #rock-paper scissor.py
└── README.md
```

## What I Learned

This project helped me practice some basic but important Python
concepts:

-   Importing and using a module with `random`
-   Working with lists
-   Taking input from the user
-   Using `try-except` for basic input validation
-   Using `while` loops
-   Using conditional statements
-   Comparing values to decide the winner
-   Creating a program that can keep running until the user decides to
    quit

## Future Improvements

There are a few things I could add to make the game more interesting in
the future:

-   Keep track of the player's score
-   Keep track of the computer's score
-   Add a best-of-3 or best-of-5 mode
-   Add more visual effects to the terminal
-   Improve the input system so the player can enter words like `rock`,
    `paper`, or `scissors`
-   Add difficulty levels

## Author

Created as a beginner Python project to practice programming
fundamentals.

------------------------------------------------------------------------

**Thanks for checking out the project! 🎮**
