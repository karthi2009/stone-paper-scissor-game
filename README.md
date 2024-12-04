This program implements a Rock, Paper, Scissors game in C, where the user plays against the computer. The game uses random number generation for the computer's choice and keeps track of the scores throughout the game.
Global Variables:

usrScore and compScore: Keep track of the user's and computer's scores respectively.
Function checkOptions:

Compares the user's choice and the computer's choice.
Updates the scores based on the outcome.
Displays appropriate messages for each outcome.
Main Function:

Manages the game loop and user input.
Generates a random choice for the computer.
Gameplay Logic
The game follows these rules:

Options:

1 = Scissor
2 = Paper
3 = Rock
4 = Quit
Rules:

Scissor beats Paper.
Paper beats Rock.
Rock beats Scissor.
If the choices are the same, it’s a tie.
Outcome Calculation:

The checkOptions function:
Determines if it’s a win, loss, or tie based on the user's and computer's choices.
Updates the scores (usrScore or compScore) accordingly.
Displays the corresponding message and the current match result.
