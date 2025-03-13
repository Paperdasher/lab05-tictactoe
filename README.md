# Lab05-TicTacToe

In this lab, you will create a n*n tic tac toe board and have the user play against the computer(random placement).
Test each function individually to debug easier, and ensure each algorithm/code is working.

## Functions

```
createBoard(n)- Creates a n*n board.
userInput(input)- Takes user input of where they would like to place next mark. If invalid slot, ask user again.
computerChoose()- Randomly chooses empty slot to mark.
checkWin(board, player)- Checks board to see if either player has won
isBoardFull(board)- Checks if board is full(i.e. draw)
printBoard(board)- Prints full board, used after every turn

main()
- Wrapper function, prints the board each move(user and computer) via printBoard function.
- Also lets user keep playing repeatedly and keeps track of score.
```
