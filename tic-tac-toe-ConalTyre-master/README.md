# Tic-Tac-Toe
## Tic Tac Toe Challenge for Week 5

- This is a skeleton code for the Tic Tac Toe Challenge
You need to update the two functions inside TicTacToe.cpp, the functions are:
```
void PlayGame(char square[], int &choice, int &player, char mark)
```
This is a function for playing the tic-tac-toe game, users will input in the box no, and the program will update the box with mark based on the player id (Player 1 / Player 2). Invalid box no will be ignored and user will input a new box no. Please look at the do...while loop in the main function to understand the flow of the program.

```
void CheckWin(char square[], int &result)
```
This is a function to check the completion of the game. If there is a line, then the program will end with result = 1, if all boxes are ticked without any winner, then result = 0, and if the game continues, result = -1.

