# tictactoe-j
We are going to create a Tic-Tac-Toe game.

We are going to build it in three phases.

Phase 1: Build the two dimensional array and print the game board

Phase 2: Game logic to prompt Player X and Player O to enter a row and column to place their move, and logic to determine who won or if it was a draw

 

For Phase 1: 

There will be two java files: TicTacToe.java and PlayTicTacToe.java

TicTacToe.java will contain all the logic for the game.

PlayTicTacToe.java will be the program itself that instantiates and runs the game.

You will need the following:

- Two dimensional char array
- Default constructor to initialize that array to be 3 x 3
- A method called "printBoard()" to print the game board to the terminal

Need to be able to iterate through the two dimensional array to print moves if made

The printed board should look like the following:

 _______________________ 
|       |       |       |
|       |       |       |
|_______|_______|_______|
|       |       |       |
|       |       |       | 
|_______|_______|_______|
|       |       |       |
|       |       |       |
|_______|_______|_______|
There should be 7 spaces between the vertical pipes if the square is blank or 3 spaces on either side of a "X" or "O" if not.

Phase 2:
- Alternating Prompt for Player "X" and Player "O" to move.
- Ask the user which position they would like to place their token
- Verify that is an open space in the 2D array
- If not, re-prompt for location
- If valid move, update the array
- Print the updated board after every move
- Check to see if a player has won
- If a player won, print the board with a congratulations message
- If the board is full and no winner, declare a draw
- If no winner and no draw, then ask the next player to move
- Continue until either win or draw