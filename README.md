# Tic Tac Toe Game

A simple command-line Tic Tac Toe game implemented in Python. This program allows two players to play the game by taking turns.

## Features
- Two-player game with turn-based input.
- Clear display of the game board after each turn.
- Win detection for rows, columns, and diagonals.
- Displays the winner and ends the game upon winning or a tie.

---

## How to Run the Game

1. Make sure Python is installed on your system. If not, download it from [python.org](https://www.python.org/).
2. Clone this repository to your local system:
   ```bash
   git clone https://github.com/username/repository-name.git
3.Navigate to the project directory:
  cd Tic-Tac-Toe
4.Run the game using:
  python TicTacToe.py

----------
### How to Play
1.The game starts with Player X's turn.
2.The board positions are represented by numbers 0-8 as shown below:
0 | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8

3.Each player takes turns to choose a position by entering the corresponding number.
4.The game board updates after every move.
5.The first player to get three in a row (horizontally, vertically, or diagonally) wins.

---------
### Sample Output
Starting the Game:
Welcome to Tic Tac Toe
0 | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8
X's Chance
Please enter a value: 0
Updated Board After X's Turn:
X | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8
O's Chance
Please enter a value: 4
Winning Message:
X Won the match
Match over

-----
### Code Explanation
sum(a, b, c)
A helper function to calculate the sum of three values for win detection.

printBoard(xState, zState)
This function prints the current state of the board. It replaces numbers with X or O based on the moves made by the players.

checkWin(xState, zState)
Checks all possible winning combinations:

Horizontal: [0, 1, 2], [3, 4, 5], [6, 7, 8]

Vertical: [0, 3, 6], [1, 4, 7], [2, 5, 8]

Diagonal: [0, 4, 8], [2, 4, 6]
Returns:

1 if Player X wins.
0 if Player O wins.
-1 if no winner yet.
Contributing
If you would like to contribute to this project:

1.Fork the repository.
2.Create a new branch for your feature:

  git checkout -b feature-name
3.Commit your changes:

  git commit -m "Add your message here"
4.Push your changes:

  git push origin feature-name
5.Open a Pull Request.



