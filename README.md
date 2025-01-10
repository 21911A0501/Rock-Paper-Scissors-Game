The Java Program: Rock-Paper-Scissors Game
This Java program is a simple implementation of the classic Rock-Paper-Scissors game where the player competes against the computer in a best-of-five matches tournament. The program uses the Scanner class for user input and the Random class to generate random moves for the computer.

Features of the Program
Player Choices: The player can choose from the following options:

1 for Rock
2 for Paper
3 for Scissors
Computer Choices: The computer randomly selects one of the three options for each match.

Game Logic:

The program checks the player's and computer's moves and decides the winner based on the rules:
Rock beats Scissors.
Paper beats Rock.
Scissors beats Paper.
A tie occurs if both make the same move.
Match Outcome:

After each match, the program announces whether the player won, lost, or tied the game.
Tournament Outcome:

After five matches, the program calculates the total points for the player and the computer.
It announces the final result:
Player wins the tournament.
Computer wins the tournament.
The tournament is a draw.


How It Works
The player is prompted to enter a choice (1, 2, or 3) for each match.
The computer randomly generates a choice using the Random class.
The program compares the player's choice with the computer's choice to determine the winner.
Points are awarded accordingly:
Player wins: Player gets 1 point.
Computer wins: Computer gets 1 point.
Tie: No points are awarded.
At the end of the 5 matches, the program displays the total points and the final result.


Key Concepts Used
Loops: The for loop iterates over 5 matches.
Conditionals: if statements handle game logic to determine the winner.
Random Number Generation: The Random class is used to simulate the computer's move.
Input Handling: The Scanner class takes input from the player.
